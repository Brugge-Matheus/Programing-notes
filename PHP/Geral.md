
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