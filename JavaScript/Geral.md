#### Regras gerais
- Case sensitive  - as variáveis são afetadas por letras maiúsculas e minúsculas (idade e Idade)

#### Tipos de Variáveis

`Var`  -

`let` - 

`const`  - Um valor declarado em const não pode ser alterado

`typeof`  - Serve para ver qual o tipo de uma variavel
![[Pasted image 20240102211047.png]]

#### Tipos de dados dentro de uma variável

`= "#"`  - Variável do tipo string, usada para guardar valores de texto
![[Pasted image 20240102210430.png]]

`= 21`  - Variável do tipo number
![[Pasted image 20240102210440.png]]

`Nan`  - Not a number
![[Pasted image 20240102210500.png]]

`= false`  - Variável do tipo booleana (verdadeiro ou falso) 
![[Pasted image 20240102210515.png]]

`undefined`  - Define um valor indefinido
![[Pasted image 20240102210557.png]]

`null`  - Define um valor nulo
![[Pasted image 20240102210647.png]]


#### Operadores

##### Operadores matemáticos


`adição`  - soma  valores
![[Pasted image 20240102215501.png]]

`subtração`  - subtrai valores
![[Pasted image 20240102215507.png]]

`multiplicação`  - Multiplica valores
![[Pasted image 20240102215514.png]]

`divisão`  - Divide valores
![[Pasted image 20240102215519.png]]

`Módulo`  - O resto de uma divisão
![[Pasted image 20240102215526.png]]

Guardar um resultado em uma nova variável
`let (variável) = (variavel1) + (variável2)`  - guarda um certo resultado de uma operação em uma nova variável
![[Pasted image 20240102215645.png]]


##### Operadores de atribuição  - Define que valor1 # valor2
![[Pasted image 20240102220608.png]]

`adicionar e atribuir`
![[Pasted image 20240102220618.png]]

`subtrair e atribuir`
![[Pasted image 20240102220624.png]]

`multiplicar e atribuir`
![[Pasted image 20240102220629.png]]

`dividir e atribuir`
![[Pasted image 20240102220638.png]]

`calcular a sobra da divisão e atribuir`
![[Pasted image 20240102220644.png]]


##### Operadores de strings  - Define determinadas operações em strings
![[Pasted image 20240102221124.png]]

`concatenação simples`  - Junta uma string a outra
![[Pasted image 20240102221132.png]]

`concatenação e atribuição`  - Atribui uma string a outra
![[Pasted image 20240102221147.png]]


#### Operadores de incremento e decremento  - Adiciona ou remove uma unidade de algum valor
![[Pasted image 20240102221540.png]]

`incremento`
![[Pasted image 20240102221608.png]]

`decremento`
![[Pasted image 20240102221640.png]]

#### Operadores de comparação
`A == B` - Se o valor A é igual ao valor B
`A === B` - Se o valor e o tipo de dados de A é igual ao valor B
`A != B` - Se o valor A não é igual ao valor de B
`A < B `- Se o valor A é menor que B
`A > B` - Se o valor de A é maior que B
`A <= B` - Se A é menor ou igual a B
`A >= B` - Se A é maior igual a B
Exemplo:
![[Pasted image 20240102230958.png]]
![[Pasted image 20240102231012.png]]


#### Operadores Lógicos
`(Condição A && Condição B)`  - Verdadeiro se ambas são verdadeiras (E)
`(Condição A || Condição B)`  - Verdadeiro se ao menos uma for verdadeira (OU)
`(!Condição A)`  - Verdadeiro se condição A for falsa (É verdadeiro se algo for falso)
Exemplo:
![[Pasted image 20240102231711.png]]
![[Pasted image 20240102231724.png]]

Outro exemplo:
![[Pasted image 20240102232857.png]]
![[Pasted image 20240102232905.png]]

Outro exemplo:
![[Pasted image 20240102233505.png]]

![[Pasted image 20240102233510.png]]

Outro exemplo:
![[Pasted image 20240102233755.png]]
![[Pasted image 20240102233801.png]]


#### Operador Ternário  - Serve para substituir o if e o else

`Var (nome da variável)  = (condição) ? valor1 : valor2`  - Cria uma variavel representando o resultado de uma operação, sendo o `'?' `para sim e o `':'` para não
Exemplo:
![[Pasted image 20240102234624.png]]
![[Pasted image 20240102234632.png]]

Outro exemplo:
![[Pasted image 20240102235009.png]]
![[Pasted image 20240102235015.png]]

