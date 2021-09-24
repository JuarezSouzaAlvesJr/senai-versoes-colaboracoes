# senai-versoes-colaboracoes

os principais comandos utilizados para gerenciar o versionamento de um código são:
git init: para criar a estrutura inicial do repositório Git no computador local.
git add: para adicionar arquivos ao histórico do projeto, na staging.
git add .: para adicionar todos os arquivos na área de staging
git commit -m "comentário que descreve o que feito feito na commit": para registrar/salvar a alteração no repositório.
git push -u origin "nome da branch": para enviar as alterações feitas no repositório local para o repositório remoto.
git pull: para baixar as alterações feitas no repositório remoto para o repositório local.
git checkout -b "nome da branch": para criar uma nova branch, ou seja, um novo ramo de trabalho para realizar tarefas de forma paralela.
git merge "nome da branch": para mesclar branchs (ramos), ou seja, unificar os trabalhos feitos de forma paralela, colocando todos na trunk (tronco), no código-fonte da master. Também pode-se fazer o download das informações fornecidas pela outra branch, com o comando "git pull origin <nome da brach que terá seu conteúdo adicionado à outra>".
