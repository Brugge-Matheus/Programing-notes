
## Geral
=> `ls` - Podemos ver quais os arquivos e pastas existem no local atual

=> `git log` - Abre o log de alterações

=> `git status` - Diz as especificações do projeto criado

=> `git init` - Inicia o git em algum lugar

## Criação de arquivos

=> `cd` - Acessar alguma pasta
=> `cd ..` - Volta uma pasta para trás

=> `mkdir nomeDaPasta` - "Make directory" Cria uma pasta

## Edição de arquivos
=> 



## Branches
*Se trata de uma versão específica do seu projeto (Ex: Staging, Main)*

### Criação de branches

=> `git branch` - lista todas as branches e mostra qual a branch selecionada.

=> `git branch NomeDaBranch` - Cria uma branch.
=> `git switch -c "NomeDaBranch"` - Cria uma branch e troca para ela automaticamente.

=> `git switch NomeDaBranch` - Troca para a branch selecionada.

*Neste momento as alterações feitas em uma branch não estara presente na outra a não ser que você de o comando*
## Fazendo Merge

=> `git merge NomeDaBranch` - Junta uma branch com outra branch.

=> `git branch -d NomeDaBranch` - Deleta uma branch local
=> `git push origin --delete nomeDoBranchRemoto` - Deleta uma branch remota
