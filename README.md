leiame

Alguns comandos no git para resetar altercoes
git reset 
--soft = volta anterior para ser comitado novamente.

--mixed = volta para ser adicionado e comitado novamente.

--reset = volta tudo sem deixar rastro.

git add (arq) ou -A -> git commit -m "Message"

git branch (nome) para criar
git push origin (name) irá subir todas branch mencionadas
git checkout (nome) para alterar de branch

git branch -d (name) delete branch
git push origin :(name) = delete branch remote

git diff mostra oque foi alterado no arquivo

git diff --name-only = somente nome do arquivo modificado

após termina todo o processo localmente e caso queira enviar para o seu repositório basta utilizar o comando
git push -u origin master = para subir pela primeira vez.
git push origin master = para subir alteraçoes comuns

Utilizando o .gitignore voce consegue esconder arquivos que voce nao deseja que subam para o repositorio remoto.
basta criar o arquivo e inserir dentro dele nomes, diretorios ou somente extensoes que devem ser ignoradas.

Caso voce tenha feito merda e precise voltar atras para nao ficar fora do ar seu serviço, mas voce não quer perder o código que trabalhou voce pode usar o revert que irá voltar atras no commit que voce quiser, porem nao irá perder os commits feitos anteriormentes, voce podera entrar neles novamente quando estiver pronto para acessar novamente e resolver o bug.
git revert --no-edit (key da branch)

para pegar atualizacoes do repositorio remoto ou de outro usuario bastar usar o pull.
git pull origin master

git clone (url do projeto)  = voce clona um projeto no git para poder fazer suas modificacoes como queira.

Para contribuir com um projeto basta acessar o projeto original -> FORK e após dar um clone em sua maquina e fazer as contribuiçoes que vc deseja e depois de dar um push e depois enviar um pull request no diretorio principal
