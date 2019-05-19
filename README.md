# eslint-example

## How to create (create once)

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

## How to run

* run eslint

```
$ npm run lint
```
