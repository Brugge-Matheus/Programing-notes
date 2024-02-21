
## Manipulação de String
=> `.length` - Seleciona a quantidade de caracteres de um item.

=> `.indexOf('')` - Procura a posição de algo em um item, como uma letra, uma palavra etc...

=> `.slice(0, 10)` - Serve para selecionar ou utilizar uma quantidade especifica de itens. (Ex: mostrar os caracteres do 0 ao 15 em uma frase)

=> `.substr(3, 1)` - Serve para procurar itens em uma string, fornecendo dois parâmetros sendo primeiro a posição e o segundo a quantidade de itens.

=> `.replace('Pesquise', 'Substitua')` - Serve para substituir um item, recebendo dois parâmetros sendo um o item atual e o outro o item novo.

=> `.toUpperCase` - Deixa uma string maiúscula.
=> `.toLowerCase` - Deixa uma string minúscula.

=> `.trim()` - Serve para remover espaços inúteis de uma string.

=> nome_da_variavel`[3]` - Serve para selecionar um item especifico de uma string como uma letra por exemplo.

=> `map()` - 

=> `.split(' ')` - Itera uma string e onde ele encontrar o item do parâmetro passado ele transforma em array.
![[Pasted image 20240201221938.png]]
![[Pasted image 20240201221917.png]]

=> `closest('#')` - Busca dentro de um elemento o elemento mais próximo que tenha as propriedades passadas por parâmetro.


## Manipulação de Numbers
=> `.toString()` - Converte um número para uma string.

=> `toFixed(2)` - Fixa somente uma quantidade de números depois da virgula.

=> `parseInt(variavel)` - Transforma uma variável em número inteiro 
=> `parseFloat(variavel)` - Transforma uma variável em número flutuante (números com virgula).


## Manipulação de Arrays
=> `.toString` - Transforma um array em string.

=> `.join('-')` - Transforma um array em string e separa pelo parâmetro definido.

=> `.indexOf('item')` - Procura e retorna o item solicitado no parâmetro.

=> `.pop('item')` - Remove o ultimo item de um array.
=> `.shift('item')` - Remove o primeiro item de um array.

=> `.push('item')` - Adiciona um novo item ao final do array.
=> `.unshift('item')` - Adiciona um item ao inicio do array.

=> `.splice(1, 1)` - Remove um item completamente de um array, passando dois parâmetros, sendo um a partir de qual item e os segundo quantos itens.

=> `nome_da_array.concat(outro_array)` - Serve para juntar dois arrays em um.

=> `.sort()` - Ordena alfabeticamente
=> `.reverse()` - Inverte a ordem, se usado com o `.sort()` ordena alfabeticamente de forma decrescente.

#### Métodos Avançados
=> `.filter()` - Serve para filtrar itens de forma a retornar uma condição
![[Pasted image 20240202160455.png]]
![[Pasted image 20240202160516.png]]

Ex2:
![[Pasted image 20240202160839.png]]
![[Pasted image 20240202160601.png]]

=> `.every()` - Faz uma analise se a função passada bate com o array, retorna um valor boolean (true or false)
Ex:
![[Pasted image 20240202205336.png]]

=> `.some()` - Mesma ideia do `.every()` porem ele valida se ao menos um item segue o padrão exigido.

=> `.find()` - Encontra e retorna um item específico que exista no array, caso não existe retorna 'undefined'
Ex:
![[Pasted image 20240202221611.png]]
![[Pasted image 20240202221709.png]]

=> `.findIndex('parâmetro')` - Serve para encontrar a posição de um item em um array. 


## Datas
==> Para acessarmos a função `.Date()` precisamos criar um item da seguinte forma.
![[Pasted image 20240203013919.png]]

#### Utilizando a propriedade `.get` podemos acessar diversas funções de datas 
=> `.getFullYear()` - Retorna o ano atual.
=> `.getMonth()` - Retorna o mês atual.
=> `.getSeconds()` - Retorna o segundo atual.
=> `.getDate()` - Retorna o dia atual.

==> `Date.now()` - Retorna a data em tempo real

#### Manipulação de datas
=> `.setFullYear()` - Define o ano.
=> `.setMonth()` - Define o mês.
=> `.setHours()` - Define o horário.
=> `.setSeconds()` - Define os segundos.

=> `.setDate()` - Define o dia atual
=> É possível fazer pequenos sistemas utilizando as funções de data: (Retorna a data atual mais 5 dias)
![[Pasted image 20240204022213.png]]



## Matemática
==> Utilizando a classe `Math...` podemos fazer operações matemáticas gerais.
![[Pasted image 20240204024625.png]]

