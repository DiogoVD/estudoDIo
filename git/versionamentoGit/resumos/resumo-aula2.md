## Aula 2 criando branchs

### comandos

--Cria uma branch nova--
git checkout -b <nome da nova branch>

--Alterna entre as branchs--
git checkout <nome da branch que deseja ir>

--Junta as branchs definidas com a main--
git merge <nome da branch que deseja juntar a main/master>

--Lista as branchs ativas--
git branch

--Apaga as branchs definidas--
git branch -d <nome da branch que deseja deletar>


## Tratando conflitos

--Baixa as alteraçoes do branch remoto sem juntar--
git fetch origin main

--Verifica as diferenças entre os repositorios local e remoto--
git diff main origin/main

--Clona apenas a branch definida do repositorio--
git clone <caminho do repositorio> --branch<nome da branch a ser clonada> --single-branch

--lista a alteraçãorealizada na branch para criar uma novas--
git stash
git stash list
git stash pop
git stash apply


