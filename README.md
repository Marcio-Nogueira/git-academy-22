# git-academy-22

## git init
Inicialização de um projeto
```bash
git init
```
## Configurações iniciais
```bash
git config --global user.name "username"
git config --global user.email "user@email.com"
```

## Controle de alterações
Para visualizar as alterações feitas, vamos usar:
```bash
git status
```

## Criando commits
Primeiramente precisamos adicionar as mudanças e enfim 'commitar':
> Utilize o ponto para adicionr todas as alterações do projeto.
```bash
git add .
git commit -m "descricao das alteracoes"
```

## Branches
Podemos ramificar o código usando branches para criar uma nova, executamos:
```bash
git switch --create <nome-da-nova-branch>
# or
git checkout -b <nome-da-nova-branch>
```
- Listando Branches
```bash
git branches
```

- Apagando Branch
```bash
git branch - D <nome-da-branch>
```

...
## GitHub
- Adcionando um remote origin:
```bash
git remote add origin htttps://github.com/user/repo-name.git
```
- Subindo alterações:
```bash
git push -u origin <nome-da-branch> 
# caso a branch não exista no GitHub use:
git push -u origin <nome-da-branch> #ele criará a branch no GitHub

