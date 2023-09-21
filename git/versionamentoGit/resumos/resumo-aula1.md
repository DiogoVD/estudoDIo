## Comandos git

-----remove o versionamento do git------
rm -rf .git

-----restaura o arquivo definido------
git restore <nome do arquivo>

----Altera a ultima mensagem do commit----
git commit --amend -m"nova mensagem"

-- realiza a restauração dos arquivos baseados no comit definido--

-realiza a adição dos arquivos posteriores ao commit definido para a area de preparação-
git reset  --soft <hash do commit(atravez do git log)>

-realiza a adição dos arquivos posteriores ao commit definido para a area de preparação-
git reset --mixed <hash do commit(atravez do git log)>

-realiza a o reset sem adicionar os arquivos a area de preparação-
git reset --hard <hash do commit(atravez do git log)>


