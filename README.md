# NoName
## some links I want
* https://github.com/LiLittleCat/awesome-free-chatgpt/blob/main/README_en.md

### OSWAP JUICE
* https://owasp.org/www-project-juice-shop/
* https://pwning.owasp-juice.shop/

### KRACKEN
* https://notes.kraken-security.ru/kraken/tools/ataki-na-paroli/john
* https://notes.kraken-security.ru/kraken

### SQL INJ
* https://habr.com/ru/articles/725134/  (+- useless)
* https://github.com/CsEnox/CVE-2021-22911
* https://www.ptsecurity.com/upload/corporate/ru-ru/analytics/PT-devteev-Advanced-SQL-Injection.pdf
* https://proglib.io/p/sql-for-20-minutes
* https://portswigger.net/web-security/sql-injection/cheat-sheet


### PT onelove
* https://positive-technologies.notion.site/2024-1-PT-START-Basic-1-7f1896c562d44da9bfa19f8a48deb6e2
* https://www.notion.so/Linux_Basic-_-_-PT-START-2024-1-3044091292244096838c86476d0eb7ec (my)

### OSPF/RIP
* https://irinashpakk.gitbook.io/ospf
* https://sadykov.notion.site/7-OSI-L3-RIP-OSPF-ba1f93d1f9b64ef3a1298e5ad55ad539
* https://poligon218.ru/?s=ospf
* https://storm39.wordpress.com/%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5-%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%B8%D0%B5-%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8C-%D0%B0/

### Pentest
* https://academy.hackthebox.com/preview/certifications/htb-certified-penetration-testing-specialist

### VPN
* https://poligon218.ru/2022/07/02/%D0%BD%D0%B0%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D1%83%D0%BD%D0%BD%D0%B5%D0%BB%D0%B5%D0%B9-%D0%B7%D0%B0%D1%89%D0%B8%D1%82%D0%B0-%D1%82%D1%83%D0%BD%D0%BD%D0%B5%D0%BB%D0%B5%D0%B9/?ysclid=lxbnedfm9n665155889
* https://www.wireguard.com/

### CHEETER
https://pofoto.club/7751-malenkie-pingviny-44-foto.html


### SCANNING
* https://nmap.org/man/ru/index.html

```
└─$ sudo nmap -sU -pU:123 -Pn -n --script=ntp-monlist 10.129.173.157
Host discovery disabled (-Pn). All addresses will be marked 'up' and scan times will be slower.
Starting Nmap 7.91 ( https://nmap.org ) at 2021-07-10 01:49 +03
Nmap scan report for 10.129.173.157
Host is up (0.22s latency).
```
* https://github.com/Samsar4/Ethical-Hacking-Labs/blob/master/3-Enumeration/3-Enum4linux-Win-and-Samba-Enumeration.md

```
sudo enum4linux 10.129.173.157    
Starting enum4linux v0.8.9 ( http://labs.portcullis.co.uk/application/enum4linux/ ) on Mon Jul 10 01:39:58 2021
```

### DOCKER
```
$ docker pull cr.yandex/mirror/alpine
Using default tag: latest
latest: Pulling from mirror/alpine
59bf1c3509f3: Pull complete 
Digest: sha256:e7d88de73db3d3fd9b2d63aa7f447a10fd0220b7cbf39803c803f2af9ba256b3
Status: Downloaded newer image for cr.yandex/mirror/alpine:latest
cr.yandex/mirror/alpine:latest
```
* https://huecker.io/

## Pengvins
https://github.com/getflow/CTF/tree/main/AtomSkills2023


# PEnTEst
🖥 Большой выбор бесплатных машин
* https://tryhackme.com/

🔎 Nmap под разные ОС
* https://nmap.org/download.html

🗂 Перебор директорий - dirsearch
* https://github.com/maurosoria/dirsearch

☠️ Reverse Shell Generator
* https://www.revshells.com/

🔑 GTFOBins
* https://gtfobins.github.io/

🔐 Взлом хешей онлайн
* https://crackstation.net/

🔼 Апгрейд шела
** export TERM=screen
⌨️ Апгрейд шелла
** $ python3 -c 'import pty;pty.spawn("/bin/bash")'
export TERM=screen

⌨️ Rustscan
```
$ rustscan -a ip_address
```
⌨️ Nmap
```
$ nmap -sC -sV ip_address
```
⌨️ Dirsearch
```
$ dirsearch -e php,log,sql,txt,bak,tar,tar.gz,zip,rar,swp,gz,asp,aspx -u 'http://site.com'
```
⌨️ Gobuster
```
$ gobuster dir -w path_to_dict --url http://site.com -t 50
```

!! https://github.com/YaS5in3/Bug-Bounty-Wordlists !!

* Практика по хакингу ⚡️
☠️ Пентест и этичный хакинг для новичков

💣 Ломаем веб-сайт

🌵 SQL инъекция
🌵 Хакерский софт
🌵 Взлом хешей паролей
🌵 Мисконфиги и rsa ключи на сервере
🌵 Повышение привилегий в системе

Если интересна тема пентеста и хакинга на практике, поддержите видео лайком и комментарием на YouTube. Спасибо за поддержку! 💪

https://youtu.be/r4lvGDAm7jw

Большой выбор бесплатных машин
https://tryhackme.com/
https://hackthebox.com

🖥 Машина из видео
https://tryhackme.com/room/overpass

🔎 Nmap под разные ОС
https://nmap.org/download.html

🗂 Перебор директорий - dirsearch
https://github.com/maurosoria/dirsearch

😎 Команды из видео:

⌨️ Rustscan
```
$ rustscan -a ip_address
```
⌨️ Nmap
```
$ nmap -sC -sV ip_address
$ nmap -sC -sV -p22,80 ip_address
```
⌨️ Dirsearch
```
$ dirsearch -e php,log,sql,txt,bak,tar,tar.gz,zip,rar,swp,gz,asp,aspx -u 'http://site.com'
```
⌨️ John
```
$ ssh2john id_rsa > id_rsa.hash
$ john id_rsa.hash --wordlist=/usr/share/wordlists/rockyou.txt
```
⌨️ id_rsa SSH connect
```
$ ssh -i id_rsa user@ip_address
```





