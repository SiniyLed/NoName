# NoName
some links I want
https://github.com/LiLittleCat/awesome-free-chatgpt/blob/main/README_en.md

OSWAP JUICE
https://owasp.org/www-project-juice-shop/
https://pwning.owasp-juice.shop/

KRACKEN
https://notes.kraken-security.ru/kraken/tools/ataki-na-paroli/john
https://notes.kraken-security.ru/kraken

SQL INJ
https://habr.com/ru/articles/725134/  (+- useless)
https://github.com/CsEnox/CVE-2021-22911
https://www.ptsecurity.com/upload/corporate/ru-ru/analytics/PT-devteev-Advanced-SQL-Injection.pdf
https://proglib.io/p/sql-for-20-minutes
https://portswigger.net/web-security/sql-injection/cheat-sheet


PT onelove
https://positive-technologies.notion.site/2024-1-PT-START-Basic-1-7f1896c562d44da9bfa19f8a48deb6e2
https://www.notion.so/Linux_Basic-_-_-PT-START-2024-1-3044091292244096838c86476d0eb7ec (my)

OSPF/RIP
https://irinashpakk.gitbook.io/ospf
https://sadykov.notion.site/7-OSI-L3-RIP-OSPF-ba1f93d1f9b64ef3a1298e5ad55ad539
https://poligon218.ru/?s=ospf
https://storm39.wordpress.com/%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5-%D0%BF%D0%BE%D1%81%D0%BE%D0%B1%D0%B8%D0%B5-%D0%BC%D0%BE%D0%B4%D1%83%D0%BB%D1%8C-%D0%B0/

Pentest
https://academy.hackthebox.com/preview/certifications/htb-certified-penetration-testing-specialist

VPN
https://poligon218.ru/2022/07/02/%D0%BD%D0%B0%D0%B7%D0%BD%D0%B0%D1%87%D0%B5%D0%BD%D0%B8%D0%B5-%D1%82%D1%83%D0%BD%D0%BD%D0%B5%D0%BB%D0%B5%D0%B9-%D0%B7%D0%B0%D1%89%D0%B8%D1%82%D0%B0-%D1%82%D1%83%D0%BD%D0%BD%D0%B5%D0%BB%D0%B5%D0%B9/?ysclid=lxbnedfm9n665155889
https://www.wireguard.com/

CHEETER


SCANNING
https://nmap.org/man/ru/index.html

