# --Netlify

1 створити файл netlify.foml
[build]
   publish = "build"

   [[redirects]]
   from = "/"
   to = "/index.html"
   status = 200

2 написати команду - npm install netlify-cli -g
