**Resolvendo conflitos**

Como os conflitos acontecem no GitHub e como resolvê-los:

**GIT CLONE** - pegar o repositorio que esta no githube e copiar para o local, sua máquina.

**-> Para alterar seu arquivo depois de ter enviado para o GitHub**

1. abra o arquivo e faça a alteração

2. use **git add * ** (para add as alterações do GIT, o * serve para alterar em todas as pastas)

3. use **git status** para checar se deu certo e se ele foi pra staged

4. use **git commit -m "texto"**

5. envie o cod da maquina para o githube: **git push origin master**

   

**->Enviando um repositório para o github, tbm serve se caso queira alterar tbm.**

-  após uma alteração no commit, qualquer q seja, o comando para atualizar no console é:
  - git add *

isso significa que o arquivo moveu do modified para o staged

- após isso, o arquivo estar no staged, eu posso dar um commit novamente
- depois envia-lo para o github novamente com o: git push origin master

**-> Caso dê erro, no processo, significa que está ocorrendo um: **

**conflito de merge**( quando existe duas alterações na mesma linha de código, com isso o github não vai atualizar o repositório que vc quer, antes ele vai solicitar que os reponsáveis pela alteração fiquem todos com o msm código, vai ter que alterar manualmente na maq local)

-  se isso acontecer vc terá que puxar o repositório que está no github para sua maquina local, com o comando: 
  - git pull origin master

- isso vai gerar um arquivo .md, vc abre o arquivo copia e cola em um editor de texto, faz as alterações, salva e cola novamente no arquivo .md
- nesse momento o repositorio vai estar no **modified**, dê um **git add * ** e envie para o stage 
- cria um novo commit : **git commit -m "resolve conflitos"**
- após as alterações, vc envia para o github novamente com o comando: **git push origin master**



**-> Como baixar códigos prontos do github para maq local **

- vá até o codigo desejado, copie o link

- **git clone " cola o link"**

  

