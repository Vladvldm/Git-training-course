# Git and Github course.

Git crash course by.
-------------------------------------------------
Основные команды:<br>
git init<br>
Позволяет инициализировать репозиторий в текущей папке

git status<br>
Показывает текущий статус
-------------------------------------------------
git add<br>
Отслеживает изменения файлов

git add index.html — добавляет index.html<br>
git add . — добавляет все файлы
-------------------------------------------------
git commit<br>
Сохраняет изменения в коммит<br>

git commit -m 'commit message' — создает коммит с сообщением<br>
флаг -m позволяет вводить соммит непосредственно в терминале
-------------------------------------------------
git branch<br>
Работа с ветками в репозитории

git branch — показывает список веток<br>
git branch branch-name — создает новую ветку branch-name<br>
git branch -D branch-name — удаляет ветку branch-name
-------------------------------------------------
git checkout<br>
Переключается на другую ветку

git checkout branch-name — переключается на последний коммит в ветке branch-name<br>
git checkout -b branch-name — создает и переключается на ветку branch-name<br>

git merge<br>
Совмещает текущую ветку с выбранной

git merge branch-name — совмещает текущую ветку с branch-name
-------------------------------------------------
git config<br>
Конфигурация и параметры git

git config --global user.name — Показывает имя пользователя<br>
git config --global user.name 'new user' — Изменяет имя пользователя<br>
git config --global user.email — Показывает email пользователя<br>
git config --global user.email 'test@mail.ru' — Изменяет email пользователя<br>
-------------------------------------------------
git push<br>
Заливает текущие локальные коммиты в удаленный репозиторий
-------------------------------------------------
git pull<br>
Забирает изменения с удаленного репозитория в локальный
-------------------------------------------------
git clone<br>
Клонирует проект с удаленного репозитория
-------------------------------------------------