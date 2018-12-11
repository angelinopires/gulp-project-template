## Workflow para front-end usando Gulp



Toda a estrutura deste workflow foi baseada nesse artigo: https://nystudio107.com/blog/a-gulp-workflow-for-frontend-development-automation

### Pré-requisitos:

* OS Windows: é preciso do Node.js e o NPM:
`` https://nodejs.org/en/download/ ``



* OS Linux: é preciso do Node.js, NPM e NVM:
``https://medium.com/collabcode/como-instalar-node-js-no-linux-corretamente-ubuntu-debian-elementary-os-729fb4c92f2d``



* OS Windows/Linux: Caso não tenha o Gulp, instale-o globalmente:
``npm install gulp -g``



### Instalação:

Após clonar o projeto você irá precisar realizar os itens abaixo:

* Baixe o projeto e use:
``npm install``

* Para rodar o projeto:
``gulp``

### Comandos:

``gulp -> build básico para o desenvolvimento do cotidiano``

``gulp imagemin -> Minifica imagens, mantendo a proporção e diminuindo o tamanho``

### Sobre:

Apesar do artigo citado acima possuir um Script muito mais completo, ele também te deixa mais confuso. O que eu fiz foi abstrair o necessário para o desenvolvimento cotidiano de seu front-end e atualizar algumas dependências que eram necessárias.


### Estrutura de pastas:

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

### Changelog

* 11/12/2018 - O básico necessário foi criado. Ainda irei adicionar outras features e um servidor local para o desenvolvimento.