# docker-laravel
Docker container - Ubuntu 16.10, php7, composer, phpunit, &amp; laravel installer

# Base Docker Image

Stock Ubuntu 16.10

# Linux Components

* git
* Zip
* wget
* Vim
* sqlite3
* Curl
* Redis

# PHP7

* php7.0
* php7.0-fpm
* php7.0-mbstring
* php7.0-xml
* php7.0-curl
* php7.0-json
* php7.0-zip
* php7.0-sqlite3
* phpRedis 7

# PHP Components

* [Composer](https://getcomposer.org) - Current stable release
* [hirak/prestissimo](https://github.com/hirak/prestissimo) - Composer addon that speeds up composer
* [phpunit/phpunit](https://phpunit.de) - Current stable release
* [Laravel Installer](https://laravel.com) - Current stable release

# Misc

* apt-get update and upgrade run
* Composer bin added to PATH
* apt-get clean run and temp files deleted