`(nome da variável) == 10 ? console.log('#') :  console.log('#')`  - Também é possível utilizar sem cria uma variável, dessa forma como no exemplo
![[Pasted image 20240102235447.png]]
![[Pasted image 20240102235454.png]]

Outro exemplo:
![[Pasted image 20240102235805.png]]
![[Pasted image 20240102235812.png]]





### Instruções condicionais

`If`  - Significa 'Se' ou seja, se algo acontecer resultara em algo 
![[Pasted image 20240102224037.png]]

`else`  -Significa 'Caso contrario' ou seja, caso contrario faça algo, normalmente utilizado junto ao `if`
![[Pasted image 20240102224314.png]]

Outro exemplo:
![[Pasted image 20240102224727.png]]
![[Pasted image 20240102224742.png]]

`else if`  - Permite que mais de uma verificação seja feita de uma vez, como exemplo esse simples sistema de avaliação de notas
![[Pasted image 20240102225619.png]]


### Switch case  - Consiste em uma instrução de itens a serem executadas
Estrutura simples:
`switch (variavel) {`
	`case 1:`
			`codigo para valor 1`
		`break`
		
	`case 2:` 
			`codigo para valor 2`
		`break`
		
	`default:`
			`codigo para outro valor`
		`break`
`}`
Exemplo pratico:
![[Pasted image 20240103135124.png]]
![[Pasted image 20240103135143.png]]





Exemplo de estrutura com definição de operação, define operações dentro das cases
![[Pasted image 20240103134937.png]]
![[Pasted image 20240103134947.png]]




Exemplo de estrutura com varias cases:
![[Pasted image 20240103135902.png]]
![[Pasted image 20240103135910.png]]



`break`  - Serve para se uma certa alteração for aceita as outras abaixo serão canceladas
`default`  - Define que se nenhuma das cases sejam escutadas carrega ele, (equivalente ao else)

`true` - Define que um bloco será executado



### Array  - É um tipo especial de variável que é utilizada para armazenar vários dados em uma variável

Estrutura:
`let nomes = ["variavel1", "variavel2", "variavel3"]`

##### Formas de apresentar um array:
`console.log(variavel) ` - Apresenta todos os elementos em formato de código

`console.log(variavel[1])`  - Apresenta o número selecionado na contagem dos itens (**Lembrando que começa em 0**)

`console.table(nomes)`  - Apresenta todos os itens em formato de tabela


##### Formar de alterar os dados de um array
`variavel[1] = '#'`  - Altera um valor em especifico do array


##### Quantos elementos tem um array
`consolo.log(varivel.length)`  - Diz a quantidade de elementos dentro de um array



##### Adicionar elementos a um array

Ao final
`variavel.push("#")`  - Adiciona um elemento ao final do array, depois de todos os valores

No início
`variavel.unshift("#)`  - Adiciona um elemento no inicio do array, antes de todos os valores


##### Remover elementos do inicio de um array

`variavel.shift()`  - Remove um elemento do inicio

##### Remover elementos do final de um array

`variavel.pop()`  - Remove um elemento do final

##### Remover elementos de qualquer posição de um array

`variavel.splice(1,2, "#", "#" ,"#")` - Utilizando o splice no array depois definindo de qual a qual item deseja apagar pelo número da sequência, depois ainda adicionando outros valores no lugar

`console.table(variavel)`

Exemplo:
![[Pasted image 20240103150125.png]]
![[Pasted image 20240103150134.png]]



##### Mostrar elementos removidos

`let removido = nomes.pop()`
`console.log(removido)`
`console.table(nomes)`
Apaga um dado e mostra no console.log 


Também é possível mostrar itens removidos no formato splice
![[Pasted image 20240103150345.png]]
![[Pasted image 20240103150327.png]]


[  ]  - Seleciona um valor em especifico



##### Ordenar um array de forma ascendente - Importante - altera a estrutura do array

