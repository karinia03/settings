Node.js
===========

Official Web Site
-----------------

- [Node.js®](https://nodejs.org/en/)

Install
-------
- [Ubuntuに最新のNode.jsを難なくインストールする](http://qiita.com/seibe/items/36cef7df85fe2cefa3ea)

```bash
$ sudo apt-get install -y nodejs npm
$ sudo npm cache clean
$ sudo npm install n -g
$ sudo n stable
$ sudo ln -sf /usr/local/bin/node /usr/bin/node
$ sudo apt-get purge -y nodejs npm
```

Settings & Configiration
------------------------
### [eslint](http://eslint.org/)

- [ESLint 最初の一歩](http://qiita.com/mysticatea/items/f523dab04a25f617c87d)

```bash
$ sudo npm install eslint -g
$ sudo npm install esprima -g
$ sudo npm install -g eslint-plugin-node
```

[eslintrc](./conf/eslintrc)


### [jasmine](http://jasmine.github.io/)

- [日本語訳](http://mitsuruog.github.io/jasmine/)
- [Jasmine使い方メモ](http://qiita.com/opengl-8080/items/cf3acafda9756f4b04c9)

```bash
$ sudo npm install jasmine-node -g
```

### [Gulp.js](http://gulpjs.com/)

```bash
$ sudo npm install gulp -g
$ sudo npm install gulp-jasmine -g
```


elerning Site
---------------
- [ドットインストール](http://dotinstall.com/lessons/basic_nodejs)

