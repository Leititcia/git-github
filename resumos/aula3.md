# Desfazendo alterações no repositório local

### Remove versionamento (git init) de uma pasta errada
```
rm -rf .git
```

### Restaura o último estado de um arquivo
```
git restore <nome_do_arquivo>
```

### Altera a mensagem do último commit
```
git commit --amend -m "mensagem"
```
### Abre o editor para editar a última mensagem
```
git commit --amend 
```
para sair (esc :wq)

### Desfazer um commit
```
git reset --soft hashDoCommit
```
| git reset | função |
|-------|---------|
| --soft | retorna os arquivos que estavam posteriores ao commit indicado pelo hash |
| --mixed | padrão, adiciona a arvore de trabalho para adicionar novamente a área de preparação |
| --hard | ignora os arquivos e desaparece os arquivos |

### Histórico detalhado das alterações feitas
```
git reflog
```

### Remover arquivo
```
git reset nome_do_arquivo
```