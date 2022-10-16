# Desafio de Projeto da DIO - Construindo um Esquema Conceitual para Banco De dados

Para este projeto, aplico os conceitos de modelagem de banco de dados vistos anteriormente na seção Bancos de Dados SQL e NoSql do bootcamp Geração Tech Unimed-BH - Ciência de Dados.

# Objetivo do desafio:

Criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida.

**Narrativa:**

* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
* O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
* A mesma equipe avalia e executa os serviços
Os mecânicos possuem código, nome, endereço e especialidade
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

[Link do diagrama refinado](https://github.com/casjunior93/DIO---Refinando-um-Projeto-Conceitual-de-Banco-de-Dados-E-COMMERCE/raw/main/E-commerce/diagrama-e-commerce-aula-refinado.png) {:target=”_blank “}