Passos para iniciar ao Github.

1* Na pasta do projeto
'git init'

2* adiciona-lo para o próximo git commit utilizando o comando
'git add "pasta ou arquivo"'

3* para persistir as alterações no nosso repositório LOCAL.
'git commit -m "nome do commit"'

4* Add caminho remoto repositorio no Github
'git remote add "nome"vitorma92 "caminho"project'

5* Como nosso repositório vai ficar centralizado no Github nós vamos chamar o nosso remote de origin
'git remote add https://github.com/<SEU_LOGIN_DO_GITHUB>/<NOME_DO_REPOSITORIO>.git'

6* E agora para enviar as alteraçes nós vamos utilizar o comando
'git push <NOME_DO_REMOTE> HEAD  '

(nome do remote será o origin)
(HEAD é a versão que estamos trabalhando).

Após a criação do repositorio, inicialização, caminhos do repositorio. 

Trabalhamos sempre com o passo 2,3 e 6. 

2 * coloca o arquivo na fila 
3 * commit localmente 
6 * envia para o repositorio