`variavel.sort()
`console.table(nomes)`


#### Ordenar um array de forma decrescente - Importante - altera a estrutura do array

`variavel.sort().reverse()`
`console.table(variavel)`





### Códigos dentro de uma string

`/n`  - Define uma quebra de linha em uma frase

`/t`  - Define um paragrafo ou um tab em uma frase

`.length`  - Mostra quantos caracteres possui um certo elemento
![[Pasted image 20240102222810.png]]

`.indexOf('item que deseja verificar')`  - Analisa se um item citado esta presente em uma variável
![[Pasted image 20240102223046.png]]




### Ciclos, Loops e Iterações

#### While  - Enquanto a condição for verdadeira ele executara uma ação infinitamente (enquanto)

Estrutura básica
`While(variavel) {`
	`codigo a ser executado`
`}`
Exemplo:
![[Pasted image 20240103211139.png]]
![[Pasted image 20240103211148.png]]




#### Do - executa a ação pelo menos uma vez e depois o loop de verificação é feito

Exemplo:
![[Pasted image 20240103211555.png]]
![[Pasted image 20240103211603.png]]



#### for  - Define que a partir de algo ele ira executar uma certa ação

Estrutura:
`for(iniciação; condição; incremento){`
	`código a executar`
`}`

Exemplo:
![[Pasted image 20240103212336.png]]
![[Pasted image 20240103212343.png]]


#### for...in - Serve para percorrer ou iterar chaves/propriedades em uma sequência fazendo uma ação ou análise



#### for...of - Serve para percorrer ou iterar sobre valores dos elementos em uma sequência fazendo uma ação ou análise

Estrutura:
`let valores = [1,2,3,4]`
`for(let valor of valores) {`
	`console.log(valor)`
`}`


#### foreach  - Serve para percorrer os itens que foram selecionados 
-Executando propriedades pre definidas, são elas: (nome do item, contagem do item e valores totais do item)

Exemplo:

![[Pasted image 20240107213842.png]]
![[Pasted image 20240107213832.png]]





### funções  -  Serve para executar uma ação a partir de outra ação

Estrutura:
`function nome_da_funcao(){`
	`codigo dentro da função`
`}`
![[Pasted image 20240103220333.png]]


#### Função com parâmetros  - Podem ser definidos parâmetros diferentes para a mesma função

Exemplo:
![[Pasted image 20240103220617.png]]
![[Pasted image 20240103220625.png]]



#### Parâmetro e retorno  - Define parâmetros gerais e retorna esses valores, sendo possível depois adicionar valores a esses parâmetros utiliza-los

Exemplo:
![[Pasted image 20240103221207.png]]
![[Pasted image 20240103221216.png]]



#### Parâmetro com valor padrão  - É criado um valor padrão para um parâmetro, porem quando outro valor é adicionado ele substitui o padrão

Exemplo:
![[Pasted image 20240103221631.png]]
![[Pasted image 20240103221639.png]]



#### Function Expressions  - Uma variável que vai ser uma função (Não eh muito utilizado, usar arrow)

Estrutura:
`let funcao = function(){`
	`console.log("Texto da função")`
`}`
`funcao()`
![[Pasted image 20240104092919.png]]








#### Arrow Functions  -  Uma forma moderna de declarar uma variável com uma função

Estrutura:
![[Pasted image 20240104093438.png]]



#### Arrow Functions parâmetros  - arrow functions com parâmetros 

Estrutura:
![[Pasted image 20240104094001.png]] 

Outro exemplo:
![[Pasted image 20240104094630.png]]



#### Escopo de variáveis  

Escopo Global  - Se tratam de variáveis que foram definidas fora de blocos e valem para qualquer lugar do código
Ex:
![[Pasted image 20240104100519.png]]
![[Pasted image 20240104100528.png]]


Escopo local  - Se trata de variáveis que foram definidas dentro de um bloco, e é valida somente para o mesmo
Ex:
![[Pasted image 20240104100758.png]]
![[Pasted image 20240104100805.png]]





#### Objetos em JavaScript  - Se trata de uma coleção de valores nomeados por propriedades e métodos

Regras:
`:  ,`  - Depois do nome das propriedades e depois dos nomes das funções sempre dois pontos, depois de finalizar uma propriedade ou um método sempre usar virgula

`this`  - Serve para se referir a uma propriedade dentro do objeto


`.`  - Quando for apresentar o objeto sempre relacionar o nome do objeto aos dados dele por ponto
Ex: `console.log(nome_do_objeto.nome_da_função());`


Exemplo de estrutura de um objeto:
![[Pasted image 20240104112605.png]]


##### Como apresentar esse objeto
![[Pasted image 20240104113832.png]]
![[Pasted image 20240104113856.png]]


##### Adicionar ou alterar uma propriedades a um objeto  

Estrutura  - utilizando o ponto pode adicionar ou editar uma propriedade
![[Pasted image 20240104115044.png]]
![[Pasted image 20240104115141.png]]


##### Deletar uma propriedade de um objeto
![[Pasted image 20240104120547.png]]
![[Pasted image 20240104120558.png]]




##### Criar um novo objeto a partir de outro objeto
![[Pasted image 20240104120417.png]]
![[Pasted image 20240104120428.png]]










