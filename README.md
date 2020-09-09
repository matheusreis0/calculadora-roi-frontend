# Calculadora de ROI (frontend)
Projeto para especificar frontend de uma aplicação que calcula ROI de leads e compara o valor com os serviços do **olist**.

* Inspirado inicialmente nesta [página](https://olist.com/solucoes/como-comecar-a-vender/)

### Arquitetura
* O projeto é um plugin para Wordpress, podendo seguir até mesmo a estrutura do [Contact Form](https://wordpress.org/plugins/contact-form-7/). Lembrando que deve ficar desacoplado do código-fonte, o plugin cria uma interface nova na parte de admin, e pergunta ao usuário em qual tela deve ser implementado, após isso, mostra uma prévia e uma opção para salvar a alteração.

### Tecnologias usadas
* A calculadora fica visível no site principal do olist (olist.com), levando em conta a especificação de arquitetura, o plugin é desenvolvido em PHP. A parte de frontend é em HTML, CSS e JavaScript, ficando a par do Wordpress renderizar o código.

### Telas

* Para ver prints das telas e fluxo de trabalho entre elas no figma:
[telas](https://www.figma.com/proto/yMvQvtLgKBqELgwjMttYGH/calculadora-roi-frontend?node-id=33%3A2&scaling=min-zoom)

### Campos e funcionalidades
1. Tela inicial:

Campo | Tipo
--- | ---
Nome do responsável | string
E-mail da empresa | string, email

2. Tela com calculadora

Campo | Tipo
--- | ---
Categoria dos produtos | string
Investimentos em campanha por mês | decimal
Ticket médio | decimal
Volume médio de vendas por mês | decimal

3. Tela com resultado
* Gráfico com ROI sem o olist
* Gráfico com ROI com o olist

### Fluxo de comunicação com API
1. Fluxo de comunicação com API e redirecionamento de telas
![](images/calculadora-roi-frontend.jpg)
