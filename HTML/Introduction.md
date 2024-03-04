# Concept

> O **HTML** (**HYPERTEXT MARKUP LANGUAGE**) se resume na utilização de **ELEMENTOS SEMÂNTICOS** os quais definem a estrutura e o significado em uma **WEB PAGE**.

# HTML - O quê é?

**[[#HTML]]** (**HYPERTEXT MARKUP LANGUAGE**).

O **[[#HTML]]** é categorizado como uma **LINGUAGEM DE MARCAÇÃO**, sendo responsável pela estruturação e definição de uma **WEB PAGE**, através da utilização de **[[#ELEMENTOS]]**.

Em suma, o **[[#HTML]]** se consiste em diferentes tipos de **[[#ELEMENTOS]]**, os quais, alguns por exemplo, nos permitem anexar, envolver e até mesmo marcar certas partes do documento.

## HTML - Estrutura

![[Pasted image 20240211001457.png]]
`<!DOCTYPE HTML>` - Declaração de que este documento é **[[#HTML]]**, e isso fará com que a **WEB PAGE** seja exibida corretamente.

`<HEAD> </HEAD>` - Atua como um container para todo o conteúdo da página **[[#HTML]]** que não é visível para os visitantes do site. Isso inclui palavras-chave e a descrição da página as quais queremos que apareçam nas buscas, o **[[#CSS]]** para estilizar o conteúdo da página (Apesar de ser recomendado fazê-lo num arquivo separado), declaração de conjunto de caracteres, e etc. 

`<META CHARSET="UTF-8>` - Este **[[#ELEMENTO]]** define o tipo da codificação dos caracteres que o seu documento deve usar, neste caso, para o tipo **UTF-8**, que inclui a maioria dos caracteres das línguas humanas escritas. Essencialmente, ele consegue lidar com qualquer tipo de conteúdo textual que você puder colocar no documento.

`<TITLE> </TILE>` - Definirá o título de nossa **WEB PAGE** na guia do navegador.

`<BODY> </BODY>` - A parte que será exibida em nossa **WEB PAGE**, ou seja, tudo aquilo que queremos que seja visível, devemos estruturar dentro deste **[[#ELEMENTO]]**.

## ELEMENTOS

Os **[[#ELEMENTOS]]** são representados pelas **TAG's**, desde a sua abertura, o conteúdo e o fechamento das mesmas. E todo **[[#ELEMENTO]]** que não possuir conteúdo, é considerado como um **ELEMENTO VAZIO**, não sendo necessário terem um fechamento, e um exemplo seriam as **TAG's BR e IMG**.

![[Pasted image 20240210211552.png]]
### ELEMENTOS - Aninhamento

Podemos, dentro da estrutura de um **[[#ELEMENTO]]**, ter outros **[[#ELEMENTOS]]**, e isso é chamado de **[[#ANINHAMENTO]]**.

![[Pasted image 20240210212044.png]]
### ELEMENTOS - BOX LEVEL / INLINE LEVEL

#### BOX LEVEL

Os **ELEMENTOS [[#BOX LEVEL]]** são caracterizados por sempre começarem em uma nova linha, mesmo que haja espaço acima deles ou abaixo. São geralmente **[[#ELEMENTOS]]** estruturais, tais como **PARÁGRAFOS, TABELAS, RODAPÉS** e muitos outros.

#### INLINE LEVEL

Os **ELEMENTOS [[#INLINE LEVEL]] são aqueles que podem ser contidos em pequenos espaços, e geralmente envolvem apenas pequenas partes do documento, e não parágrafos inteiros ou agrupamentos de conteúdos. E o mesmo não fará com que uma linha nova apareça quando for usado. Geralmente, os **ELEMENTOS [[#INLINE LEVEL]]** aparecem dentro de parágrafos, através de **TAG's** de ênfases e links, como as **EM & STRONG** ou **A**.

![[Pasted image 20240210213617.png]]
### ELEMENTOS - Atributos

Um **[[#ELEMENTO]]** pode conter **[[#ATRIBUTOS]]**, os quais são informações extras sobre o **[[#ELEMENTO]]**, que o farão ter funcionalidades a mais. E no caso do exemplo abaixo, adicionamos o **ATRIBUTO CLASS**, o qual permite darmos uma identificação específica ao **[[#ELEMENTO]]**, a qual pode ser usada mais tarde para uma melhor estilização do conteúdo.

![[Pasted image 20240211000016.png]]
Obs: O **[[#ATRIBUTO]]** deve conter as seguintes características: 

- Um espaço entre o **[[#ATRIBUTO]]** e o **[[#ELEMENTO]]** (ou o **[[#ATRIBUTO]]** anterior, caso o **[[#ELEMENTO]]** já contenha um ou mais **[[#ATRIBUTOS]]**.)
- O nome do **[[#ATRIBUTO]]**, seguido por um sinal de igual.
- Um valor de **[[#ATRIBUTO]]**, com aspas de abertura e fechamento em volta dele.