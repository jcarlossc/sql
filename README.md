# SQL
Principais instruções.

## CREATE DATABASE é usada para criar um novo banco de dados SQL.
```CREATE DATABASE nomedobandodedados;```
## USE inicializa um banco de dados.
```USE nomedobandodedados;```
## DROP DATABASE exclui o banco de dados.
```DROP DATABASE nomedobandodedados;```
## BACKUP DATABASE é usada no SQL Server para criar um backup completo de um banco de dados SQL existente.
```
BACKUP DATABASE nomedobandodedados
TO DISK = 'filepath'
```
## Um backup diferencial faz backup apenas das partes do banco de dados que foram alteradas desde o último backup completo do banco de dados.
```
BACKUP DATABASE nomedobandodedados
TO DISK = 'filepath'
WITH DIFFERENTIAL;
```
## CREATE TABLE é usada para criar uma nova tabela em um banco de dados.
```
CREATE TABLE nomedatabela (
    nomedocampo tipodedado(valor),
    nomedocampo tipodedado(valor),
    nomedocampo tipodedado(valor),
   ....
);
```
## DROP TABLE é usada para descartar uma tabela existente em um banco de dados.
```DROP TABLE nomedatabela;```
## TRUNCATE TABLE é usada para excluir os dados dentro de uma tabela, mas não a própria tabela:
```TRUNCATE TABLE `nomedatabela;```
## Continua....
