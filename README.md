# Desafio de projeto da DIO Git/GitHub

### Resumo dos principais comandos no GIT usando CLI com o Bash



##### Listando comandos usados no Git:

+ $ git

##### Verificando a versão do Git instalado em seu computador:

+ $ git --version

##### Visualizando o status da sua árvore de trabalho, onde podemos ver a necessidade de se fazer um add ou commit:

+ $ git status

##### Inicializando ou reiniciando um repositório já existente:

+ $ git init

##### Visualizando as branches que estão sendo trabalhadas localmente:

+ $ git branch

##### Criando uma branch:

+ $ git branch nova-branch

##### Renomeando a branch:

+ $ git branch -M "main" (renomeamos para main)

##### Preparando apenas um arquivo ou todos arquivos (criados ou alterados) para o commit:

+ $ git add nome_do_arquivo (apenas o arquivo mencionado será considerado para o commit)

+ $ git add . ou -A ( o ponto "." ou "-A" prepara todos os arquivos para o commit)

##### Fazendo um commit:

+ $ git commit -m "Primeiro commit"

 ##### Criando conexão com o repositório remoto:

+ $ git remote add origin http://github.com/souza-aldeni/repositorio  (origin - é o nome dado a conexão)

##### Atualizando o GitHub através do seu repositório local:

+ $ git push origin main 

##### Fazendo um merge:

+ $ git merge nome-da-branch

##### Mudando de branch:

+ $ git checkout minha-branch

##### Criando e mudando para uma nova branch:

+ $ git checkout -b "nova-branch" (além de criar uma nova branch já entra automaticamente nela)

##### Clonando um repositorio do GitHub:

+ $ git clone https://github.com/souza-aldeni/repositorio

##### Visualizando as configurações do Git:

 + $ git config --list

##### Alterando o config do GIT:

+ $ git config --global --unset user.email (apaga o e-mail)

+ $ git config --global --unset user.nickname (apaga o nome)

+ $ git config --global --user.email "e-mail@email.com.br" (inclui o e-mail)

+ $ git config --global --user.nickname "seu nome" (inclui o nome)

##### Verificando as conexões remotas no repositorio local:

+ $ git remote
+ $ git remote -v

##### Alterando o endereço da conexão remota em seu Git:

 + $ git remote remove nome-da-conexao (removeu a conexão)
 + $ git remote add origin https://github.com/novo-endereco (incluiu uma nova conexão)


