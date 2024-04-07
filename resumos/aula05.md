
# Trabalhando com Branches
## Comandos Úteis no Dia a Dia

### Baixa conteúdo do repositório remoto sem mesclar a branch local
```
git fetch origin main
```
```
git merge origin/main
```

### Mostra diferença entre as branches
```
git diff main nome_branch origin/nome_branch
```

### Clonar uma branch específica
```
git clone URLrepositorio --branch nomeDaBranch --single-branch 
```

### Abrir uma branch específica
```
git checkout nome_branch
```

### Mostra modificações arquivadas
```
git stash list
```
```
git stash apply
```
```
git stash pop
```

| apply | Mantem modificação na lista para uso posterior |
|-------|-------------------------|
| pop | Traz modificações de volta para a branch e exlui alteração mais recente |