---------------------------------------------------------------------------------------------------------------------
┌──(user㉿kali)-[~]
└─$ sudo nmap -sU -pU:123 -Pn -n --script=ntp-monlist 10.129.173.157
Host discovery disabled (-Pn). All addresses will be marked 'up' and scan times will be slower.
Starting Nmap 7.91 ( https://nmap.org ) at 2021-07-10 01:49 +03
Nmap scan report for 10.129.173.157
Host is up (0.22s latency).

PORT    STATE SERVICE
123/udp open  ntp
| ntp-monlist:
|   Target is synchronised with 34.127.56.0 (reference clock)
|   Alternative Target Interfaces:
|       10.0.4.20
|   Private Servers (0)
|   Public Servers (0)
|   Private Peers (0)
|   Public Peers (0)
|   Private Clients (2)
|       10.0.8.35     169.254.138.55
|   Public Clients (597)
|       10.129.173.123     10.129.173.55    10.129.173.63   10.129.173.76
|       ...
|
|   Other Associations (1)
|_      127.0.0.1 seen 1853555 times. last tx was unicast v2 mode 7
Nmap done: 1 IP address (1 host up) scanned in 6.64 seconds
----------------------------------------------------------------------------------------------------------------------

https://github.com/Samsar4/Ethical-Hacking-Labs/blob/master/3-Enumeration/3-Enum4linux-Win-and-Samba-Enumeration.md

----------------------------------------------------------------------------------------------------------------------
sudo enum4linux 10.129.173.157    

Starting enum4linux v0.8.9 ( http://labs.portcullis.co.uk/application/enum4linux/ ) on Mon Jul 10 01:39:58 2021

 ========================== 
|    Target Information    |
 ========================== 
Target ........... 10.129.173.157
RID Range ........ 500-550,1000-1050
Username ......... ''
Password ......... ''
Known Usernames .. administrator, guest, krbtgt, domain admins, root, bin, none

 ====================================================== 
|    Enumerating Workgroup/Domain on 10.129.173.157    |
 ====================================================== 
[E] Can not find workgroup/domain

 ============================================== 
|    Nbtstat Information for 10.129.173.157    |
 ============================================== 
Looking up status of 10.129.173.157
No reply from 10.129.173.157

 ======================================= 
|    Session Check on 10.129.173.157    |
 ======================================= 
[+] Server 10.129.173.157 allows sessions using username '', password ''
[+] Got domain/workgroup name: 

 ============================================= 
|    Getting domain SID for 10.129.173.157    |
 ============================================= 
Domain Name: domain.com
Domain Sid: S-1-5-21-3072663084-364016917-1341370565
[+] Host is part of a domain (not a workgroup)

 ======================================== 
|    OS information on 10.129.173.157    |
 ======================================== 
[+] Got OS info for 10.129.173.157 from smbclient: 
[+] Got OS info for 10.129.173.157 from srvinfo:
Could not initialise srvsvc. Error was NT_STATUS_ACCESS_DENIED

 =============================== 
|    Users on 10.129.173.157    |
 =============================== 
index: 0x2137 RID: 0x463 acb: 0x00020015 Account: $331000-VK4ADACQNUCA  Name: (null)  Desc: (null)
index: 0xfbc RID: 0x1f4 acb: 0x00020010 Account: Administrator  Name: Administrator  Desc: Built-in account for administering the computer/domain
index: 0x2369 RID: 0x47e acb: 0x00000210 Account: andy  Name: Andy Hislip  Desc: (null)
index: 0xfbe RID: 0x1f7 acb: 0x00000215 Account: DefaultAccount  Name: (null)  Desc: A user account managed by the system.
index: 0xfbd RID: 0x1f5 acb: 0x00000215 Account: Guest  Name: (null)  Desc: Built-in account for guest access to the computer/domain
index: 0x2352 RID: 0x478 acb: 0x00000210 Account: HealthMailbox0659cc1  Name: HealthMailbox-EXCH01-010  Desc: (null)
index: 0x234b RID: 0x471 acb: 0x00000210 Account: HealthMailbox670628e  Name: HealthMailbox-EXCH01-003  Desc: (null)
index: 0x234d RID: 0x473 acb: 0x00000210 Account: HealthMailbox6ded678  Name: HealthMailbox-EXCH01-005  Desc: (null)
index: 0x2351 RID: 0x477 acb: 0x00000210 Account: HealthMailbox7108a4e  Name: HealthMailbox-EXCH01-009  Desc: (null)
index: 0x234e RID: 0x474 acb: 0x00000210 Account: HealthMailbox83d6781  Name: HealthMailbox-EXCH01-006  Desc: (null)
index: 0x234c RID: 0x472 acb: 0x00000210 Account: HealthMailbox968e74d  Name: HealthMailbox-EXCH01-004  Desc: (null)
index: 0x2350 RID: 0x476 acb: 0x00000210 Account: HealthMailboxb01ac64  Name: HealthMailbox-EXCH01-008  Desc: (null)
index: 0x234a RID: 0x470 acb: 0x00000210 Account: HealthMailboxc0a90c9  Name: HealthMailbox-EXCH01-002  Desc: (null)
index: 0x2348 RID: 0x46e acb: 0x00000210 Account: HealthMailboxc3d7722  Name: HealthMailbox-EXCH01-Mailbox-Database-1118319013  Desc: (null)
index: 0x2349 RID: 0x46f acb: 0x00000210 Account: HealthMailboxfc9daad  Name: HealthMailbox-EXCH01-001  Desc: (null)
index: 0x234f RID: 0x475 acb: 0x00000210 Account: HealthMailboxfd87238  Name: HealthMailbox-EXCH01-007  Desc: (null)
index: 0xff4 RID: 0x1f6 acb: 0x00020011 Account: krbtgt  Name: (null)  Desc: Key Distribution Center Service Account
index: 0x2360 RID: 0x47a acb: 0x00000210 Account: lucinda  Name: Lucinda Berger  Desc: (null)
index: 0x236a RID: 0x47f acb: 0x00000210 Account: mark  Name: Mark Brandt  Desc: (null)
index: 0x236b RID: 0x480 acb: 0x00000210 Account: santi  Name: Santi Rodriguez  Desc: (null)
----------------------------------------------------------------------------------------------------------------------

DOCKER
----------------------------------------------------------------------------------------------------------------------
$ docker pull cr.yandex/mirror/alpine
Using default tag: latest
latest: Pulling from mirror/alpine
59bf1c3509f3: Pull complete 
Digest: sha256:e7d88de73db3d3fd9b2d63aa7f447a10fd0220b7cbf39803c803f2af9ba256b3
Status: Downloaded newer image for cr.yandex/mirror/alpine:latest
cr.yandex/mirror/alpine:latest
----------------------------------------------------------------------------------------------------------------------
https://huecker.io/


