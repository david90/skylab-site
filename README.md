# Skylab Website


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