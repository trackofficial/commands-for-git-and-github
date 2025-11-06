<h1>Commands for GitHub & Git</h1>

> This table is designed to work with GitHub and Git. It is created to memorize and help with projects. I'm still learning how to work, and that's why I created it to make it easier to navigate projects.

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
