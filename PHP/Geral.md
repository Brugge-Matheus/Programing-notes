
## Initial Code

=> `;` - A linguagem requer `;` ao final de cada código

=> `phpinfo();` - Mostra as informações do Php baseado no servidor em que ele esta alocado

## Maneiras de delimitar código PHP

=> `<?php ?>` - Super tag PHP

=> `<? ?>` - Short open tag

=> `<% %>` - Asp tag

=> `#` - Short tag PHP


## Variáveis e constantes 
*Dados que são guardados na memória*

### Declaração de Variáveis e Constantes

==> `$variavel = '#';` - Cria uma variável

==> `const constante = '#';` - Cria uma constante

![[Pasted image 20240307194549.png]]

==> `var_dump();` - Mostra o tipo de uma variável

=> `(type)` - Podemos definir o tipo de uma variável, porem o Php permite trocas e não gera erros

![[Pasted image 20240307194645.png]]

### regras
=> Variáveis sempre começam com o símbolo `$`
=> O segundo caractere pode ser letra ou símbolo `_`
=> O terceiro caractere pode ser [a-z], [A-Z]. [0-9] e [_]
=> A linguagem é case sensitive
=> nomes especiais como $this não podem ser usados


## Tipos Primitivos
**

### Escalares

=> *String* - Sequência de letras, números e símbolos, sempre representadas entre ""

=> *Int ou integer* - Valor numérico inteiro, sem a parte decimal

=> *Float* - Valor numérico real que possui a parte decimal

=> *boolean* - Valor lógico que aceita apenas dois valores (true ou false)


### Compostos

=> *Array* - Um array em PHP é uma estrutura de dados que armazena múltiplos valores sob um único nome, acessíveis por índices

=> *Object* - Em PHP, um objeto é uma instância de uma classe que encapsula dados e comportamentos relacionados, permitindo a criação de estruturas mais complexas e reutilizáveis em programas.

### Especiais

=> *Null* - Em PHP, null é um valor especial que indica a ausência de um valor ou a falta de uma referência válida para uma variável

=> *Resource* -   
Em PHP, resource é um tipo de dado especial que representa um recurso externo, como uma conexão de banco de dados.

=> *Callabe* - Em PHP, "callable" é um tipo de dado que representa uma função ou método que pode ser chamado diretamente. Isso inclui funções

=> *Mixed* - Em PHP, mixed é um tipo de dado que indica que uma variável pode conter múltiplos tipos de valores,


## Manipulação de Strings

=> `.` Concatenar strings

### Double quoted ("")
*Existe a interpretação do conteúdo*

#### Sequência de escape
*Serve para escapar itens e símbolos

=> `\"variavel"\` - Permite a utilização de uma variável mesmo com a utilização das aspas simples

=> `/n` - Nova linha
=> `/t` - Tabulação horizontal (tab.)
=> `//` - Exibir barra invertida
=> `/$` - Mostrar cifrão na tela
=> `/u{}` - Utilizar símbolos

![[Pasted image 20240307225905.png]]

### Single quoted ('')
*Não existe interpretação de conteúdo*

![[Pasted image 20240307225918.png]]


### String Heredoc
**Uma maneira alternativa de apresentar strings interpretando conteúdo**

=> Utilizando `<<<` e depois alguma palavra qualquer entre aspas simples, depois fechando com a mesma palavra e um ponto e virgula, todo o texto adicionado entre os dois itens será apresentado.

![[Pasted image 20240314234518.png]]



### String Nowdoc
*Uma maneira alternativa de apresentar strings não interpretando conteúdo*

=> Utilizando `<<<` e depois alguma palavra qualquer entre aspas simples, depois fechando com a mesma palavra e um ponto e virgula, todo o texto adicionado entre os dois itens será apresentado.

![[Pasted image 20240314234558.png]]


## Obtendo dados de formulário
*#*

### Variáveis super global
*Variáveis que irão funcionar independentemente da situação*

=> `$_GET` - Recebe os dados enviados e mostra na Url
=> `$_POST` - Recebe os dados enviados escondendo na Url
=> `$_REQUEST` - Aceita tanto dados Post quanto Get

### Submit

=> `action = ""` - Definindo o `action` em um formulários é possível definir o destino de um `Submit`

![[Pasted image 20240317171743.png]]


### Capturar dados do formulário

=> `$_GET["nameDoInput"]` - Dessa forma podemos capturar dados enviados em um input 

![[Pasted image 20240317171902.png]]


### Operador de coalescência nula

=> `??` - Define um valor padrão quando as informações não são passadas

![[Pasted image 20240317172114.png]]



## Aritmética


### Ordem de precedência
*Define a ordem com que as operações aritméticas serão resolvidas*

----> `()` - Será sempre priorizado oque estiver dentro dos parênteses 

---> `**` - Potência

--> `* / %` - Multiplicação e Divisão

-> `+ -` - Adição e Subtração

### Funções aritméticas

=> `abs()` - Retorna o valor absoluto 

==> `base_convert()` - Converte em base decimal, octal e hexadecimal 
=> Ex: `base_convert(254, 10, 8)`

=> `ceil(), floor(), round()` - Arredonda respectivamente em para cima, para baixo e arredondamento aritmético 

=> `hypost()` - Calcula a hipotenusa

=> `intdiv()` - Retorna a divisão inteira

=> `min(), max()` - Retorna o valor mínimo e máximo de uma sequencia 

=> `pi() ou M_PI` - Retorna o lugar de `pi`

=> `pow()` - Retorna a potência

=> `sin(), cos(), tan()` - Retorna o seno, cosseno e tangente

=> `sqrt()` - Retorna a raiz quadrada de um número


==> `rand(min, max)` - Passando o número mínimo depois o número máximo ele retorna um número aleatório entre eles

=> `mt_rand(min, max)` - Maneira mais atualizada de gerar números aleatórios

=> `random_int(min, max)` - Maneira mais "lerda" de gerar, porem os números são criptografados 


### Operadores Aritméticos

=> `+` - Adição
=> `-` - Subtração
=> `*` - Multiplicação
=> `/` - Divisão
=> `%` - Módulo de uma divisão inteira
=> `**` - Exponenciação


