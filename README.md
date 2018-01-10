#Curso de Git Básico#

##1) git status</h2>##

Reporta como está a situação do repositório no momento

##2) git add 'arquivo'##

Com esse comando o git passa a reconhecer o arquivo e sai do 'untracked'.
Assim já temos o arquivo adicionado preparado pro commit.

Se nesse status eu voltar a editar o mesmo arquivo então será necessário digitar o comando novamente:

`$ git add 'arquivo'`

Exemplo:

`$ git add "arquivo.txt"`

Caso queira colocar todos os arquivos:

`$ git add .`

##3) git commit -m "mensagem do commit"##

O 'commit' é o momento que vou avisar ao git: "pegue todos os arquivos do meu repositório e crie uma imagem dele" (snapshot).

É necessário adicionar o arquivo para podermos 'commitar':

`$ git add "arquivo.txt"`

##4) git log##

1. Mostra o código(hash) do commit, autor e data do commit.

`$ git log --decorate`

2. mostra qual branch pra qual branch.

`$ git log --author="Rafaela"`

3. mostra os commits por autor.

`$ git shortlog`

4. mostra em ordem alfabética os autores, quantos commits fizeram e quais eles foram.

`$ git shortlog -sn`

5. mostra a quantidade de commits por autor.

`$ git log --graph`

6. mostra em forma gráfica o que está acontecendo com os branchs e suas versões.

`$ git show 158459ee6cdbd200100fa2feb07fc635b173f5f9`

7. mostra as informações do commit pelo código(hash), mostrando quais arquivos foram modificados e suas alterações.



