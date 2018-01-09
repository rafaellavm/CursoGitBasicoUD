<h1>Curso de Git Básico</h1>

<h2>1) git status</h2>

Reporta como está a situação do repositório no momento

<h2>2) git add <arquivo></h2>

Com esse comando o git passa a reconhecer o arquivo e sai do 'untracked'.
Assim já temos o arquivo adicionado preparado pro commit.

Se nesse status eu voltar a editar o mesmo arquivo então será necessário digitar o comando novamente:

git add <arquivo>

Caso queira colocar todos os arquivos:

git add .

<h2>3) git commit -m "mensagem do commit"</h2>

O 'commit' é o momento que vou avisar ao git: "pegue todos os arquivos do meu repositório e crie uma imagem dele" (snapshot).

É necessário adicionar o arquivo para podermos 'commitar':

git add <arquivo> 

