funções git 😎:

1- git clone:

Esse comando é usado para criar uma cópia local de um repositório Git remoto. Ele baixa todo o histórico de commits, branches e arquivos do repositório remoto para o seu diretório local.

Ex: git clone https://github.com/usuario/repositorio.git

2- git add:

Esse comando é usado para adicionar arquivos ou alterações específicas ao índice do Git. O índice é uma área intermediária onde você prepara os arquivos para um próximo commit.

Ex: git add .

3- git commit:

Esse comando é usado para criar um novo commit no histórico do Git. Um commit representa um conjunto de alterações que você deseja registrar.

Ex: git commit -m "Adicionando funcionalidade X"

4- git push:

Esse comando é usado para enviar os commits locais para um repositório remoto. Quando você faz alterações e commits no seu repositório local, o comando git push permite que você envie essas alterações para um repositório remoto, como o GitHub.

Ex: git push origin main

5- git pull:

Esse comando é usado para atualizar seu repositório local com as alterações mais recentes do repositório remoto. Ele combina o comando git fetch, que busca as alterações do repositório remoto, com o comando git merge, que mescla as alterações no seu branch local.

Ex: git pull origin main

6- gh pr create:

Esse comando é usado para criar uma nova pull request (solicitação de recebimento de código) no GitHub diretamente da linha de comando. Ele permite que você especifique a branch de origem e a branch de destino, além de adicionar uma descrição à pull request.

Ex: gh pr create --title "Adicionar nova funcionalidade" --body "Esta pull request adiciona a funcionalidade X"
