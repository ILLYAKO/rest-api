REST API. Практический Курс. Пишем Fullstack приложение на JavaScript
https://www.youtube.com/watch?v=lzQIhjElV_g&t=1180s&ab_channel=%D0%92%D0%BB%D0%B0%D0%B4%D0%B8%D0%BB%D0%B5%D0%BD%D0%9C%D0%B8%D0%BD%D0%B8%D0%BD

1. New folder /client

2. New file /client/index.html add script
<body>
    <script type="module" src="frontend.js"></script>    
</body>

3. New file /client/frontend.js add line from website vuejs.org
import Vue from 'https://cdn.jsdelivr.net/npm/vue@2.6.12/dist/vue.esm.browser.js'

4.Server app.js
4.1. npm init
4.2. npm install express
4.3. npm install -D nodemon
4.3.1. Add script to package.json
    "scripts": {
            "test": "echo \"Error: no test specified\" && exit 1",
            "start" : "node app.js",
            "dev":"nodemon app.js"
            }
4.4. app.js
const express = require("express");
const app = express();
app.listen(3000, ()=> console.log('Server has been started on port 3000 ...'))

4.5. npm run start
4.6. npm run dev

5.1. Bootstrap getbootstrap.com
5.2. copy CSS link to index.html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">

bootstrap spinner

6.1 npm i uuid

1:14:56




