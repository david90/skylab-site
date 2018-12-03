# Skylab Website

![Main Page](https://user-images.githubusercontent.com/1916493/49353823-c8727000-f6fa-11e8-82f1-49f67c0f4c9d.png)

### Update Content

The content is written with Jade templating language
Please reference the [Jade Syntax](https://naltatis.github.io/jade-syntax-docs/) for correct syntax.

### Installation

To start using the server, you will first have to install hexo-server.

```
$ npm install hexo-server --save
```

### Run
```
$ npm run start
```

### Generating static files with Hexo (for deployment)

```
$ npm run build
```

Update theme:

#### Compile Sass and css

```
$ npm run reload
```

```
$ gulp sass;gulp build:css;
```

```
$ gulp watch
```

```
$ gulp jade
```