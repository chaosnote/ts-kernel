# Typescript 常用功能

## 預先安裝

``` text
npm i -g typescript@5.4.5
npm i -g uglify-js@3.17.4
npm i -g uglifyjs-folder@3.3.0
```

## npm 指命

del kernel-0.0.0-development.tgz&&npm run build

## packages

``` json
"prestart": "npm uninstall kernel",
"start": "npm i ../kernel/dist/kernel-0.0.0-development.tgz"
```