# Formulários em html
### tags:
#form - tag que o formulário deve se manter dentro
#input_text - input que faz uma caixa de texto
#input_submit - criar um botão para o envio de informações
#input_email - cria uma caixa para preenchimento de email
#input_password - cria uma caixa para digitar senha, esconde os itens do campo
#input_number - cria uma caixa de seleção de apenas números
#input_url - cria uma caixa para preencher uma url
#input_date - cria caixa de seleção de data
#input_time - cria uma caixa de seleção de horas
#input_color - cria um seleção de cores para que o usuário preencha
#input_checkbox - cria uma caixa de seleção para que o usuario preencha
#input_range - cria um slider range 
#input_hidden - cria um valor escondido  na página
#select - cria um select para adicionar opções
#option - cria opções de um select
#optiongroup - cria títulos para seções dentro do select
#textarea - cria uma caixa para colocar textos
#datalist - cria uma lista de sugestões para preencher um campo, é preciso usar o elemento list para vincular o input com o datalist
#option - vai dentro de #datalist e serve para setar as opções de sugestão
#input_reset - limpa todos os dados do formuláio
### Elementos inline:
#accesskey - define uma tecla de atalho para fazer a aplicação de um botao, por padrão alt + (tecla selecionada)

#title - da um titulo a um botao quando passamos o mouse por cima

#disabled - desabilita todos os elementos de um certo lugar

#list - serve para vincular o input com o datalist, utilizando um id no datalist e a tag inline #list no input

#method = "post" ou "get" (dentro de form) - post é um formato mais seguro de enviar informações e nao tem limitação, get não é tão seguro e mostra as informações na url

#step - Seleciona de quanto em quanto um valor vai pular (ex: de 100 em 100, 50 em 50 e etc...)

#maxlengh #minlengh - limita o mínimo e o máximo de caracteres que poderá colocar em um input de texto (dentro do input de texto)

#required - obriga o usuário a preencher o campo (dentro do input de texto)

#placeholder - fornece ao usuario uma dica do que deve ser escrito dentro daquele input
![[Pasted image 20231208133700.png]]

#value="#" - predefine um valor dentro de um input de texto (dentro do input de texto)


Css:



```HTML
<body>

    <h3 class="centralizar">Formulário</h3>

    <!-- Formulário -->

    <form action="https://sys4soft.com/udemy/forms/index.php" method="post" class="form_container">

        <!-- input de texto -->

        <div class="form_group">

            <input type="text" name="Usuário" maxlength="20" minlength="5" required placeholder="Preencha seu nome">

        </div>
        
        <!-- input de email -->

        <div class="form_group">

            <input type="email" name="Campo de email" placeholder="E-mail" required>

        </div>

        <!-- input de senha -->

        <div class="form_group">

            <input type="password" name="Senha" placeholder="Senha" required>

        </div>

        <!-- input de número -->

        <div class="form_group">

            <input type="number" name="número" placeholder="Digite um número" minlength="0" maxlength="10">

        </div>

  

        <!-- input de data -->

        <div class="form_group">

            <input type="date" name="campo_date">

        </div>
        <!-- input de tempo -->

        <div class="form_group">

            <input type="time" name="tempo">

        </div>

        <!-- input de url -->

        <div class="form_group">

            <input type="url" name="url" placeholder="Url do site">

        </div>

        <div class="input_color">

            <input type="color" name="cores">

        </div>

        <!-- input de botão -->

        <div class="form_group">

            <input type="submit" value="Enviar">

        </div>

    </form>

</body>
