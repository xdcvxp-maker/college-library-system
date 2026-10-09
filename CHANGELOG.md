## — 2026-10-09

### (Тимлид)
* `docs: add final laboratory report` — сформирован итоговый отчет `LAB_REPORT.md` с обоснованием стека.
* `docs: create project regulation and git rules` — разработан регламент работы команды `REGULATION.md`.
* Инициализирована структура репозитория, создана интеграционная ветка `develop`.

### (Бэкенд)
* `feat: add user auth logic and access db connection` — реализован Python-скрипт `server.py` для авторизации.
* Создана пустая структура репозитория базы данных Microsoft Access (`library_db.accdb`).

### Добавлено (София / Фронтенд)
* `feat: create search ui components` — разработан интерфейс каталога книг `index.html`.
* `feat: design modern frontend UI catalog search and fill initial access records` — интегрированы стили и таблицы.

### Исправления (QA)
* `fix: resolve merge conflicts between backend and frontend logs` — **Успешно разрешен конфликт слияния** в файле `CHANGELOG.md` при объединении веток бэкенда и фронтенда.
* `fix: replace empty database file with valid MS Access format` — исправлена структура файла базы данных для корректного открытия в СУБД.
* `fix: change index.html encoding to UTF-8 for GitHub Pages compatibility` — исправлено отображение русского текста (убраны ромбики).
