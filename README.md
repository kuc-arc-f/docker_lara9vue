# docker_lara9vue

 Version: 0.9.1

 Author  : Kouji Nakashima / kuc-arc-f.com

 date    : 2022/06/01
 
 update  : 2022/06/06

***

### summary

docker setup, nginx + php8.1 + laravel + vue 2

***
* php:8.1.0-fpm
* nginx
* mysql
* laravel 9
* vue: 2.6

***
### setup

* docker-compose
```
sudo docker-compose  up
```

* laravel install
```
php composer.phar create-project --prefer-dist laravel/laravel myblog "9.*" 
```

***
### laravel mix
```
npm i

#dev（開発ビルド）
yarn dev

# watch(監視モード)
yarn watch

#prod
yarn prod

```

***
### blog

***
