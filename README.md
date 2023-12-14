# custom_app

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```
### Module Federation
Список модулей которые необходимо пошарить, находится в vue.config.js в св-ве exposes
```js
 exposes: {
            './HelloWorld': './src/components/HelloWorld',
          },
```
В качестве ключа указываем ./HelloWorld, по нему мы будем в основном приложении импортировать компонент.
В качестве значения до компонента(Модуля) в текущем приложении.

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
