# yarn build 一键发布命令
````javascript
yarn init -y
"scripts": {
    "build": " rm -rf dist && parcel build src/index.html --no-minify --public-url ./ "
  },
  yarn build
  ````
