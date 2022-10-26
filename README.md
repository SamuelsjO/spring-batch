# batch MultithreadingStep


rodar o comando docker

  - docker run -e MYSQL_ROOT_PASSWORD=root --name meu-mysql -d -p 3306:3306 mysql:8.0


Abrir gerenciador de banco de dados(workbench) e criar uma banco dados_bancariodb

executar o sql abaixo:


    DROP TABLE IF EXISTS pessoa;
    CREATE TABLE pessoa(id INT, nome VARCHAR(500),email VARCHAR(500),data_nascimento DATETIME,idade INT, PRIMARY KEY(id));
    DROP TABLE IF EXISTS dados_bancarios;
    CREATE TABLE dados_bancarios(id INT, pessoa_id INT,agencia INT, conta INT, banco INT , PRIMARY KEY(id));


Criar um banco pessoadb.
