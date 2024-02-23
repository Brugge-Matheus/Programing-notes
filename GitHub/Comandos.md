
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

*Neste momento as alterações feitas em uma branch não estará presente na outra a não ser que você de o comando*
## Fazendo Merge

=> `git merge NomeDaBranch` - Junta uma branch com outra branch.

=> `git branch -d NomeDaBranch` - Deleta uma branch local
=> `git push origin --delete nomeDoBranchRemoto` - Deleta uma branch remota

=> `git merge --abort` - Aborta um merge que esta em processo

## Corrigindo mensagem de commit

=> `git log --oneline` - Lista os commits

=> `git commit --amend -m "#"` - Troca a mensagem do commit Head

## Voltando para commits com revert
*Volta para a branch selecionada mantendo o histórico*

=> `git revert HEAD --no-edit` - volta para o ultimo commit feito mantendo o histórico


## Voltando para commits com reset
*Reseta completamente para a branch selecionada sem salvar histórico*

=> `git reset "códigoDoCommit"` - Volta para o commit selecionado sem manter o histórico

=> `git stash` - Cancela todas as alterações que não foram commitadas ainda


## Diferença entre commits

=> `git diff codigoCommit1 codigoCommit2` - Mostra as diferenças entre os dois commits que foram selecionados 


## Resolvendo conflito de merge
### Button changes 
 ![[Pasted image 20240222230038.png]]
=> `Accept Current Changes` - 
=> `Accept Incoming Changes` - Aceita somente as novas funcionalidades
=> `Accept Both Changes` - junta as duas modificações de harmoniza o código 
=> `Compare Changes` - 

=> Depois de resolver os conflitos faça commit das alterações

