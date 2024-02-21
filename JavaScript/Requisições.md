### Requisições `Síncrona e Assíncrona`
#### Como funciona? (Requisição e Resposta)
=> Request =  Requisição
==> Cabeçalhos / Headers
=> Response = Resposta
#### Síncrona
=> Execução linear de códigos, de cima para baixo da esquerda para direita

#### Assíncrona
=> Execução de forma conjunta executando todos os códigos ao mesmo tempo, podendo até ser executado em ordem inversa

### Como funciona uma API? (Application Programing Interface)
#### Comunicação entre máquinas
=> inclui regras e protocolos que ajudam a usar as funções de um aplicativo dentro do outro


### Json (JavaScript Object Notation)
==> *É uma forma simples de trocar dados*

=> `JSON.parse()`- Podemos transformar uma estrutura de exemplo de um Json em um Json real.
![[Pasted image 20240205140215.png]]

=> `JSON.stringify()`- Podemos transformar uma estrutura de Json em uma string.


### Oque é Callback?
=> A função callback é um conceito fundamental em programação JavaScript. Ela permite passar uma função como argumento para outra função, que será executada em um momento específico ou em resposta a um evento.


### Como fazer uma requisição simples

=> Utilizando a função `Fetch()` podemos adicionar o link da API que desejamos chamar.
=> Logo após isso utilizamos a função `.then` utilizando o parâmetro `response` para retornar os dados dessa API.
=> Assim podemos converter ela para um `Object` assim podendo acessar as informações de dentro dela com `.`

![[Pasted image 20240130205450.png]]
![[Pasted image 20240130222823.png]]

#### Oque é Promise
=> Uma promise **é um objeto retornado por uma função assíncrona, que representa o estado atual da operação**. No momento em que a promise é retornada para quem à chamou, a operação muitas vezes ainda não foi finalizada, mas o objeto da promise oferece métodos para tratar o possível sucesso ou falha da operação

#### Métodos que podem ser utilizados com o `Fetch()`
=> `.catch(error)` - É rodado quando acontece algum erro no Callback, também pode ser utilizado um parâmetro de `error` que cita o erro que ocorreu na chamada
![[Pasted image 20240130224053.png]]

=> `.finally()` - É rodado somente quando o Callback é finalizado por completo
![[Pasted image 20240130224501.png]]

=> `.then()` - É utilizado para pegar a resposta do Callback
![[Pasted image 20240130224711.png]]

### Métodos de envio de requisição
#### Get
=> Quando eu quero pegar informações
#### Post
==> Quando eu quero inserir uma informação nova
=> Ao abrir a chave na função `Fetch` podemos definir informações como o método utilizado, e assim definir a estrutura das informações que serão enviadas para a API. 
![[Pasted image 20240131155019.png]]
![[Pasted image 20240131155327.png]]
#### Put
=> Quando eu quero alterar alguma informação existente
#### Delete
=> Quando eu quero deletar alguma informação existente


### Promise utilizando `Async` e `await`
==> Se trata de uma forma mais moderna e mais utilizada de se fazer Callbacks.

=> Utilizando o `Async` podemos criar uma função assíncrona, com o `await` definimos a espera até que a requisição termine para que assim o código seja continuado.

=> Fazemos todos esses processos utilizando variáveis
#### GET
![[Pasted image 20240131171148.png]]
#### POST
![[Pasted image 20240131171256.png]]


f