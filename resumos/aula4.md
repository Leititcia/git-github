
# Trabalhando com Branches
## Criando, Mesclando, Deletando e Tratando conflitos

### Troca para uma nova branch
```
git checkout -b teste
```

### Cria commit dentro da nova branch
```
echo "#commit-3-branche-teste" > commit-3-branch-teste.txt
```
```
git add .
```
```
git commit -m""
```

### Retorna para a branch main
```
git checkout main
```

### Lista últimos commits das Branches
```
git branch -v
```

### Mesclar Branches com a main
```
git merge nome_da_branch
```

### Lista as Branches
```
git branch
```

### Excluir branch
```
git branch -d nome_da_branch
```

## Conflitos de Merge
Acontece quando ocorrem alterações concorrentes.

### Retorna o conflito para o arquivo local
```
git pull
```
então, decidir quais alterações devem ser mantidas
```
git add .
```
```
git commit -m""
```
### Envia alterações para o repositório remoto
```
git push origin main
```