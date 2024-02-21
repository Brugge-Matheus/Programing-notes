## Display
`display: inline;`  - Deixa itens que estavam separados padronizados para uma linha
antes:
![[Pasted image 20231227145846.png]]
depois:
![[Pasted image 20231227145904.png]]

`display: block;`  - Deixa os elementos da mesma forma que um paragrafo 
antes:
![[Pasted image 20231227150108.png]]
depois:
![[Pasted image 20231227150122.png]]


`Display: none;`  - Remove o visual de um item fazendo ele desaparecer

## Float
`Float: left;`  - Serve para definir o posicionamento de um item
antes:
![[Pasted image 20231227163056.png]]
depois:
![[Pasted image 20231227163109.png]]

`overflow: auto; ` - Dita que o espaçamento de um item vai ser levado em consideração
depois:
![[Pasted image 20231227163132.png]]

## Position
`position: relative;`  - Torna um elemento relativo a algo 
![[Pasted image 20231228100030.png]]
`position: absolute;` - torna um elemento relativo ao documento, não a outro elemento, deixando ele por cima de todos os outros

`position: fixed;` - Define que um elemento fique fixo na tela não importa as alterações feitas

`position: sticky;` 
`top: 0px;`
- Define que um elemento ira ser alterado pela pagina até que chegue em uma certa posição (No exemplo acima até que chegue ao topo da página)


`z-index: 0, 1, -1`  - Define que um elemento fique a frente ou não de outro elemento (valores positivos a frente, negativos atras)

## FlexBox
#### `display: flex;`  - Se for definido somente o display flex os itens irão ficar preenchendo completamente o espaço do container definido em grade
antes:
![[Pasted image 20231228104405.png]]
depois:
![[Pasted image 20231228104348.png]]



#### `flex-direction: (#) ` - Define a direção e formato que os elementos irão ficar
`row`  - Modo padrão do flex-box mostrado acima no "depois"
`row-reverse`  - Inverte a ordem dos itens

`colum` - Direção normal do html, em colunas mostrado acima no "antes"
`colum-reverse`  - Direção é invertida na vertical



#### `flex-wrap: (#)`  - Define oque acontece com os itens quando falta espaço para eles no container

`wrap`  - Define que os elementos podem se adaptar indo para outras linhas se necessário 
![[Pasted image 20231228111224.png]]

`no-wrap`  - Define que os elementos não podem ir para outras linhas

`wrap-reverse` - Altera a ordem que os elementos se adaptam
![[Pasted image 20231228111254.png]]



#### `justify-content: (#)`  - Define como os elementos vão se justificar horizontalmente

`center`  - Centraliza os elementos horizontalmente
![[Pasted image 20231228111401.png]]

`flex-start`  - Centraliza os elementos a esquerda
![[Pasted image 20231228111511.png]]

`flex-end ` - Centraliza os elementos a direita
![[Pasted image 20231228111528.png]]

`space-arround`  - Distribui os itens com espaços iguais porem com espaços diferentes para as bordas
![[Pasted image 20231228111550.png]]

`space-betwen` - Distribui os itens de forma que o primeiro e o ultimo fiquem grudados na borda
![[Pasted image 20231228111610.png]]


`space-evenly ` - Distribui os itens igualmente incluindo as boras



#### `align-items: (#)`  - Define como os elementos vão se justificar verticalmente

`flex-start`  - Ajusta os itens baseado no tamanho do conteúdo dentro deles
![[Pasted image 20231228111820.png]]

`flex-end`  - Ajusta os itens baseado no tamanho do conteúdo mas de baixo para cima
![[Pasted image 20231228111909.png]]

`center`  - Centraliza os itens verticalmente
![[Pasted image 20231228112132.png]]



`baseline` - Alinha os itens baseado no tamanho da box que eles estão colocados 



 `Gap: (#px)`  - Define o espaçamento entre os itens no interior do container
 ![[Pasted image 20231228114553.png]]


`row-gap: (#px)`  - Define o espaçamento entre as linhas do layout
![[Pasted image 20231228114736.png]]


`colum-gap: (#px)` - Define um espaçamento entre as colunas
![[Pasted image 20231228114851.png]]


#### `place-items: # #; ` - Define o alinhamento tanto vertical quanto horizontal dos itens
`center`  - Centraliza os elementos
`start`  - Alinha a esquerda
`end`  - Alinha a direita
`stretch`  - Assim como o "space-arround" ele obriga os itens a utilizarem todo o espaço disponível a ele na vertical e na horizontal


### Elementos dentro dos Flex Itens (child)

![[Pasted image 20231228115930.png]]

