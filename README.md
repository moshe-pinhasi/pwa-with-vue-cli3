# A progressive web application with serverless (functions) using firebase

the code based on [this](https://blog.sicara.com/a-progressive-web-application-with-vue-js-webpack-material-design-part-1-c243e2e6e402) article.

## Project setup

```
npm install
```

### Compiles and minifies for production

```
npm run build
```

### run the dist

##### first you need to install globally

```
npm install -g serve
```

##### then after the build, run

```
serve dist/
```

### Lints and fixes files

```
npm run lint
```

### Run your unit tests

```
npm run test:unit
```

### Run your end-to-end tests

```
npm run test:e2e
```

## See the demo

[here](https://moshe-pinhasi.github.io/pwa-with-vue-cli3/#/)

change the url
1) vue.config
    - github: baseUrl: "/pwa-with-vue-cli3",
    - local: no need,
2) manifest
    - github: "start_url": "/pwa-with-vue-cli3",
    - local: "start_url": "/",
