```

npm init

npm install --save react react-dom

npm install --save-dev webpack webpack-dev-server typescript ts-loader source-map-loader @types/jasmine @types/core-js @types/node babel-loader babel-core babel-preset-es2015 @types/react @types/react-dom babel-preset-react

"scripts": {
  "start": "./node_modules/.bin/webpack-dev-server --content-base app --inline --hot"
},

```


```

"scripts": {

  "test": "./node_modules/.bin/karma start --single-run",
  "tdd": "./node_modules/.bin/karma start",

},

```
