# Изучение GIT
Инициализация git в каталоге:
```
git init  
```

Статус git:
```
git status
```

Добавить файл для отслеживания версий:
```
git add <file>
```

Фиксация версий:
```
git commit -m "comment"
```

Настройка user:
```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

Показывает все "коммиты" в полной форме:
```
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
```
git reset --hard
```

Переключение на фиксированное состояние:
```
git checkout <commit id>
```

Переход в последнее место где были:
```
git switch -
```
