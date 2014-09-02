Cubox-i-Debian
============

<img src="http://www.igorpecovnik.com/wp-content/uploads/2014/08/cubox-login.png" alt="cubox-login" width="640" height="412">

Scripts to create an Image of Debian or only kernel for Cubox-i and Hummingboard

Images, manual and history:

http://www.igorpecovnik.com/2014/08/19/cubox-i-hummingboard-debian-sd-image/

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CUYH2KR36YB7W"><img style="padding:0;" width=74 height=21  src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt="Donate!" / border="0"></a>


Installation steps
------------------
1. <a href=http://releases.ubuntu.com/14.04/>Install Ubuntu 14.04 LTS</a> into your (virtual) PC
2. Login as root and execute:

```shell
sudo apt-get -y install git
cd ~
git clone https://github.com/igorpecovnik/Cubox-i-Debian
chmod +x ./Cubox-i-Debian/build.sh
cd ./Cubox-i-Debian
sudo ./build.sh
```
