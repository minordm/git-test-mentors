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
