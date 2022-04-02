# MDB to MySQL or SQLITE(3)


`Em 01/04/2022`

-	implementado *dialog de entrada* para:
-	seleção do tipo de procedimento<br>
![f001](https://github.com/jAgnaldoGomes/MDB_to_MySQLorSQLITE/blob/v3.22.0401/img/f002.jpg)<br>
> - seleção do arquivo MDB de entrada.<br>
![f001](https://github.com/jAgnaldoGomes/MDB_to_MySQLorSQLITE/blob/v3.22.0401/img/f001.jpg)<br>
> - seleção do arquivo SQLITE(3)/Script MySQL de saída.
> - denominação do dbName para o script mysql.

-	implementado *formulário de seleção* para:<br>
> - marcação das tabelas que desejar no procedimento.<br>
![f001](https://github.com/jAgnaldoGomes/MDB_to_MySQLorSQLITE/blob/v3.22.0401/img/f003.jpg)<br>
> - marcação das consultas que desejar no procedimento.<br>
![f001](https://github.com/jAgnaldoGomes/MDB_to_MySQLorSQLITE/blob/v3.22.0401/img/f004.jpg)<br>
>caso haja alguma consulta que não for possível gerar a VIEW correspondente, <br>será listada no log de execução do aplicativo, com instruções para ajustes,<br>
>assim como também os erros encontrados durante a execução.
