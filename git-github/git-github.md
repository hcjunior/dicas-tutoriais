# GIT-GITHUB
**Arquivo explicativo com dicas e tutoriais do git**

## Configurações gerais

### Setar email
    git config --global user.email "hcj...@gmail.com"

### Setar usuario
    git config --global user.name "Heliton Junior"


## Repositorio local
**Comandos usados no repositorio local**

### Criar um novo repositorio
    git init

### Checar status de arquivos/repositorios
    git status

### Adicionar arquivos/diretorios (modificações feitas)

**Adicionar todas as mudanças**
```
git add .
```

**Adicionar arquivo/diretorio**
```
git add arquivo/diretorio
```

**Adicionar um arquivo que está listado no .gitignore**
```
git add -f arquivo/diretorio
```

### Comitar modificações
    git commit -m "mensagem"

### Remover arquivo/diretorio
**Remover arquivo/diretorio**
```
git rm arquivo/diretorio
```
**Remover arquivo/diretorio sem apaga-lo fisicamente**
```
git rm --cached
```
Para mais informações: <br>
https://github.com/da2k/curso-git-e-github-ninja/issues/32 <br>
https://git-scm.com/docs/git-rm

### Historico do git
**Mostrar historico**
```
git log
```
**Mostrar historico resumido em 1 linha**
```
git log --oneline
```
**Mostrar historico com diff (mostra as alterações que foram feitas neles)**
```
git log -p (pode colocar -1 / -2 / -3 para exibir uma quantidade especificas de commits)
```
**Mostra resumo geral do historico**
```
git log stat
```
**Exibir histórico com formatação específica (hash abreviada, autor, data e comentário)**
```
git log --pretty=format:"%h - %an, %ar : %s"
```
	
* %h: Abreviação do hash;
* %an: Nome do autor;
* %ar: Data;
* %s: Comentário.<br>
Exemplo pego em: [git.md]https://gist.github.com/leocomelli/2545add34e4fec21ec16