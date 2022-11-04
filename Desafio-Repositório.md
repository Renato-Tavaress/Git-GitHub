# Introdução ao Git/GitHub

**Comandos Básicos Git**

Git init - (Iniciar o Git)

Git add "nome arquivo" - (Adiciona arquivo no controle de versão)

Git add . (Adiciona todos arquivos no controle de versão 

Git commit -m - (Cria um Commit e o -m(mensagem descrição do commit)) 

Git Status - (Mostra os arquivos no controle de versão)

Git Push - (Envia o versionamento do código para o github)

Git Reflog (Verifica o histórico de atualizações das versões)

Git reset --hard "id da versão" (navega sobre as versões do código)

Git branch "nome branch" (criar branchs para versões em desenvolvimento)

git checkout "nome da branch" (alternamos de branch)

git checkout -b "nome da branch de origem" "nome da nova branch"

git pull (traz atualizações dos servidores com a maquina local)

Git Merge "branch que quer unir a versão atual"(Uni as versões dos códigos)

Git Clone (clonar um repositório)

touch .gitIgnore (cria um arquivo a ser adicionado as restrições)



**Comandos Configurações**

git config --golbal user.email "email"

git config --global user.name "nome" 

git remote add origin "Url do Repositório" (vai estar definindo para qual repositório será enviado o código)

**Chave SSH**

ssh-keygen -t ed25519 -c "email" (gera uma chave publica e privada)

eval $ (ssh-agent -s) (gera um agent PID, adicione a chave PRIVADA a esse agent)

ssh -add id_ed25519 + senha que foi criada para a chave







