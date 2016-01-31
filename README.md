## Dockerfile: Debian - PHP 5

[![Build Status](https://travis-ci.org/ericmdev/php5.dockerfile.svg?branch=master)](https://travis-ci.org/ericmdev/php5.dockerfile)

**Dockerfile** of [Debian](https://www.debian.org/) [PHP 5](https://secure.php.net/):

- php5-dev
- php5-common
- php5-cli
- php5-mcrypt
- php5-mysql
- php5-gd
- php5-imagick
- php5-curl
- php5-intl

*Requirements*
- [Docker](https://www.docker.com/) 

*Base Docker Image*
- [ericmdev/essentials](https://hub.docker.com/r/ericmdev/essentials/)

*Docker Pull Command*
- `docker pull ericmdev/php5`

### Usage

Build the image.

    $ make

Run the container.

    $ make run

Dig into the container.

    $ make exec

*See the `Makefile` for more options.