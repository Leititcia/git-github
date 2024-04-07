
# Salvando Alterações no Repositório Local

### Mostra status da área de preparação
```
git status
``` 

### Mostra repositórios remotos que está conectado 
```
git remote -v
```

### Conecta a um repositório remoto
```
git remote add origin URLrepositorio
```

### Adiciona arquivo a área de preparação
```
git add nome_do_arquivo
```

### Descreve commit das alterações feitas
```
git commit -m"comentario"
```

### Exibe commits feitos
```
git log
```

### Para pasta não aparecer no commit
```
echo nome_pasta/ > .gitignore
```

### Para reconhecer diretório vazio no commit
```
touch nome_pasta/.gitkeep
```

### Adiciona todos os arquivos para a área de preparação
```
git add .
```