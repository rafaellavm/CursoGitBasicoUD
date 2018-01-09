<h1>Curso de Git Básico</h1>

1) git status

Reporta como está a situação do repositório no momento

2) git add <arquivo>

Com esse comando o git passa a reconhecer o arquivo e sai do 'untracked'.
Assim já temos o arquivo adicionado preparado pro commit.

Se nesse status eu voltar a editar o mesmo arquivo então será necessário digitar o comando novamente:

git add <arquivo>

Caso queira colocar todos os arquivos:

git add .

3) git commit -m "mensagem do commit"

O 'commit' é o momento que vou avisar ao git: "pegue todos os arquivos do meu repositório e crie uma imagem dele" (snapshot).

É necessário adicionar o arquivo para podermos 'commitar':

git add <arquivo> 

