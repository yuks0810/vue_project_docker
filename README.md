# vue project

## 初回起動

### docker
vueの環境構築を行えるDocker

```
$ docker-comopse up -d --build
$ docker-compose exec web sh
```
### npm

```
$ npm install --prefix=/app/quiz
```

```
$ npm run serve
```

## version
versionは3.1.1に指定しているので、必要であればDockerfileで適宜変更

でDockerコンテナ構築、コンテナ内に移動した後に作業開始

## vue create
```
#app/ vue create
```

上記コマンドでプロジェクトを開始できる。


## 起動

```
$ cd quiz
$ npm run serve
```

## Bootstrap
https://bootstrap-vue.org/docs

すでにインストールしているが下記コマンドでインストール
```
$ npm install vue bootstrap bootstrap-vue
```

## npm

```
$ npm install --prefix=/app/quiz --save <package name>
```


## API

### Quiz API
https://opentdb.com/

