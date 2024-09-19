# GIT Essentials

Tips:

1. Init vs Clone
Caso seja um novo projeto, criar o ficheiro de git no projeto:
* * * git init
Depois associar a um repositório:
*** git remote add origin git@github.com:xxxxxxxxxxxxx

Caso já exista um repositório com código:
> git clone xxxxxxxxxxxxxx

2. README
Por boas praticas cria-se sempre um ficheiro README.md com info do projeto

Commands:

> git clone
> git add ('git add .' inclui todos os ficheiros, ou pe 'git add index.html')
> git commit
> git push
> git pull
> git remote -v  // lista todos os remotes
> git push -u origin master // -u (upstream) irá marcar por defeito origin master, sendo apenas preciso escrever git push
 - origin
 - master é a branch
> git diff mybranch // mostra diferenças
> git merge

GIT  BRANCHING

> git branch // lista as branches
> git checkout nunodev // entra na branch
> git checkout -b feature-something // cria e entra na branch

40m
