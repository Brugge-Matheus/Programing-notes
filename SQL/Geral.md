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

`select * from nomeDaTabela` - Seleciona e mostra todos os itens de uma tabela

`describe NomeDaTabela` - Mostra a estrutura da tabela

## Criando bd, table e parâmetros

### parâmetros
==> `if not exists` - Faz algo se aquilo não existir
![[Pasted image 20240227211825.png]]

==> `if exists` - Faz algo se aquilo existir
![[Pasted image 20240227211806.png]]
### criação

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


## Alterar dados na tabela
*Comando principal para fazer alteração em tabelas, sempre adicionada antes das funções desejadas*

=> `alter table nomeDaTabela`

### Adicionar coluna

=> `add column nomeDoCampo tipoDeDado;` - Adiciona um campo a uma tabela selecionada
![[Pasted image 20240227201940.png]]

=> `add column nomeDoCampo tipoDeDado after nomeDoCampo`; - Adiciona uma coluna após outra coluna escolhida, assim manipulando a ordem dos itens na tabela
![[Pasted image 20240227201954.png]]

=> `add nomeDoCampo tipoDeDado firts;` - Adiciona um item por primeiro na tabela
![[Pasted image 20240227202613.png]]



### Remover coluna
*Por padrão o `drop` é utilizado para apagar itens no sql*

=> `drop column nomeDoCampo;` - Remove uma coluna de uma tabela criada
![[Pasted image 20240227202004.png]]

### Modificar a estrutura

=> `drop table nomeDaTabela` - Apaga uma tabela
![[Pasted image 20240227211326.png]]

=> `modify column nomeDaCampo tipoDeDadoeModificação ...;` - Altera a estrutura de uma coluna, como o tipo de dado as propriedades e etc...
![[Pasted image 20240227205525.png]]

=> `change column nomeAtualDaColuna novoNomeDaColuna ...;` - Muda o nome de uma coluna para outro
![[Pasted image 20240227205631.png]]

=> `rename to novoNomeDaTabela` - Renomeia a tabela toda
![[Pasted image 20240227205749.png]]

==> `add primary key (#);` - Podemos definir uma coluna como a primary key dessa forma
![[Pasted image 20240227211226.png]]


## UPDATE
*Serve para atualizar registros e campos existentes no banco de dados*

`UPDATE nomeDaTabela set nomeDoCampo = 'alteraçãoDesejada' WHERE = 'condicional'`

## Key Primary
*São campos únicos que definem *

