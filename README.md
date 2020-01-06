# AVATAR SERVER
Avatar Server for OSU!RIPPLE

## 2X
- Python3.6.x+
- Go

## Setting Up Avatar-Server
- For `avatar-server.go`
```bash
$ go get -u https://github.com/Uniminin/OSU-AVATAR-SERVER/blob/master/avatar-server.go
$ mkdir avatar-server
$ mkdir avatar-server/avatars
$ mv /root/go/bin/avatar-server-go ./avatar-server/avatar-server
$ wget -O 0.png https://github.com/light-ripple/OSU-AVATAR-SERVER/blob/master/Avatars/-1.png
$ wget -O 999.png https://github.com/light-ripple/OSU-AVATAR-SERVER/blob/master/Avatars/999.png
./avatar-server
```
- For `avatar-server.py`
```bash
$ mkdir avatar_server && cd avatar_server
$ wget https://raw.githubusercontent.com/Uniminin/OSU-AVATAR-SERVER/master/avatar-server.py
$ pip3 install -r requirements.txt
$ python3 avatar-server.py
```

## License ? :scroll: [![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Uniminin/OSU--AVATAR-SERVER/blob/master/LICENSE)
- Check Licence file for more info!
