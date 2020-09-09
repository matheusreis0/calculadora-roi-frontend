# Calculadora de ROI (frontend)
Projeto para especificar frontend de uma aplicação que calcula ROI de leads e compara o valor com os serviços do **olist**.

* Inspirado inicialmente nesta [página](https://olist.com/solucoes/como-comecar-a-vender/)


### Telas

* Para ver prints das telas e fluxo de trabalho entre elas no figma:
[telas](https://www.figma.com/proto/yMvQvtLgKBqELgwjMttYGH/calculadora-roi-frontend?node-id=33%3A2&scaling=min-zoom)

### Campos e funcionalidades
1. Tela inicial:
* Nome do responsável
* E-mail da empresa

2. Tela com calculadora
* Categoria dos produtos
* Investimentos em campanha por mês
* Ticket médio
* Volume médio de vendas por

2. Tela com resultado
* Gráfico com ROI sem o olist
* Gráfico com ROI com o olist

### Arquitetura
* Plugin para Wordpress

### Tecnologias usadas
* A calculadora fica visível no site principal do olist (olist.com), por conta disso, o projeto é desenvolvido em PHP.

### Fluxo de comunicação com API
1. Fluxo de comunicação com API e redirecionamento de telas
![](images/calculadora-roi-frontend.jpg)
