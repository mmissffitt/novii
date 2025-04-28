Что угодно

mkdir lesson

cd lesson/

git init

git status

git remote add origin https://github.com/mmissffitt/novii.git 

git remote -v

touch README.md

explorer . - открыть проводник 

git add .

git commit -m "Что угодно"

git push -u origin master - ошибка:

remote: Permission to mmissffitt/novii.git denied to ritapp7.
fatal: unable to access 'https://github.com/mmissffitt/novii.git/': The requested URL returned error: 403 

исправление:

git config user.name "Anna"

git config credential.username "mmissffitt"

git push -u origin master

установка страпи - npx create-strapi-app qwerty --quickstart
