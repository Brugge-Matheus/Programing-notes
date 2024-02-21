### Concept

> A **TAG IMG** tem como propósito, inserir imagens estáticas em nosso site.

##### HTML5 / TAG IMG

Através da TAG IMG, é possível adicionar imagens de diferentes formas em nosso código, tal como uma imagem estando no mesmo documento que o nosso "Index", ou até mesmo em uma subpasta, ou caso preferirmos, podemos usar uma "URL" de alguma imagem em específico da web.

```HTML
<!DOCTYPE html>

<html lang="pt-br">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>TAG IMG / IMAGEM</title>

</head>

<body>

    <h1>Adicionando os ícones HTML, CSS & JS</h1>

    <p>Abaixo, colocaremos uma imagem que está na mesma pasta que nosso "Practice"</p>

    <img src="HTML5 Logo.png" alt="HTML5 Logo">

    <p>Agora, colocaremos uma imagem que está em uma sub-pasta de nosso "Practice"</p>

    <img src="Imagens/CSS3 Logo.png" alt="CSS3 Logo">

    <p>E por fim, adicionaremos uma imagem com link externo, ou seja, direto da Internet!</p>

    <img src="https://cdn.iconscout.com/icon/free/png-512/free-javascript-2038874-1720087.png?f=webp&w=256" alt="JS Logo">

</body>

</html>
```

Observação: "SRC" & "ALT" / "ORIGEM" & "TEXTO ALTERNATIVO". O "SRC" Tem como foco, representar a origem do documento que inserimos no código, enquanto o "ALT", tem como foco, ser um texto simples, que explique o quê o documento. 

Observação: No espaço do "SRC", podemos usar o atalho "CTRL + Espaço, assim, será mostrado uma lista das imagens que podem ser escolhidas."