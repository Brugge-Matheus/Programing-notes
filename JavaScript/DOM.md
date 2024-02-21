Explicação:
![[Pasted image 20240104121122.png]]



### Como navegar pela página por DOM
![[Pasted image 20240104124219.png]]



### Geral
#### Elementos de leitura

`innerHtml`  - Seleciona os dados em formato de código
`innerText` - Seleciona os itens em formato especifico de texto
![[Pasted image 20240104141726.png]]
![[Pasted image 20240104141804.png]]




### GetElementsby -  Seleção de elementos

Estrutura:
![[Pasted image 20240104143755.png]]

Ex:
![[Pasted image 20240104143915.png]]
![[Pasted image 20240104143942.png]]



### querySelector  - Maneira geral e moderna de selecionar elementos

`document.querySelector()`  - Busca um elemento específico que seja citado, tanto em classe como em id

Ex:
![[Pasted image 20240105092021.png]]
![[Pasted image 20240105092028.png]]




`document.querySelectorAll()`  - Busca todos os elementos de um determinado lugar (ex: p, h1, div)

Ex:
![[Pasted image 20240105092110.png]]
![[Pasted image 20240105092117.png]]




#### Todos os tipos de querySelectors
![[cod 1.png]]




### Estilos em JavaScript

Exemplo:
![[Pasted image 20240105092501.png]]


#### Identificar um style definido in-line pelo console
![[Pasted image 20240105092508.png]]
![[Pasted image 20240105092516.png]]


#### Alterar ou adicionar uma classe a um item

`Toogle`  -Melhor forma de adicionar uma ou várias classes: Vai analisar se esse item existe, se existir ele não faz nada, se não ele adiciona
![[Pasted image 20240105092527.png]]


Alterar:
![[Pasted image 20240105092538.png]]


Adicionar:
![[Pasted image 20240105092546.png]]



#### Adicionar múltiplas classes de uma vez

Ex:
![[Pasted image 20240105092555.png]]


#### Remover classe

Ex:
![[Pasted image 20240105092602.png]]



### Manipular atributos dos elementos

#### Alterar um item
`Possui dois parâmetros, primeiro oque deseja alterar, segundo pelo que deseja alterar`
![[Pasted image 20240105092610.png]]


#### remover um item
![[Pasted image 20240105092619.png]]


#### Selecionar um atributo
`getAttribute`
![[Pasted image 20240123211456.png]]


#### Verifica se um atributo existe
`hasAttribute`
![[Pasted image 20240123211644.png]]

### Cria e remover elementos

Estrutura:

`document.createElement('tag que deseja criar')` - cria um novo elemento

`nome_do_elemento.innerText = 'Texto para o elemento'` ou `.textContent = 'texto_do_paragrafo'` - Atribui um texto a um elemento

`document.body.appendChild(nome_do_elemento)`  - Adiciona o elemento ao body

`nome_do_elemento_pai.appendChild(nome_do_elemento)` - Adiciona um elemento a um elemento (ex: um h1 a uma div)
![[Pasted image 20240105225529.png]]

Exemplo de utilização:

![[Pasted image 20240105230625.png]]
![[Pasted image 20240105231055.png]]



#### Adicionar um elemento antes - Utilizando a propriedade `prepend` é possível adicionar um item antes de outro

![[Pasted image 20240107015827.png]]
![[Pasted image 20240107020010.png]]



#### Adicionar um elemento depois  - Utilizando a propriedade `append` é possível adicionar um item depois de outro
![[Pasted image 20240107020055.png]]
![[Pasted image 20240107020120.png]]



#### Outra forma de fazer a realocação do local do elemento

-Utilizando a tag `insertAdjacentHTML` e as propriedades mostradas abaixo é possível alterar o posicionamento do item

![[Pasted image 20240107021703.png]]
![[Pasted image 20240107021827.png]]




#### Remover itens em JavaScript

Usando a função remove pode-se remover itens
![[Pasted image 20240107022011.png]]



