# Подсказка по GIT

## Работа с локальным репозиторием
### Ввод данных пользователя
``````
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
``````

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
git checkout <branch_name> 
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
Пример:
![скриншот](example.jpg) 


### Слияние веток
```sh
git merge -d <branch_name>
``````
*Если надо выполнить коммит слияния, выполните команду git merge с флагом*
``````
git merge --no-ff existing_branch_name
``````

# Работа Git c GitHub