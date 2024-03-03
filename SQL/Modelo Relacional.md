## Conceitos

=> *Entidades* - Uma entidade é uma representação de um conjunto de informações sobre determinado conceito do sistema, cada tabela se trata de uma entidade

=> *Atributos* - Toda entidade possui ATRIBUTOS, que são as informações que referenciam a entidade, se tratam das informações da tabela

## Relacionamento
*Define que duas ou mais entidades podem se relacionar*

### D.E.R - Diagrama Entidade Relacionamento

==> Exemplo de diagrama entidade relacionamento
![[Pasted image 20240303134100.png]]

### Cardinalidade
*A cardinalidade em bancos de dados refere-se à relação entre as tabelas, especificamente ao número de registros em uma tabela*

#### Classificação

=> *Muitos para muitos* N:N - Este tipo de relacionamento ocorre quando múltiplas linhas em uma tabela podem estar relacionadas com múltiplas linhas em outra tabela

=> *Um para um* 1:1 - Neste tipo de relacionamento, cada linha em uma tabela está associada a uma única linha em outra tabela, e vice-versa.

=> *Um para muitos* 1:N - Neste tipo de relacionamento, uma linha em uma tabela está associada a uma ou mais linhas em outra tabela, mas cada linha na segunda tabela está associada a apenas uma linha na primeira tabela.


## Keys

### Primary Key (Chave Primária)
*Uma chave primária é uma coluna ou um conjunto de colunas que identifica de forma única cada linha em uma tabela.*

### Foreign Key (Chave Estrangeira)
*Se trata de uma chave primária vinda de outro lugar*

## Exemplos de relacionamento

### 1:1
![[Pasted image 20240303140856.png]]

### 1:N
*Pega a chave do lado 1 e joga para o lado foreign*
![[Pasted image 20240303141012.png]]

### N:N
*Desmembrar o relacionamento criando assim vários relacionamentos 1:N*
![[Pasted image 20240303141435.png]]




  

