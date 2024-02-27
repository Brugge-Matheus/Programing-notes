## Conceitos
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

`select * from nomeDaTabela` - Seleciona e mostra todos os itens de uma tabela

`describe NomeDaTabela` - Mostra a estrutura da tabela

## Criando bd e table 

=> `create database NomeDoBanco` - Cria um bd 

=> `use NomeDoBanco` - Utiliza um bd criado

=> `create table NomeDaTabela ()` - Cria um tabela sql

## Inserindo dados

*Caso a ordem de inserção dos itens seja a mesma ordem de construção da tabela não precisamos definir a ordem dos itens*
=> `insert into NomeDaTabela values (dados que deseja inserir);`

*Caso não seja a mesma ordem precisamos definir os registros base antes*
=> `insert into NomeDaTabela (dados base da tabela) values (dados que deseja inserir);`

*Podemos inserir varios itens de uma vez só*
=> `insert into NomeDaTabela values (dados que deseja inserir), (dados que deseja inserir);`


=> `(id) (default)` - Caso tenhamos passado itens como `auto_increment` podemos simplesmente não defini-los ou utilizar default.

### Ex banco
![[Pasted image 20240227143607.png]]


## Key Primary
*São campos únicos que definem *

