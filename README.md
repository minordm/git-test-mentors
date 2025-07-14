Команды git

git init - инициализация нового проекта

git add . - добавление всех файлов в индекс git для последующего коммита
    git add index.html - либо можно явно указать файл 

git commit -m "Initial commit" - создание коммита с сообщением "Initial commit"

после создания репозитория в github его нужно подключить в IDE
git remote add origin https://github.com/{my username}/{my repositories}.git
    проще всего просто скопировать https ссылку из github

git push -u origin main - отправка коммита в github

git pull - загрузить коммит из github

git branch - просмотр веток (* - текущая используемая ветка)
git branch {название ветки} - создание новой ветки
git branch -D {название ветки} - удаление ветки

git checkout {название ветки} - переключение на другую ветку
git checkout -b {название ветки} - создание и переключение на новую ветку

