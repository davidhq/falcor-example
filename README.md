## Falcor example

Use [n](https://github.com/tj/n) node version manager (optional), then clone this project somewhere and:

    npm install

    node index.js

Open `http://localhost:7777/index.html` in browser.

Also try:

    curl "http://localhost:7777/model.json?paths=%5B%5B%22greeting%22%5D%5D&method=get"

Url decoded would be: `/model.json?paths=[["greeting"]]&method=get`

## Additional Resources

Basic example this is based on is in the [main repo](https://github.com/Netflix/falcor)

For detailed high-level documentation **and videos** explaining the Model, the Router, and JSON Graph check out the [Falcor website](http://netflix.github.io/falcor).

For API documentation, go [here](http://netflix.github.io/falcor/doc/Model.html)

For a working example of a Router, check out the [falcor-router-demo](http://github.com/netflix/falcor-router-demo).

For questions and discussion, use [Stack Overflow](http://stackoverflow.com/questions/tagged/falcor).
