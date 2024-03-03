## Oque é?
*são utilizados para combinar dados de duas ou mais tabelas com base em uma condição relacionada*

## INNER JOIN
*Retorna registros que têm valores correspondentes em ambas as tabelas*

==> `SELECT tabela1.colunaTabela1, tabela2.colunaTabela2 FROM tabela1 INNER JOIN tabela2 ON tabela1.PrimaryKey = tabela2.ForeignKey;`
![[Pasted image 20240303160642.png]]


## LEFT OUTTER JOIN
*Retorna todos os registros da tabela à esquerda (primeira tabela mencionada na instrução JOIN), e os registros correspondentes da tabela à direita*

==> `SELECT tabela1.colunaTabela1, tabela2.colunaTabela2 FROM tabela1 LEFT OUTTER JOIN tabela2 ON tabela1.PrimaryKey = tabela2.ForeignKey;`
![[Pasted image 20240303161144.png]]


## RIGHT OUTTER JOIN
*Retorna todos os registros da tabela à direita (segunda tabela mencionada na instrução JOIN), e os registros correspondentes da tabela à esquerda*

==> `SELECT tabela1.colunaTabela1, tabela2.colunaTabela2 FROM tabela1 RIGHT OUTTER JOIN tabela2 ON tabela1.PrimaryKey = tabela2.ForeignKey;`
![[Pasted image 20240303161227.png]]


### Atribuição de apelidos
*A propriedade "AS" em SQL é usada para atribuir um alias (apelido) a uma tabela ou a uma coluna em uma consulta.*

==> `SELECT nomeDaColuna AS apelido FROM nomeDaTabela;` - Dessa forma pode-se atribuir apelidos com o intuito de facilitar a consulta

#### Exemplos com o JOIN

==> *INNER JOIN*
![[Pasted image 20240303161656.png]]


==> *OUTTER LEFT OR RIGHT JOIN*
![[Pasted image 20240303161758.png]]