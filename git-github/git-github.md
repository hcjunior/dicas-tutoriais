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