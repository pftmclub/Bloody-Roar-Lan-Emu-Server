# Bloody-Roar-Lan-Emu-Server
Lanemu P2P VPN for Bloody Roar

[![en](https://img.shields.io/badge/lang-en-purple.svg)](README.en.md)
[![vn](https://img.shields.io/badge/lang-vn-green.svg)](README.md)

How to use :

Step 1: Download the archive from Release pages:


[https://github.com/pftmclub/Bloody-Roar-Lan-Emu-Server/releases/download/1.0/BloodyRoar_LanEmuVpn.7z](https://github.com/pftmclub/Bloody-Roar-Lan-Emu-Server/releases/download/1.0/BloodyRoar_LanEmuVpn.7z)

<br>


<img width="969" height="571" alt="001" src="https://github.com/user-attachments/assets/5f2dae8a-6f5d-4585-a257-f0399c4b1190" /> <br>

Extract the archive, go to ``driver`` , right click ``tap-windows-9.24.7-I601-Win10.exe`` and choose ``Run as administrator`` : <br>


<img width="969" height="571" alt="002" src="https://github.com/user-attachments/assets/28649849-c49d-4828-b56e-55349cdab4f5" /><br>

When driver installation is finished , right click  ``set_use_tapv9`` and choose ``Merge`` <br>

<img width="969" height="571" alt="002a" src="https://github.com/user-attachments/assets/6a0c38ca-1a05-4841-a10d-9782b74d6ff2" /><br>

After registry files is done merge,  go to ``build`` folder , right click ``Lanemu.exe`` and choose ``Properties`` : <br>

<img width="969" height="571" alt="003" src="https://github.com/user-attachments/assets/50e88ac2-eb3a-4d67-9bab-48db230a3984" /><br>

Switch to ``Compatibility`` tab , check ``Run this program as an Administartor`` and choose "OK" : <br>

<img width="363" height="525" alt="003a" src="https://github.com/user-attachments/assets/51664763-256b-4977-9d32-9e52b73bdcb5" /><br>

Run ``Lanemu.exe`` , you'll see a pop up with a message ``Do you want to join 'Default network'?``, choose ``No`` : <br>

<img width="286" height="128" alt="004" src="https://github.com/user-attachments/assets/b58b9200-0757-491d-b45e-54102991c901" /><br>

Click the ``Option`` icon : <br>

<img width="260" height="541" alt="005" src="https://github.com/user-attachments/assets/7ce8bfca-3604-41f4-94fa-60c466cf5380" /><br>

Type your username on  ``Your Name `` section, ``Listen on Port`` = 6666,  then choose "OK": <br>

<img width="504" height="450" alt="006" src="https://github.com/user-attachments/assets/62ab7189-c252-485c-a840-827045518448" /><br>

Click on  ``Accept Invitation`` icon : <br>

<img width="260" height="541" alt="007" src="https://github.com/user-attachments/assets/40ecc1dc-6474-4b8f-a8eb-26a55996c9a5" /><br>

Press ``Load from file``  button: <br>

<img width="462" height="309" alt="008" src="https://github.com/user-attachments/assets/67799afc-57c5-4bcb-adfd-ac7db707f9bc" /><br>

Browse the text files called ``BloodyRoar.txt`` then "OK": <br>

Or pase those code into the clipboard : <br> 
```css

#==============================
#Sun Jul 27 21:51:45 GMT+07:00 2025
network.bootstrap.DHT=yes
network.bootstrap.connectTo.0=222.255.238.138\:6666
network.bootstrap.tracker.0=https\://tracker.yemekyedim.com\:443/announce
network.ip.network=10.6.0.0
network.ip.subnet=255.255.0.0
network.name=Bloody Roar Online Viet Nam
network.publicKey.0=MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAx5lT3Qu4qAzAUkzVrZU+qvTyclrC9l2y
network.publicKey.1=MFvgga6a2PmpE6uxVpDM1KYHW8pBbrQXqtcElpZ9iHwH+lWeQKokXgP0li59M36aLFqum/c8yp6n
network.publicKey.2=QsOKBR9k1/If2bZJydm53vhv4m/In/KczIMoyE6OwrIBevFcMYApT7Bn7OtuDvrkmPJzPULb9lGR
network.publicKey.3=Hla3ItoLPWtIIjhZDm/gPGvdrQiQiqYM5QyyraYj11jl5FODdMaCsDBnHAvcvs7tEiT49OcwkIZb
network.publicKey.4=VH+bK5nlfIbGyFutV3ePC4pvoz63RqPsM7MKYt6E90bhPnO+1vCRx4l6AlTZ3fL5+mU/jXdiYhik
network.publicKey.5=5m0GkwIDAQAB
network.signature.0=oV6K72STUg0WWp224JJ0FgdTK2bqFrIQHYgYwIwf8+UGSdv7axCX3zrXyQGbQkDaGKd6U2EmEkuX
network.signature.1=kE8YClQ+6o1QfvRiQW5K4lcJCMaU3WwjVjyf6KAhGKJwd7oQepzgFdM6QlWa90NrAtXdJGezcgkt
network.signature.2=Vy6OsFrtZg72HGnA1voW1cnIRYkynneNAQwTRXxbdsqO1gZ4pcyvgsKL5W9/fIZHcbWZVY0/nVBJ
network.signature.3=4/TNsiIGly3o5AmbpXsbTCSNTgUkjNHAbo5fQNOtBT+q9n+hB7L745B77RwWE460JsmIOB6HFDw1
network.signature.4=aWpIyw2TcxzVR0DywL1WCGeDng5bREuYHJQLRw\=\=
secret.network.privateKey.0=MIIEvwIBADANBgkqhkiG9w0BAQEFAASCBKkwggSlAgEAAoIBAQDHmVPdC7ioDMBSTNWtlT6q9PJy
secret.network.privateKey.1=WsL2XbIwW+CBrprY+akTq7FWkMzUpgdbykFutBeq1wSWln2IfAf6VZ5AqiReA/SWLn0zfposWq6b
secret.network.privateKey.2=9zzKnqdCw4oFH2TX8h/ZtknJ2bne+G/ib8if8pzMgyjITo7CsgF68VwxgClPsGfs624O+uSY8nM9
secret.network.privateKey.3=Qtv2UZEeVrci2gs9a0giOFkOb+A8a92tCJCKpgzlDLKtpiPXWOXkU4N0xoKwMGccC9y+zu0SJPj0
secret.network.privateKey.4=5zCQhltUf5srmeV8hsbIW61Xd48Lim+jPrdGo+wzswpi3oT3RuE+c77W8JHHiXoCVNnd8vn6ZT+N
secret.network.privateKey.5=d2JiGKTmbQaTAgMBAAECggEAMFF8zMD+pafYktPI0mmTrxz26BnyomNSNIS5V4tmLupZNMrWdkc9
secret.network.privateKey.6=XqkGlQDkUCFGrXO5x56MqxKjd8VsNuk5Po0kk4qTgni+Z8hYBqeWTtKTWQUvD0hnSCNz9Gc9e6C6
secret.network.privateKey.7=bzCjHSTEY3v+2z9RCxSBWL5wv0tYbx9AYOsqbV8c2IEUR6NTPuKKDEf1xDJQKt+9RDpvBU9gGpN4
secret.network.privateKey.8=n+rCmtNEObGyfOu+LfFn5TWyFo8FnoKr6vJ1Jd1XKWm6c9IhqQNyUBKf2HbMs1bkXUR1cQB409q8
secret.network.privateKey.9=R0/OjCqn+C2dBZ//SgvmUfPZFJztJRVDAEecIzFAxFa9xXynq4tN3mdsud7ooQKBgQDyrCRVUCvv
secret.network.privateKey.a=VKB0exJxEFDXmAMVdzVD9QsnGwNUcHidKvgtIVUlWunFHKlQoCnjoVvmyGPorJ2ZyoMKljWF8/0n
secret.network.privateKey.b=QD/EHaT8N/JRdQyCphU998bjwL0f1FFwUUQkW9cz4W12iqhuGeqXiTjD4QvJVQYlthdFAWaqA5LM
secret.network.privateKey.c=bN7p1GEV0QKBgQDSj5fN87V2jNgD7khJJsGMAhkP7leABKIRzvqLLfowtTfZ8g5pS9YT2Priu1eo
secret.network.privateKey.d=avZjub18WTgwWnClICjeueW05aIJGg6DGTnjtPnwp3bcxYhLWIxyWzHzT7YGbnUFDsZtQkJDb9Ow
secret.network.privateKey.e=uAhSg754VS5/I47M3di56AP2w2yz5robIwKBgQCjfbhIxeejqVckwpnNFJnydhZ1ysdXDmtCIF/g
secret.network.privateKey.f=7plEAeQLu646qYJfawzjJdSy6E4bMJym8EyJhTc91a8fnR7L5+xN+07hIeweVwZjqvMauakEXiDM
secret.network.privateKey.g=peVsD0QiXsGg0VpHB+mrq8gx6aAVz7N6I88tbv1EX0pEdn3bPen8jToPUQKBgQC1kJyWO1B+qXSb
secret.network.privateKey.h=7xzl90VuNWDnG97XxSb7tD7XRQ44cgt3JALJSVuQQcoVOPadg55y3/dFAqoxB8ual+CmLialll3i
secret.network.privateKey.i=+1UINvh0IdpkagNU3ABq+DAja//mjxWm9hhyBAuWq0v4WrVv7UE/5dqYaNtvRnocri/0Ht1MK7fQ
secret.network.privateKey.j=aWSRgQKBgQCXHFLV9ZangHor3AxC0ZCK4e+EIYZA7Uewlt6yG63+LkPdpr7UnjkgL14vdjhz2U7B
secret.network.privateKey.k=OIptvhaWFtDZsr3ct9fsXYSsDnY4F2JRZ31L9/FWU47mWvKg0BKFRiI9CFoV2EAhsX3Mm5/XK+lE
secret.network.privateKey.l=jif5xW9rSXa0PnEfhIqlvdxHcuWbdw\=\=
#==============================
```

<img width="599" height="379" alt="009" src="https://github.com/user-attachments/assets/96fa36e7-210d-40ce-a28e-c97e157e8cdd" /> <br>

<img width="462" height="309" alt="010" src="https://github.com/user-attachments/assets/ffdc0d44-1aeb-49b0-9bad-c31e88227610" /><br>

The server name "Bloody Roar Viet Nam" will visiable below, Right click the user and click ```Copy VPN IP address``` , paste those IP into command prompt and ping those IP<br>
<img width="260" height="541" alt="011" src="https://github.com/user-attachments/assets/94ce7f14-321e-44c0-a9ae-cb5e15c2b49e" /><br>



<img width="825" height="835" alt="012" src="https://github.com/user-attachments/assets/28d01a74-0499-4d99-a6ca-3ed74189068b" /><br>

This tutorial is done, thanks for reading !












