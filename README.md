# Руководство по Git

## Что такое Git?

Git - это система управления версиями, которая позволяет отслеживать изменения в исходном коде проекта. Git помогает командам разработчиков работать над проектами совместно, сохраняя историю изменений и облегчая управление различными версиями кода.

## Основные команды Git

### Инициализация репозитория

- `git init`  
  Инициализирует новый Git-репозиторий в текущей директории.

### Проверка состояния

- `git status`  
  Показывает текущее состояние рабочей директории и индекс.

### Добавление файлов в индекс

- `git add <файл>`  
  Добавляет указанный файл в индекс (стадию) для следующего коммита.

- `git add .`  
  Добавляет все изменённые файлы в индекс.

### Выполнение коммита

- `git commit -m "Сообщение коммита"`  
  Создаёт новый коммит с указанным сообщением.

### Просмотр истории

- `git log`  
  Показывает историю коммитов в текущей ветке.

### Сравнение изменений

- `git diff`  
  Показывает изменения между рабочей директорией и индексом.

- `git diff --cached`  
  Показывает изменения между индексом и последним коммитом.

### Работа с ветками

- `git branch`  
  Показывает список веток в репозитории.

- `git branch <имя_ветки>`  
  Создаёт новую ветку с указанным именем.

- `git checkout <имя_ветки>`  
  Переключается на указанную ветку.

- `git merge <имя_ветки>`  
  Сливает указанную ветку с текущей веткой.

- `git branch -d <имя_ветки>`  
  Удаляет указанную ветку.

### Синхронизация с удалённым репозиторием

- `git remote add origin <URL>`  
  Добавляет удалённый репозиторий с указанным URL.

- `git push origin <имя_ветки>`  
  Отправляет изменения в удалённый репозиторий в указанной ветке.

- `git pull origin <имя_ветки>`  
  Загружает изменения из удалённого репозитория и сливает их с текущей веткой.

### Регистрация на GitHub

1. Перейдите на сайт [GitHub](https://github.com).
2. Нажмите на кнопку "Sign up" в правом верхнем углу.
3. Следуйте инструкциям для создания учётной записи.

### Основные понятия

- **Репозиторий (Repo)** - Хранилище, где Git сохраняет все версии проекта.
- **Коммит (Commit)** - Снимок текущего состояния файлов в репозитории.
- **Ветка (Branch)** - Отдельная линия разработки в репозитории.
- **Слияние (Merge)** - Процесс объединения изменений из одной ветки в другую.
- **Индекс (Staging Area)** - Промежуточное место для подготовки файлов перед коммитом.

## Полезные ссылки

- [Официальная документация Git](https://git-scm.com/doc)
- [Руководство по Git для начинающих](https://git-scm.com/book/ru/v2)

