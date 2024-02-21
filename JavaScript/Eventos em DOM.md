-Adicionando 'on' em uma tag de Html podemos ver diversas opções de eventos

![[Pasted image 20240107022558.png]]



### `onclick` - Faz algo ao clicar em um item

Adicionando o onclick em uma tag Html podendo executar ações, inclusive adicionar funções para utilizar em Js
![[Pasted image 20240107022716.png]]


#### Exemplo alterando o texto de um botão
![[Pasted image 20240107024030.png]]
![[Pasted image 20240107024015.png]]
![[Pasted image 20240107024100.png]]




### Mostrar qual evento aconteceu quando determinada ação foi feita

Usando a propriedade `event` na propriedade `on`, depois adicionando um parâmetro quando for puxar a função no js e assimilar esse parâmetro a propriedade `target` é possível mostrar oque foi feito

![[Pasted image 20240107024836.png]]
![[Pasted image 20240107024850.png]]



### Propriedades On
`oncontextmenu`  - Faz algo ao clicar com o botão direito em algo
`onmouseenter`  - Faz algo ao entrar com o mouse em algum lugar
`onmousemove`  - Faz algo ao se mover com o mouse em algum lugar
`onmouseleave`  - Faz algo ao sair com o mouse em algum lugar



### Adicionar mais de um evento a um item

-Utilizando a tag abaixo e definindo as duas propriedades que são: o tipo de evento e a função que ocorrera podemos adicionar diversos eventos a apenas um item
`addEventListener('tipo_do_evento', 'function(){`
	`codigo_que_sera_executado`
`}')`

![[Pasted image 20240107173431.png]]
![[Pasted image 20240107173647.png]]


### Adicionar mais de um evento utilizando arrow function

-Utilizando a propriedade `() => ###` logo após a definição do tipo de evento pode-se obter as mesmas alterações

![[Pasted image 20240107175452.png]]
![[Pasted image 20240107175559.png]]



### Remover um evento

-Utilizando a propriedade `removeEventListener` e definindo o tipo de evento usado e a função que deseja remover

![[Pasted image 20240107183238.png]]



### Exercício utilizando Event Listner

![[Pasted image 20240107183413.png]]
![[Pasted image 20240107183428.png]]


### retirar a dependência de um item sobre outro

-Utilizando a propriedade `stopPropagation` é retirada assim a dependência de um item sobre outro, no caso abaixo (section, article e div)

![[Pasted image 20240107185758.png]]



-Também é possivel fazer este mesmo código utilizando o `forEach`
![[Pasted image 20240107190950.png]]
![[Pasted image 20240107191024.png]]



### Desativar a função nativa de um link

-Utilizando a função `preventDefault()` é possível inativar o `href` de um link
![[Pasted image 20240107222931.png]]
![[Pasted image 20240107223003.png]]


### Desativando a função de um input
![[Pasted image 20240107225234.png]]















