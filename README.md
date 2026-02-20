# Изучение GIT
Инициализация git в каталоге:
```sh
git init  
```

Статус git ___(самое важно для Михаила!!!!!)___:
```sh
git status
```

Добавить файл для отслеживания версий:
```sh
git add <file>
```

Фиксация версий:
```sh
git commit -m "comment"
```

Настройка user:
```sh
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

Показывает все "коммиты" в полной форме:
```sh
git log
```

Показывает все "коммиты" в краткой форме:
``` sh
git log --oneline --all --graph
# --oneline - в одну линию
# --all - все веткиgo
# --graph - ввиде графа
```

Откат до последнего "коммита":
```sh
git reset --hard
```

Переключение на фиксированное состояние:
```sh
git checkout <commit id>
```

Переход в последнее место где были:
```sh
git switch -
```

Список веток:
```sh
git branch
```

Перенестись в нужную ветку:
```sh
git checkout <название ветки/id commit>
```

Добавить удалённый(далеко) репозиторий:
```sh
git remote add origin <ссылка>
```
Посмотреть список удалённый(далеко) репозиторий:
```sh
git remote -v
```

Удаленние удалённого репозитория:
```sh
git remote  remove origin
```

Перемеиновать текущую ветку:
```sh
git branch -M <новое название>
```

Отправить ветку в удалённый репозиторий:
```sh
git push -u origin <название ветки>
```