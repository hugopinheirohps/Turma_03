## Aula 6
- Iniciar um repositório vazio
    git init

- Adicionar um arquivo a staging area
    git add (file)

- Adicionar todos os arquivos para a staging area
    git add .

- Realizar um commit 
    git commit -m 

- Realizar um commit com track em todos os arquivos unstaged
    git commit -am

- Mandar a staging area para o repo na nuvem 
    git push origin (repo)

- Pegar as alterações do repo na nuvem
    git push origin (repo)

- Criar uma branch 
    git branch (nome)

- Deletar uma branch 
    git branch -D (nome)

- Alterar o nome de uma branch 
    git branch -M (nome) (nome_novo) 

- Alterar de branch
    git checkout 

- Alterar de branch criando uma nova
    git checkout -b

- Retornar a branch para um commit 
    git revert (hash)

- Retornar a branch para um commit permitindo alterações de arquivos
    git reset (hash)

- Ver o status da staging area
    git status

- Ver o status da staging area de uma forma resumida
    git status -s

- Ver o Log da Tree
    git log

- Ver o log da Tree de uma forma resumida 
    git log --pretty

- Alterar a mensagem do último commit 
    git commit --amend 
    