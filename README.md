# Roteiro de teste


##Testes:
###Banco de dados:
####Preparação
executar o script: pessoas_mysql.sql que cria uma tabela no banco de dados

####Teste
1 - criar um arquivo insere.sql com uma instrução sql que cadastra na tabela pessoas_mysql as seguintes pessoas e sua data de nascimento (uma instrução para cada pessoa):
* Jose 17/11/2000
* Maria 22/05/2001
* Joaquim 05/10/1999

2 - criar um arquivo mostra.sql com uma instrução sql que seleciona e retorna o nome das pessoas que tem 18 anos ou mais da tabela pessoas_mysql

###Programação com PHP:
####PREPARACAO
executar o script: pessoas_php.sql que cria uma tabela no banco de dados

####Teste
1 - criar um arquivo insere.php que deverá cadastrar na tabela pessoas_php as seguintes pessoas e sua data de nascimento:
* Jose 17/11/2000
* Maria 22/05/2001
* Joaquim 05/10/1999

2 - criar um arquivo mostra.php que deverá consultar o nome das pessoas que tem 18 anos ou menos da tabela pessoas_php e mostrar os nomes na tela

##Orientações:
###Banco de dados:
* utilizar MySQL
###Programação com PHP:
* poderá ser utilizada qualquer versão do PHP
* utilizar somente recursos nativos, não utilizar frameworks

Qualquer dificuldade para rodar o mysql ou o php, utilize https://www.apachefriends.org/pt_br/index.html