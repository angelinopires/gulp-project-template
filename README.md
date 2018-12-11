## A Workflow to front-end with Gulp.js



All the structure of this workflow was based on this article: ``https://nystudio107.com/blog/a-gulp-workflow-for-frontend-development-automation``



### What do you need:


* OS Windows: You should install Node.js and NPM:
`` https://nodejs.org/en/download/ ``



* OS Linux: You'll need Node.js, NPM and NVM:
``https://medium.com/collabcode/como-instalar-node-js-no-linux-corretamente-ubuntu-debian-elementary-os-729fb4c92f2d``



* OS Windows/Linux: If you don't have gulp.js, install it globally:
``npm install gulp -g``



### Almost there, just a few things before

The package.json of this workflow was builded to give you more productivity and time to develop more and more consistent. Therefore, you just need to change a few inputs:

* Insert your project name on the "name" field;

* Insert your project descripton on the "description" field;

* At the repository field, insert your project URL at "url";


### Setup:

* Get the project:
``git clone https://github.com/angelinopires/A-workflow-to-front-end.git``

* Move to the folder and then install all dependencies:
``cd A-workflow-to-front-end; npm install ``

* To run the project, use:
``gulp``

* Access http://localhost:8080/index.html to see your webpage.



### Commands:

``gulp -> basic command to run and watch your changes``

``gulp imagemin -> Minify images``



### Folder Struct:

```

├── .babelrc
├── .browserslistrc
├── build
│   ├── cs
│   ├── fonts
│   ├── html
│   └── js
├── craft
├── .git
├── .gitignore
├── gulpfile.js
├── node_modules
├── package.json
├── public
│   ├── css
│   ├── favicon.ico
│   ├── favicon.png
│   ├── fonts
│   ├── img
│   ├── js
│   ├── webappmanifest.json
│   └── web.config
├── README.md
├── scripts
├── src
│   ├── conf
│   ├── scss
│   ├── fontello
│   ├── fonts
│   ├── img
│   ├── js
│   └── json
└── yarn.lock
```



### About:

The original workflow was very tricky, that's why I decided to change and simplify everything. For now, only the development script was created, and I have plans to modify and improve the Deploy script as well.

If you have better gulp tasks, hints or anything else, open a Pull Request :)   



### Changelog

* 11/12/2018 - Local server added with gulp-connect. Access via: http://localhost:8080/index.html

* 11/12/2018 - Only the basic script was created. I still need to test on Linux OS and create a local server.