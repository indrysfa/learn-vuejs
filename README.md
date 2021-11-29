# vue-ui

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

Jika gagal edit ini pada file `package.json`

```
"scripts": {
    "serve": "vue-cli-service serve",
    "build": "vue-cli-service build",
    "lint": "vue-cli-service lint"
  },
```

Jika menggunakan WSL

```
"scripts": {
    "serve": "export NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service serve",
    "build": "export NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service build",
    "lint": "export NODE_OPTIONS=--openssl-legacy-provider && vue-cli-service lint"
  },
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
