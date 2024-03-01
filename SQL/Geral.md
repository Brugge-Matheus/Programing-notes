## Conceitos

### geral

=> *Registro ou Tupla* - A linha da tabela de forma (horizontal)

=> *Campo ou Atributos* -  A coluna da tabela (vertical)
### DDL - Data Definition Language
==> `create database, create table`

### DML - Data Manipulation Language 
==> `insert into`


## Tipos primitivos de dados

### Numéricos
#### Inteiro
==> TinyInt, SmallInt, Int, MediumInt, BigInt
#### Real
==> Decimal, Float, Double, Real
#### Lógico
==> Bit, Boolean

### Data/Tempo
==> Date, DateTime, TimeStamp, Time, Year


### Literal
#### Caractere
==> Char, VarChar
#### Texto
==> TinyText, Text, MediumText, LongText
#### Binário
TinyBlob, Blob, MediumBlob, LongBlob
#### Coleção
==> Enum, Set

### Espacial
==> Geometry, Point, Polygon, MultiPolygon



## Comandos gerais

`DESCRIBE NomeDaTabela` - Mostra a estrutura da tabela

## Criando bd, table e parâmetros

### parâmetros
==> `IF NOT EXISTS` - Faz algo se aquilo não existir
![[Pasted image 20240227211825.png]]

==> `IF EXISTS` - Faz algo se aquilo existir
![[Pasted image 20240227211806.png]]
### criação

=> `CREATE DATABASE NomeDoBanco` - Cria um bd 

=> `USE NomeDoBanco` - Utiliza um bd criado

=> `CREATE TABLE NomeDaTabela ()` - Cria um tabela sql

## Inserindo dados

*Caso a ordem de inserção dos itens seja a mesma ordem de construção da tabela não precisamos definir a ordem dos itens*
=> `INSERT INTO NomeDaTabela VALUES (dados que deseja inserir);`

*Caso não seja a mesma ordem precisamos definir os registros base antes*
=> `INSERT INTO NomeDaTabela (dados base da tabela) VALUES (dados que deseja inserir);`

*Podemos inserir varios itens de uma vez só*
=> `INSERT INTO NomeDaTabela VALUES (dados que deseja inserir), (dados que deseja inserir);`


=> `(id) (default)` - Caso tenhamos passado itens como `auto_increment` podemos simplesmente não defini-los ou utilizar default.

### Ex banco
![[Pasted image 20240227143607.png]]


## Alterar dados na tabela
*Comando principal para fazer alteração em tabelas, sempre adicionada antes das funções desejadas*

=> `ALTER TABLE nomeDaTabela`

### Adicionar coluna

=> `ADD COLUMN nomeDoCampo tipoDeDado;` - Adiciona um campo a uma tabela selecionada
![[Pasted image 20240227201940.png]]

=> `ADD COLUMN nomeDoCampo tipoDeDado AFTER nomeDoCampo`; - Adiciona uma coluna após outra coluna escolhida, assim manipulando a ordem dos itens na tabela
![[Pasted image 20240227201954.png]]

=> `ADD COLUMN nomeDoCampo tipoDeDado FIRST;` - Adiciona um item por primeiro na tabela
![[Pasted image 20240227202613.png]]



### Remover coluna
*Por padrão o `drop` é utilizado para apagar itens no sql*

=> `DROP COLUMN nomeDoCampo;` - Remove uma coluna de uma tabela criada
![[Pasted image 20240227202004.png]]

### Modificar a estrutura

=> `DROP TABLE nomeDaTabela` - Apaga uma tabela
![[Pasted image 20240227211326.png]]

=> `MODIFY COLUMN nomeDaCampo tipoDeDadoeModificação ...;` - Altera a estrutura de uma coluna, como o tipo de dado as propriedades e etc...
![[Pasted image 20240227205525.png]]

=> `CHANGE COLUMN nomeAtualDaColuna novoNomeDaColuna ...;` - Muda o nome de uma coluna para outro
![[Pasted image 20240227205631.png]]

=> `RENAME TO novoNomeDaTabela` - Renomeia a tabela toda
![[Pasted image 20240227205749.png]]

==> `ADD PRIMARY KEY (#);` - Podemos definir uma coluna como a primary key dessa forma
![[Pasted image 20240227211226.png]]


## UPDATE
*Serve para atualizar registros e campos existentes em uma tabela no banco de dados*

=> `UPDATE nomeDaTabela set nomeDoCampo = 'alteraçãoDesejada' WHERE = 'condicional'` - Selecionando uma tabela depois configurando oque deseja alterar e depois fazendo a condicional podemos alterar um registro existente

![[Pasted image 20240228140342.png]]

=> `LIMIT number` - Utilizando o `limit` e depois um número, podemos limitar as alterações a um número específico de números
![[Pasted image 20240228140859.png]]


## DELETE
*Serve para deletar registros e campos existentes em uma tabela no banco de dados*

=> `DELETE FROM nomeDaTabela WHERE condicional` - Definindo a tabela e depois a condicional podemos apagar registros de uma tabela
![[Pasted image 20240228141130.png]]

=> `LIMIT number` - Também podemos usar o `limit` para limitar os registros que irão ser deletados
![[Pasted image 20240228141248.png]]


## TRUNCATE
*Serve para apagar todos os registros de uma tabela de uma vez só*

=> `TRUNCATE TABLE nomeDaTabela` - Apaga todos os registro da tabela
=> `TRUNCATE nomeDaTabela`


## SELECT
*Serve para buscar itens em uma base de dados*

=> `SELECT * FROM nomeDaTabela` - Seleciona e mostra todos os itens de uma tabela

=> `SELECT nomeDaColunan FROM nomeDaTabela` - Seleciona quais as colunas que deseja fazer a busca

==> `ORDER BY colunaDaTabela` - item opcional que seleciona a ordenação que sua busca vai ter

=> `asc` `desc` utilizado junto ao order by para definir se a ordem vai ser crescente ou não
![[Pasted image 20240229215148.png]]

### Condicional

=> `WHERE condicional...` - também se pode utilizar o where junto ao select para fazer uma condicional de busca
![[Pasted image 20240229215401.png]]

=> `WHERE IN (#,#)` - Faz a condicional baseado nos itens que estão definidos pelo in 
![[Pasted image 20240229215741.png]]

=> `WHERE BETWEEN condicional1 (operadorLógico) condicional2` - Faz a busca entre um item e outro
![[Pasted image 20240229220017.png]]

#### Operadores Lógicos
*Operados a serem utilizados dentro de uma condicional (WHERE)*

==> `OR` - Significa Ou e seleciona um item com uma condição ou outra
==> `AND` - Significa E e selecionado um item com uma condição e outra

=> `>` - Maior
=> `>=` = Maior igual
=> `<` - Menor
=> `<=` - Menor igual
=> `!=` - Diferente
## Key Primary
*São campos únicos que definem *

