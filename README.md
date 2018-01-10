<h1>Curso de Git Básico</h1>

<h2>1) git status</h2>

Reporta como está a situação do repositório no momento

<h2>2) git add 'arquivo'</h2>

Com esse comando o git passa a reconhecer o arquivo e sai do 'untracked'.
Assim já temos o arquivo adicionado preparado pro commit.

Se nesse status eu voltar a editar o mesmo arquivo então será necessário digitar o comando novamente:

git add 'arquivo'

Exemplo:

git add "arquivo.txt"

Caso queira colocar todos os arquivos:

git add .

<h2>3) git commit -m "mensagem do commit"</h2>

O 'commit' é o momento que vou avisar ao git: "pegue todos os arquivos do meu repositório e crie uma imagem dele" (snapshot).

É necessário adicionar o arquivo para podermos 'commitar':

git add "arquivo.txt"

<h2>4) git log</h2>

Mostra o código(hash) do commit, autor e data do commit.

git log --decorate

mostra qual branch pra qual branch.

git log --author="Rafaela"

mostra os commits por autor.

git shortlog

mostra em ordem alfabética os autores, quantos commits fizeram e quais eles foram.

git shortlog -sn

mostra a quantidade de commits por autor.

git log --graph

mostra em forma gráfica o que está acontecendo com os branchs e suas versões.

git show 158459ee6cdbd200100fa2feb07fc635b173f5f9

mostra as informações do commit pelo código(hash)



