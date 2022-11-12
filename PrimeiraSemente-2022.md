# Olá Mundo!

Conjunto de comandos do git, para trabalhar com controle de versão:
(Depois de criado o arquivo inicial)

```
git init (criar o repositório`
git add -A (adicionar tudo ao repositório)
git status (para checar)
git commit -m "Comentário do respectivo commit" (criar um commit)
```



Talvez seja necessário utilizar para o git me reconhecer:

```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```


Outros comandos (precisa contextualizar)

```
git remote add origin endereçoDoRepositorioNoGithub
git push -u origin master
```


Quando alterações forem implementadas e quisermos adicionar um novo commit para o projeto, fazemos:

```
git add -A (para checar)
git commit -m "Comentário do respectivo commit"
git push (para enviar para o repositório no github)
```


Quando for usar o repositório em outro computador:

`git clone endereçoDoRepositorioNoGithub`



FIM