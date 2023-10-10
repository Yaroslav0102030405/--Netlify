# --Netlify

1 створити файл netlify.foml
[build]
   publish = "build"

   [[redirects]]
   from = "/"
   to = "/index.html"
   status = 200

2 написати команду - npm install netlify-cli -g
3 ще одну команду - netlify login 
в браузере відкриється вкладка де треба підтвердити авторизацію
(пілся підтвердження закриваємо вкладку)
4 добавляємо в файл packade.json додаємо скрипти для деплойда
"predeploy": "npm run build",
    "deploy": "netlify deploy -p"
    5 видалити свойство  "homepage": "",
    6 водимо команду -  npm run deploy
    7 в терміналі вибрати команду створити
    8 підтвердити аавтора
    9 ввести имя сайта
