# Concept

>

# HTML5 / TAG A (External) 

Neste caso, usamos a **[[#TAG A]]** para estabelecer uma conexão com uma "**URL** **EXTERNA**" ao nosso site, no caso, o "Youtube", porém, é necessário que saibamos, que quando a nossa "**TAG**" não possuí mais nenhum **[[#ATRIBUTO]]**, como no caso de nosso primeiro exemplo, o nosso site será sobreposto pela "**URL**" que referenciamos.

E a fim de contornar este problema, devemos adicionar a estrutura desta "**TAG**", os **[[#ATRIBUTOS]]** "**TARGET & REL**", os quais, de acordo com os valores dados, fazem com que o nosso site não seja sobreposto, mas sim, como no exemplo abaixo, seja criado uma nova guia para a "**URL**" que referenciamos.

![[Pasted image 20240212134519.png]]

Obs: Usando o **[[#ATRIBUTO]]** "**TARGET**", podemos determinar onde o site de destino será aberto, em nosso caso, ele será aberto em uma nova guia, por isso o valor "**_BLANK**". Porém, como padrão, o valor é "**SELF_**", no caso, será aberto na mesma janela que o nosso site ou conteúdo atual, o sobrepondo.

Obs: Através do **[[#ATRIBUTO]]** "**REL**", podemos indicar qual a natureza de destino do "**LINK**" que referenciamos, em nosso caso, o "**LINK**" é "**EXTERNO**", ou seja, não faz parte do nosso site atual. Porém, caso pertencesse, poderíamos usar outro valor no "**REL**", como por exemplo, o valor "**NEXT**", que é utilizado quando referenciamos outra parte de nosso site atual, como uma página dois, por exemplo.