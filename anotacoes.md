# Configurando git

# Começando um repositório

# Comandos básicos

`git init`: Inicia um repositório

`git add (. ou nome dos arquivos)` : Adiciona arquivos na área de stage

`git commit -m <mensagem>"` : commita os aquivos em stage com uma mensagem descritiva desse commit.

`git revert <id>` : reverte as mudanças do commit, em seguida cria um novo commit. revert não exclui o último commit.

`git log` : log com informações

`git checkout <id>` : move temporariamente para outro commit, mudando os arquivos

`git checkout main` : para voltar ao último commit

`git reset --hard <id>` : **CUIDADO** remove todos os commits posteriores ao commit selecionado
