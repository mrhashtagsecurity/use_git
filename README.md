# Git Hub
---

Em seu primeiro repositório, ou algum que esteja com problemas, de autenticação no "https" a solução é bem simples, adicione seu login e senha na url
Assim que é criado um repositório, automaticamente o GitHub te mostra alguns comandos iniciais:
´´´
echo "# use_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mrhashtagsecurity/use_git.git
git push -u origin master
´´´


Agora modifique somente essa linha de código, adicionando login e senha antes da url;
´´´
git remote add origin https://usuario:senha@github.com/mrhashtagsecurity/use_git.git
´´´


Caso vc já tenha feito o primeiro passo do GitHub, não haverá como alterar com o mesmo codigo pra isso use:

´´´
git remote set-url origin https://usuario:senha@github.com/mrhashtagsecurity/use_git.git
´´´

*agora é só continuar com o PUSH e tudo certo ;)*