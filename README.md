# vue project

vueの環境構築を行えるDocker

```
$ docker-comopse up -d --build
$ docker-compose exec web sh
```

## version
versionは3.1.1に指定しているので、必要であればDockerfileで適宜変更

でDockerコンテナ構築、コンテナ内に移動した後に作業開始

## vue create
```
#app/ vue create
```

上記コマンドでプロジェクトを開始できる。