`Order` - Altera a ordem dos itens, sendo 0 sem ordem nenhuma, e quanto maior o valor mais em ultimo o item vai ficar
![[Pasted image 20231228120059.png]]
![[Pasted image 20231228120132.png]]


`flex-grow: 1;`  - Define a responsabilidade dos itens que tiverem essa propriedade de preencher completamente o container (quanto maior o número maior a responsabilidade de preencher)
![[Pasted image 20231228120334.png]]



#### `align-self: (#)`  - Define como um elemento deve ser alinhado indecentemente dos outros

`flex-end`  - Dita que o elemento deve ficar abaixo
![[Pasted image 20231228121236.png]]




### Grid  -  Define o posicionamento dos itens baseado em grade

`grid-template-colums: (nº de colunas, tamanho dessas colunas)`  - Define o tamanho das caixas em forma de coluna
![[Pasted image 20231229101053.png]]
![[Pasted image 20231229101107.png]]


`repeat(###)` -  É possível definir um item de repetição para que ele se repita em um padrão
`(4, 200px)`
![[Pasted image 20231229110017.png]]


`(auto-fill, 200px)`  - Define um ajuste automático dependendo do espaço disponível em tela, tornando um elemento responsável
![[Pasted image 20231229110229.png]]




`grid-template-rows: (nº de linhas, tamanho dessas colunas)` -  Define o tamanho das caixas em forma de linha
![[Pasted image 20231229101259.png]]
![[Pasted image 20231229101322.png]]

Também é possível juntar as duas funções
![[Pasted image 20231229101555.png]]
![[Pasted image 20231229101603.png]]


#### `Justify-items: ;`  - Define o alinhamento horizontal dos elementos
`center`  - Centraliza os elementos
`start`  - Alinha a esquerda
`end`  - Alinha a direita
`stretch`  - Assim como o "space-arround" ele obriga os itens a utilizarem todo o espaço disponível a ele na horizontal


#### `align-items: ;` - Define o alinhamento vertical dos itens
`center`  - Centraliza os elementos
`start`  - Alinha a esquerda
`end`  - Alinha a direita
`stretch`  - Assim como o "space-arround" ele obriga os itens a utilizarem todo o espaço disponível a ele na vertical


#### `justify-content: :`  - Define o alinhamento horizontal da caixa
`center`  - Centraliza os elementos
`start`  - Alinha a esquerda
`end`  - Alinha a direita
`stretch`  - Assim como o "space-arround" ele obriga os itens a utilizarem todo o espaço disponível a ele na horizontal


#### `place-items: #  #; ` - Define o alinhamento tanto vertical quanto horizontal dos itens
`center`  - Centraliza os elementos
`start`  - Alinha a esquerda
`end`  - Alinha a direita
`stretch`  - Assim como o "space-arround" ele obriga os itens a utilizarem todo o espaço disponível a ele na vertical e na horizontal


#### `place-content: #  #; ` - Define o alinhamento tanto vertical quanto horizontal da caixa dos itens
`center`  - Centraliza os elementos
`start`  - Alinha a esquerda
`end`  - Alinha a direita
`stretch`  - Assim como o "space-arround" ele obriga os itens a utilizarem todo o espaço disponível a ele na vertical e na horizontal



`grid-template-areas: "name" "name";`  - Define nomes as caixas podendo assim fazer chamadas utilizando esse nomes para definir propriedades
![[Pasted image 20231229104745.png]]


`grid-areas: nome da area`  - Aplica o nome do elemento a ele, (não possui aspas)
![[Pasted image 20231229104733.png]]


É importante prestar atenção nas aspas pois elas definem as colunas então caso deseje colocar duas colunas com quatro itens seria assim: `grid-template-areas: "b a" "c d";`, tendo esse resultado
![[Pasted image 20231229104710.png]]



#### `grid-template: [] ;`  - É uma junção do grid-colum e do grid-row, dividindo ambas as propriedades por uma "/"

![[Pasted image 20231229122504.png]]
![[Pasted image 20231229122520.png]]




### Media Queries  - Define regras de css para determinadas situações na pagina, como exemplo disso a responsividade de um site

`@media #`
`screen and (#)`  - Define determinadas mudanças caso diferentes tamanhos de tela sejam acessados, podendo assim criar regras de css dentro dessa media queries
![[Pasted image 20240102124005.png]]

`screen and (orientation: landscape or portrait)` - Define mudanças caso o usuario utilize o celular em formato landscape ou portrait, (deitado ou em pé)
![[Pasted image 20240102170617.png]]


#### Breakpoints para utilizar na hora de fazer a responsividade de um site segundo o bootstrap

576px  - Smartphones
768px - Tablets
992px - laptops
1200px - Telas maiores