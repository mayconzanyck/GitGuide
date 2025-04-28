## 🛠️ Resolvendo Problemas Comuns

### Guardar alterações sem fazer commit
```bash
git stash
```

### Recuperar alterações guardadas
```bash
git stash pop
```

### Desfazer último commit (sem apagar alterações)
```bash
git reset --soft HEAD~1
```

### Desfazer último commit e apagar alterações
```bash
git reset --hard HEAD~1
```