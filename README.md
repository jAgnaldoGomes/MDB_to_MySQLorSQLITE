# MDB to MySQL or SQLITE(3)

Cria um arquivo ( .sqlite ou script mysql ) a partir de um mdb ( 2003 a 2019 )


Histórico
---------

Em 01/04/2022 <a href="https://github.com/jAgnaldoGomes/MDB_to_MySQLorSQLITE/tree/v3.0401">v3.22.0401</a>

-	implementado *dialog de entrada* para:
> - seleção do arquivo MDB de entrada.<br>
> - seleção do arquivo SQLITE(3)/Script MySQL de saída.
-	implementado *formulário de seleção* para:
> - marcação das tabelas que desejar no procedimento.<br>
> - marcação das consultas que desejar no procedimento.<br>
>caso haja alguma consulta que não for possível gerar a VIEW correspondente, <br>será listada no log de execução do aplicativo, com instruções para ajustes,<br>
>assim como também os erros encontrados durante a execução.