=> `.round()` - Retorna o número passado pelo parâmetro arredondado (3.67 retorna 4.

=> `.floor()` - Retorna o número passado pelo parâmetro arredondado para baixo.

=> `.ceil()` - Retorna o número passado pelo parâmetro arredondado para cima.

=> `.abs()` - Retorna o absoluto de um número passado pelo parâmetro.

=> `min(n1, n2, n3...)` - Retorna o menor número passado no parâmetro
=> `max(n1, n2, n3...)` - Retorna o maior número passado no parâmetro

=> `.sin()` - Retorna o seno.
=> `.cos()` - Retorna o cosseno.
=> `.tan()` - Retorna a tangente.

==> `.random()` - Retorna um número aleatório entre zero e um
=> `Math.floor(Math.random() * 100)` - Utilizando o `*number` definimos até qual número o `random()` vai gerar, junto com o `.floor()` que garante que nunca passara desse número.
![[Pasted image 20240204024039.png]]


## Intervalos
==> Cria intervalos de tempo para repetições de um código

=> `setInterval(function, timeout)` - Define um intervalo de tempo em que uma função vai ser repetida, passando dois parâmetros sendo um a função que deseja repetir e o segundo o intervalo de tempo em milissegundos. 

=> `setTimeout(() => {}, timeout)` - Define o tempo que uma função vai ser rodada uma única vez, passando a função e o tempo que será rodado.



## Desconstruct 

### Desconstruindo objetos
==> *Utilizando o Desconstruct podemos desconstruir objetos e passar ele para variáveis de forma otimizada

=> Forma padronizada: Adicionando a uma variável o nome das propriedades desse objeto.
![[Pasted image 20240204144549.png]]

==> *Existem duas propriedades que podemos adicionar aos itens Desconstruct

=> `:` - Os dois pontos define um novo nome ao item do objeto permitindo que ele seja chamado por esse novo nome.
![[Pasted image 20240204144817.png]]

=> `=` - O igual permite que seja definido um valor padrão a um item do objeto, (caso não seja definido um valor para esse item no próprio objeto ele utilizara esse valor padrão).
![[Pasted image 20240204144949.png]]

==> *Também é possível acessarmos objetos dentro de objetos

=> `object:{}` - Passando o objeto dois pontos com chave e dentro dela adicionando o objeto podemos acessar objetos dentro de objetos.
![[Pasted image 20240204150653.png]]

*Podemos até mesmo mudar a chamada de um dos itens com o `:`*
![[Pasted image 20240204150821.png]]

#### Desconstrução de objetos em funções
==> *Podemos passar o Desconstruct como parâmetro de uma função*

=> Passando o parâmetro de uma função como Desconstruct utilizando suas propriedades na função e na chamada dela definindo o parâmetro como o nome do objeto.
![[Pasted image 20240204154449.png]]


*Função sem o Desconstruct*
![[Pasted image 20240204154313.png]]



### Desconstruindo arrays
==> É possível descontruir um array criando uma variável e fazendo com que ela receba o array criado, assim por ordem os nomes dessa variável vão receber os itens do array.
![[Pasted image 20240204211501.png]]

=> Podemos pular um item do array deixando um espaço em branco na hora de criar a variável.
![[Pasted image 20240204211618.png]]

#### Desconstruindo um array na criação dele

=> Podemos criar um array já desconstruído
![[Pasted image 20240204211904.png]]

=> Também podemos adicionar valores padrão aos arrays desconstruídos.
![[Pasted image 20240204211951.png]]


#### Desconstruindo um array com uma função
=> Podemos fazer uma função retornar um array e desconstruir ele logo em seguida
![[Pasted image 20240204212129.png]]



## Spread
==> *Serve para expandir os valores de um item para outro item*

### Spread em arrays
=> Criando dois arrays, no segundo adicionando `...array1, ` podemos adicionar os itens do primeiro array e ainda adicionar mais itens.
![[Pasted image 20240204214422.png]]

### Spread em objetos class method
=> Criando dois objetos, no segundo adicionando `...obj1, ` podemos adicionar os itens do primeiro objeto nesse e ainda adicionar livremente outros.
![[Pasted image 20240204214701.png]]


### Spread em objetos function method
=> Criando um função, na chamada dela adicionamos no parâmetro os itens primários do objeto, na criação dessa função colocamos `...par, `  e adicionamos os outros itens.
![[Pasted image 20240204214931.png]]



## Rest
==> *Serve para flexibilizar a utilização de parâmetros transformando itens em array se necessário*

=> Utilizando o `...` na utilização de um parâmetro por exemplo podemos com que não aja problema vários itens serem chamados de uma vez.
![[Pasted image 20240204221410.png]]

=> Podemos também transformar e adicionar itens de um array.
![[Pasted image 20240204221522.png]]
![[Pasted image 20240204221532.png]]



## Includes e Repeat

### Include
==> *Serve para fazer a procura de um item*

=> `.includes(item)` - Utilizando o include com o parâmetro igual ao item que deseja verificar se existe o sistema vai retornar um valor booleano confirmando se esse item existe ou não.
![[Pasted image 20240204222707.png]]

### Repeat
==> *Serve para fazer a repetição de algo determinadas vezes*

=> `.repeat(qtd vezes)` - Utilizando o repeat e no parâmetro a quantidade de vezes que deseja repetir algo, a informação será repetida
![[Pasted image 20240204222847.png]]
![[Pasted image 20240204222853.png]]



## Objective Keys, Values e Entries
==> *Serve para ver informações de um objeto ou um array*

### Em arrays
=> `object.keys(arrayName)` - Retorna o index dos itens do array
=> `object.values(arrayName)` - Retorna o value dos itens do array
=> `object.entries(arrayName)` - Retorna um array para cada item contendo o nome e o valor desse item (0: 'Matheus').
Ex:
![[Pasted image 20240204225424.png]]
![[Pasted image 20240204225707.png]]

### Em objetos
=> `object.keys(objectName)` - Retorna o index dos itens do objeto
=> `object.values(objectName)` - Retorna o value dos itens do objeto
=> `object.entries(objectName)` - Retorna um array para cada item contendo o nome e o valor desse item (name: 'Matheus').
Ex:
![[Pasted image 20240204225635.png]]
![[Pasted image 20240204225720.png]]



## String padStart and padEnd
=> *Estes itens preenchem uma string com outra string com uma determinada quantidade de caracteres até atingir um comprimento especificado.*

### padEnd
=> `.padEnd() - Define esses itens para esquerda, passando dois parâmetros sendo um a quantidade final de itens e o outro qual caracter deve ser colocado caso a string não atinja o tamanho indicado`
![[Pasted image 20240204231321.png]]
![[Pasted image 20240204231329.png]]


### padStart
=> `.padStart() - Define esses itens para direita, passando dois parâmetros sendo um a quantidade final de itens e o outro qual caracter deve ser colocado caso a string não atinja o tamanho indicado`
![[Pasted image 20240204231406.png]]
![[Pasted image 20240204231412.png]]

### Exemplo de aplicação real
*Validador de cartão que mostra os últimos dígitos do cartão somente*

![[Pasted image 20240204231609.png]]
![[Pasted image 20240204231617.png]]



## Manipulação de arquivos
==> **

=> Adicionando a propriedade `multipe` em um input de arquivos fazemos com que ele aceite mais de um arquivo
![[Pasted image 20240207200527.png]]

=> `.files[]` - Serve para que possamos acessar os arquivos enviados
![[Pasted image 20240207201728.png]]

=> `new FormData()` - Utilizando esse função e fazendo um `append()` a ela com os dados do arquivo podemos enviar uma variável que contenha os arquivos para a requisição POST
![[Pasted image 20240207201938.png]]

=> `headers: {'Content-Type':'multipart/form-data'}` - Ao fazermos a requisição POST, dentro do header precisamos colocar essas informações para simular um envio de arquivo
![[Pasted image 20240207202109.png]]

*Todo o processo de envio ficaria dessa forma*
![[Pasted image 20240207202134.png]]


## Inserir imagem no navegador
=> `URL.createObjectURL()` - Passando um file como parâmetro ele gera uma URL para demonstração desse arquivo 
![[Pasted image 20240207204133.png]]

==> *Exemplo de função para adicionar imagem na tela*
![[Pasted image 20240207204218.png]]


### Utilizando o FileReader
=> Podemos chegar ao mesmo resultado utilizando o file reader
![[Pasted image 20240207205404.png]]


## Mouse Position
*Pega a posição X e Y do mouse baseado na tela selecionada*

=> `pageX` - Fornece a posição X do mouse na tela 
=> `pageY` - Fornece a posição Y do mouse na tela

*Essas posições são pegas baseadas no tamanho da selecionada, porem podemos compensar isso fazendo a subtração dos itens com as propriedades da tela*
![[Pasted image 20240213103717.png]]



## Identificar itens clicados
==> *Podemos identificar os itens que foram clicados e fazer funções a partir disso*

=> `.target` - Vai retornar exatamente qual elemento foi clicado
=> `.currentTarget` - Vai retornar o elemento em que o evento foi definido

Ex da diferença:
![[Pasted image 20240213154645.png]]
![[Pasted image 20240213154723.png]]
![[Pasted image 20240213154732.png]]
