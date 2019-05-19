# eslint-example

* create package.json

```
$ npm init
```

* add eslint package

```
$ npm install --save-dev eslint
```

* check eslint version

```
$ ./node_modules/eslint -v
```

* add script into package.json(check all js files)

```
  "scripts": {
    "lint": "eslint ./*.js"
  },
```

* run eslint

```
$ npm run lint
```
