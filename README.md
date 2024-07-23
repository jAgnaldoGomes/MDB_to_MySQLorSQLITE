# MDB to MySQL or SQLITE(3)

Cria um arquivo ( .sqlite ou script mysql ) a partir de um mdb ( testado no MsAccess 2003 a 2019 )

Histórico
---------

Em 02/02/2024 `v3.24.0202`
- Ajustes na criação do script.

Em 06/06/2022 `v3.22.0606`
- Ajustes no formulário de seleção de objetos/formulário inicial.

Em 28/05/2022 `v3.22.0528`
- Adicionado formulário para edição da sentença da query antes de salvar o processo.<br>
 Formulário este que será acessado pressionando o CTRL e clicando na lista de consultas do referido mdb.

Em 08/04/2022 `v3.22.0408`
- Correção na criação de VALOR DEFAULT para os diversos tipos de DataType, uma vez que:
 Colunas do tipo BLOB, TEXT, GEOMETRY ou JSON não podem ter VALOR DEFAULT.
 
Em 06/04/2022 `v3.22.0406`
- Eliminação de objetos obsoletos / não utilizados.
- Adicionados checkbox para listar tabelas / consultas, conforme a necessidade.
- Adicionado checkbox para listar log de verificações efetuadas no script.

Em 05/042022 `v3.22.0405`
- Eliminada a geração do arquivo .sqlite quando a opção for MySQL script.
- Melhorias na codificação com a eliminação de objetos obsoletos / não utilizados.
- Ajustada a lógica de acesso aos objetos do mdb selecionado.

Em 01/04/2022 `v3.22.0401`
-	implementado *dialog de entrada* para:
> -	seleção do tipo de procedimento<br>
![f001](https://github.com/jAgnaldoGomes/images/blob/main/Mdb2SQLite/f002.jpg)<br>
> - seleção do arquivo MDB de entrada.<br>
![f001](https://github.com/jAgnaldoGomes/images/blob/main/Mdb2SQLite/f001.jpg)<br>
> - seleção do arquivo SQLITE(3)/Script MySQL de saída.
> - denominação do dbName para o script mysql.

-	implementado *formulário de seleção* para:<br>
> - marcação das tabelas que desejar no procedimento.<br>
![f001](https://github.com/jAgnaldoGomes/images/blob/main/Mdb2SQLite/f003.jpg)<br>
> - marcação das consultas que desejar no procedimento.<br>
![f001](https://github.com/jAgnaldoGomes/images/blob/main/Mdb2SQLite/f004.jpg)<br>
>caso haja alguma consulta que não for possível gerar a VIEW correspondente, <br>será listada no log de execução do aplicativo, com instruções para ajustes,<br>
>assim como também os erros encontrados durante a execução.
