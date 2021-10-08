# Git-GitHub👨‍💻
Repositório com códigos do Git.
O git é uma ferramenta de controle de versões, gera uma linha do tempo com as alterações feitas no código e nele você pode ter acesso a todas essas alterações.

Já o GitHub é o repositório remoto, lugar para onde compartilhamos nossos códigos e também é chamado de rede social dos desenvolvedores.

## Configurações Usuário
- git config --global user.name "nome"
- git config --global user.email "link do email"
- git --version (Usado para ver a versão)
<hr>

## Conectar o repositório ao GitHub
| | |
|--|--|
| git init | inicia o repositório na pasta |
| git add | adiciona arquivos ao git |
| git commit -m "mensagem" | faz a mensagem do commit |
| git remote add origin LINK | adiciona o repositório local ao remoto |
<hr>

## Comandos para repositório remoto
| | |
|--|--|
| git pull | puxa os arquivos do repositório remoto |
| git add . | adiciona todos os arquivos ao git |
| git commit -m "mensagem" | faz a mensagem do commit |
| git push -u origin main | envia o arquivo para o GitHub |
<hr>

## Comandos básicos
| | |
|--|--|
| cd nomeDaPasta | abre a pasta escolhida |
| cd .. | retorna para pasta anterior |
| git status | vê o status atual do repositório |
| git log | lista todos os commits já realizados |
| git show | mostra as alterações feitas no último commit |
| git help | imprime uma lista de comandos mais usados |
| git rm | remove arquivos |
| git -mv | move ou renomeia arquivos |
| git reset --hard | volta seu repositório para o último commit |
<hr>

## Informações
<hr>

### Post request
É o pedido para que o repositório original faça a ação de puxar as atualizações do repositório, fork ou da branch
<hr>

### Fork
É uma cópia do repositório principal ao qual você pode fazer mudanças e features neste clone sem afetar o repositório principal
<hr>

### Area de stage
A area de stage é onde você controla a versão do seu repositório, esta área não grava as mudanças pois ela apenas inicia o repositório com o comando git add, as mudanças são gravadas com o comando git commit
<hr>

### Branchs
É uma ramificação do projeto, ela representa uma versão do projeto, se pode seguir uma linha de desenvolvimento a partir de cada branch
<hr>

### Main ou master?
O nome utilizado para as branchs é main. Caso a branch de seu projeto esteja com outro nome use o comando "git branch -m main" para alterar o nome
<hr>