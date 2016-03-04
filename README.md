## Falcor example

Use [n](https://github.com/tj/n) package manager, then clone this project somewhere and:

    npm install

    node index.js

Open `http://localhost:7777/index.html` in browser.

Also try:

    curl "http://localhost:7777/model.json?paths=%5B%5B%22greeting%22%5D%5D&method=get"

(url decoded would be: `model.json?paths=[["greeting"]]&method=get`)
