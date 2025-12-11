<h1>Commands for GitHub & Git</h1>

> This table is designed to work with GitHub and Git. It is created to memorize and help with projects. I'm still learning how to work, and that's why I created it to make it easier to navigate projects.

### Russian Version (**English Version ↓**)

| Для чего | Команда | Объяснение |
|--------|------------|-------------|
| Инициализация | git init | Создаёт локальный репозиторий |
| Подключение к GitHub | git remote add origin <URL> | Привязывает удалённый репозиторий |
| Проверка подключения | git remote -v | Показывает список удалённых репозиториев |
| Добавление файлов | git add . | Добавляет все изменения в индекс |
| Первый коммит | git commit -m "Initial commit" | Сохраняет изменения в истории |
| Переименование ветки | git branch -M main | Переименовывает текущую ветку в main |
| Отправка на GitHub | git push -u origin main | Отправляет ветку и связывает её с удалённой |
| Получение изменений | git pull origin main | Подтягивает изменения из GitHub |
| Получение с rebase | git pull origin main --rebase | Вставляет локальные коммиты поверх удалённых |
| Проверка ветки | git branch | Показывает текущую ветку |
| Создание новой ветки | git checkout -b feature/имя | Создаёт и переключается на новую ветку |
| Переключение ветки | git checkout имя | Переход на другую ветку |
| Слияние ветки | git merge имя | Сливает указанную ветку в текущую |
| Удаление ветки | git branch -d имя | Удаляет локальную ветку |
| Просмотр истории | git log --oneline | Краткий список коммитов |
| Статус изменений | git status | Показывает текущие изменения и состояние |
| Обновление remote | git remote set-url origin <новый URL> | Меняет адрес удалённого репозитория |



| Шаг | Действие | Команда/Пример |
|-----|-----------|----------------|
| 1 | Инициализация Git в корне проекта | `git init` |
| 2 | Настройка `.gitignore` (чтобы не попадали лишние файлы) | Добавить шаблон для Android:<br>```.gradle<br>/build<br>/.idea<br>local.properties``` |
| 3 | Добавление файлов в индекс | `git add .` |
| 4 | Первый коммит | `git commit -m "init: базовый Android проект"` |
| 5 | Создание удалённого репозитория | На GitHub/GitLab/Bitbucket → «New Repository» |
| 6 | Привязка локального проекта к удалённому | `git remote add origin https://github.com/username/project.git` |
| 7 | Проверка подключения | `git remote -v` |
| 8 | Отправка проекта на сервер | `git branch -M main`<br>`git push -u origin main` |
| 9 | Дальнейшая работа (после изменений) | `git add .`<br>`git commit -m "feat: добавлен экран настроек"`<br>`git push` |
---

### English Version

| For what purpose | Command | Explanation |
|--------|------------|-------------|
| Initialization | git init | Creates a local repository |
| Connecting to GitHub | git remote add origin <URL> | Binds a remote repository |
| Connection check | git remote -v | Shows a list of deleted repositories |
| Adding files | git add . | Adds all changes to the index |
| The first commit | git commit -m "Initial commit" | Saves changes in the history |
| Renaming a branch | git branch -M main | Renames the current branch to main |
| Sending to GitHub | git push -u origin main | Sends a branch and links it to the deleted one |
| Getting changes | git pull origin main | Pulls up changes from GitHub |
| Getting from rebase | git pull origin main --rebase | Inserts local commits on top of deleted ones |
| Checking the | git branch | Shows the current branch |
| Creating a new branch | git checkout -b feature/name | Creates and switches to a new branch |
| Branch switch | git checkout name | Switch to another branch |
| Merging a branch | git merge name | Merges the specified branch into the current one |
| Deleting a branch | git branch -d name | Deletes a local branch |
| View history | git log --oneline | Short list of commits |
| Change status | git status | Shows current changes and status |
| Update remote | git remote set-url origin <new URL> | Changes the address of the remote repository |
