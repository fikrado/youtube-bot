[![Messenger](https://img.shields.io/badge/telegram-blue?style=for-the-badge&logo=telegram)](https://t.me/fikrado_hacker)
[![Facebook](https://img.shields.io/badge/facebook-black?style=for-the-badge&logo=Facebook)](https://facebook.com/fikrado4048063)
<img hight="100" src="https://edube.org/uploads/media/default/0001/01/f9650614a78d8e6dd04216c700704a22e9c30ff7.png">
# youtube-bot
<img hight="100" src="https://eteknix-eteknixltd.netdna-ssl.com/wp-content/uploads/2019/06/2-61-880x606.jpg" >

**NOTE:** If you want to use Tor, be aware that YouTube can flag your video and delete the views after a while.

---

Tool to increase YouTube views

## Requirements

This tool depends on python3 and uses some libraries. In order to install them, you can use pip:

```sh
$ sudo pip3 install -r requirements.txt
```

### Optional (Incomplete)

If you want, you can install tor and privoxy, once selenium does not work very well with socks proxy.

#### Install Tor and on Mac OS X

```sh
$ brew install tor
```

#### Install Tor on Debian

```sh
$ sudo apt-get update
$ sudo apt-get install tor
```

#### Install Tor on ArchLinux

```sh
$ sudo pacman -Sy tor
```

## Usage
```sh
$ python3 bot.py --help
usage: bot.py [--visits VISITS] [--url URL] [--proxy PROXY] [--enable-tor]
              [-v] [-h]

Tool to increase YouTube views

Main Arguments:
  --visits VISITS  amount of visits per video, default: 1
  --url URL        YouTube video url
  --proxy PROXY    set the proxy server to be used. e.g: 127.0.0.1:8118
  --enable-tor     enable TOR support (You must have installed TOR at your
                   system)

Optional Arguments:
  -v, --verbose    show more output
  -h, --help       show this help message and exit
$
```

## Example
```sh
$ python3 bot.py --visits 2 --url https://www.youtube.com/watch?v=HAQQUDbuudY --verbose
```
[![youtube](https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=Youtube)](https://youtube.com/c/FikradoHacker)

