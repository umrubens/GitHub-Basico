# GitHub-Basico
Neste post faço um tutorial simples para utilizar o Git no Windows e comitar seus códigos no GitHub. 

Git Para Iniciantes, 

Este processo foi realizado em sistema operacional Windows, porem pode se aplicados em Mac e Linux.
O GitHub é uma plataforma para hospedagem e controle de versão de código utilizando o sistema Git como base. Também e uma comunidade para programadores do mundo todo colaborarem em projetos pessoais e de código-aberto.
Ok, vamos lá!
Vamos seguir do princípio que você criou sua conta no Git, criou o seu repositório e realizou download Git para desktop, instalando o mesmo em seu computador. 

# Para inicializa um novo repositório digite o seguinte comando no terminal do Git “Git Bash Here”. Dentro da pasta do seu projeto no desktop.
# git init
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/1.PNG)

Será criado uma estrutura básica do repositório com nome “.git” por padrão a mesma ficara oculta e não poderá ser excluída o editada, caso aconteça algo semelhante apresentara problemas no seu projeto.   

Para adicionar todos os arquivos localizado dentro da pasta do seu projeto o as atualizações do repositório, execute o comando.
# git add "nome do arquivo" (Obs: Permitira adicionar um arquivo por vez do seu projeto) 
# “git add .” (Permitira adicionar todos os arquivos contido dentro da pasta do projeto.)
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/2.PNG)

verificar o status atual do seu repositório Git.
# git status
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/3.PNG)

Confirme as alterações com o comando commit -m no qual “mensagem” geralmente é um resumo das alterações.
# git commit -m " mensagem do commit"
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/4.PNG)

Este comando serve para gerenciar as informações nele registradas. Basicamente, toda ação que você executa dentro do Git onde os dados são armazenados.
# git reflog
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/5.PNG)

Configure seu usuário do GitHub com os comandos abaixo, adicione e-mail do git e seu nome de usuário. 
# git config --global user.email "email@email.com"
# git config --global user.name "nome"
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/6.PNG)

Adicione o git remote, ou seja, o link para o servidor do seu projeto no GitHub:
git remote add origin <url>
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/7.PNG)

Por fim, envie as alterações com o comando.
git push --set-upstream origin master
![alt text](https://github.com/umrubens/GitHub-Basico/blob/master/PNG/8.PNG)
