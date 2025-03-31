# broadcom-sta
broadcom-sta Update to kernel 6.14
ubuntu 24.04  / 6.14.0-061400-generic / gcc-14

```bash
sudo -i
cd /usr/src
git clone https://github.com/securecrt/broadcom-sta -b debain
dkms add -k 6.14.0-061400-generic /usr/src/broadcom-sta/amd64
dkms build broadcom-sta/6.30.223.271-debian -k 6.14.0-061400-generic
dkms install broadcom-sta/6.30.223.271-debian -k 6.14.0-061400-generic
```
