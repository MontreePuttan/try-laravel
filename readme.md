composer create-project --prefer-dist laravel/laravel ./



# **How to install on MAC**


# Contents
* [Install-Composer](##1.Install-Composer)
* [Install-composer-globally-into our-system](##2.Install-composer-globally)
* [Installing-Laravel](##3.Installing-Laravel)
* [Create-Project](##4.Create-Project)



## 1.**_Install-Composer_**
Go to: [composer-download](https://getcomposer.org/download/)

```
$ php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
```
```
$ php -r "if (hash_file('sha384', 'composer-setup.php') === '48e3236262b34d30969dca3c37281b3b4bbe3221bda826ac6a9a62d6444cdb0dcd0615698a5cbe587c3f0fe57a54d8f5') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
```
```
$ php composer-setup.php
```
```
$ php -r "unlink('composer-setup.php');"
```

## 2.**_Install-composer-globally_**

Go to: [composer-getstart-globally](https://getcomposer.org/doc/00-intro.md#globally)

```
$ mv composer.phar /usr/local/bin/composer
```


## 3.**_Installing-Laravel_**
```
$ composer global require laravel/installer
```

## 4.**_Create-Project_**
```
$ composer create-project --prefer-dist laravel/laravel blog
```
