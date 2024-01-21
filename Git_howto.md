# Подсказка по GIT

### Создание репозитория:
```sh
git init
```

### Добавление файла:
```sh
git add
```

### Проверка статуса репозитория:
```sh
git status
```

### Фиксация коммита сообщением:
```sh
git commit
```

### Просмотр истории коммитов:
```sh
git log
```

### Просмотр истории коммитов в одну строку:
```sh
git log --oneline
```

### Просмотр изменений:
```sh
git diff
```
## Работа с ветвлением:
### Перемещение по веткам:
```sh
<<<<<<< HEAD
git checkout <branchname> 
=======
git checkout <branch_name> 
>>>>>>> branch_3
```

### Отображение всех веток
```sh
git branch
```

### Создание новой ветки 
```sh
git branch <new_branch>
```

### Удаление ветки
```sh
git branch -d <new_branch>
```

### Отображение веток в графическом виде
```sh
git log --oneline --graph
``````

### Слияние веток
```sh
git merge -d <branch_name>
``````
