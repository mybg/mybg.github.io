# MYB - OPEN SOURCE MEDIA LIBRARY

![MYB](https://mybg.github.io/p/img/coverofficial.jpg)


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


## Features

- Easy to use
- Lightning fast
- Low end systems freindly



## Host MYB yourself!


## Installation on ubuntu/debian


Install apashe2 & git

```sh
sudo apt-get install apache2
sudo apt-get install git
```

Start apache2.service

```sh
sudo service apache2 start 
```
Clone MYB Repository
```sh
cd /var/www/html
sudo git clone https://github.com/mybg/mybg.github.io.git
```
Getting Ready
```sh
sudo mv mybg.github.io/* .
sudo service apache2 restart
```
# Now Head Over to localhost and MYB should be running.




