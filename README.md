### Bloody-Roar-Lan-Emu-Server
Lanemu P2P VPN for Bloody Roar

[![en](https://img.shields.io/badge/lang-en-purple.svg)](#english-tutorial)
[![vn](https://img.shields.io/badge/lang-vn-green.svg)](#h%C6%B0%E1%BB%9Bng-d%E1%BA%ABn-ti%E1%BA%BFng-vi%E1%BB%87t)


## Hướng dẫn tiếng Việt

Hướng dẫn sử dụng :

Bước 1: Đầu tiên tải file từ trang release về:


[https://github.com/pftmclub/Bloody-Roar-Lan-Emu-Server/releases/download/1.0/BloodyRoar_LanEmuVpn.7z](https://github.com/pftmclub/Bloody-Roar-Lan-Emu-Server/releases/download/1.0/BloodyRoar_LanEmuVpn.7z)

<br>


<img width="969" height="571" alt="001" src="https://github.com/user-attachments/assets/5f2dae8a-6f5d-4585-a257-f0399c4b1190" /> <br>

Sau đó tải về giải nén ra, truy cập vào thư mục ``driver`` , chuột phải vào ``tap-windows-9.24.7-I601-Win10.exe`` và chọn ``Run as administrator`` : <br>


<img width="969" height="571" alt="002" src="https://github.com/user-attachments/assets/28649849-c49d-4828-b56e-55349cdab4f5" /><br>

Sau khi cài đặt xong driver , chuột phải vào ``set_use_tapv9`` và chọn ``Merge`` <br>

<img width="969" height="571" alt="002a" src="https://github.com/user-attachments/assets/6a0c38ca-1a05-4841-a10d-9782b74d6ff2" /><br>

Sau đó truy cập vào thư mục ``hyper-nat`` , chuột phải vào ``hyper-nat.exe`` và chọn ``Run as administartor`` : <br>

<img width="969" height="571" alt="002c" src="https://github.com/user-attachments/assets/e33159b7-755b-46fd-95f8-36c7cee91750" /> <br>

Nếu hiện connection  open là coi như thành công , nếu ko hiện thì cửa sổ sẽ tự động đóng  :<br>

<img width="979" height="512" alt="002d" src="https://github.com/user-attachments/assets/74897a09-5d61-4543-bf89-05316f1cfee6" /><br>


Sau đó truy cập vào thư mục ``build``, chuột phải vào ``Lanemu.exe`` và chọn ``Properties`` : <br>

<img width="969" height="571" alt="003" src="https://github.com/user-attachments/assets/50e88ac2-eb3a-4d67-9bab-48db230a3984" /><br>

Chọn thẻ ``Compatibility`` , tích vào ô ``Run this program as an Administartor`` rồi chọn "OK" : <br>

<img width="363" height="525" alt="003a" src="https://github.com/user-attachments/assets/51664763-256b-4977-9d32-9e52b73bdcb5" /><br>

Sau đó chạy file ``Lanemu.exe`` , sẽ hiện thông báo có muốn join Default network, chọn ``No`` : <br>

<img width="286" height="128" alt="004" src="https://github.com/user-attachments/assets/b58b9200-0757-491d-b45e-54102991c901" /><br>

Sau đó click vào biểu tượng ``Option`` : <br>

<img width="260" height="541" alt="005" src="https://github.com/user-attachments/assets/7ce8bfca-3604-41f4-94fa-60c466cf5380" /><br>

Phần ``Your Name `` điền tên tùy ý, phần ``Listen on Port`` điền 6666, sau đó nhấn "OK": <br>

<img width="504" height="450" alt="006" src="https://github.com/user-attachments/assets/62ab7189-c252-485c-a840-827045518448" /><br>

Bấm vào biểu tượng ``Accept Invitation`` : <br>

<img width="260" height="541" alt="007" src="https://github.com/user-attachments/assets/40ecc1dc-6474-4b8f-a8eb-26a55996c9a5" /><br>

Ấn vào nút ``Load from file`` : <br>

<img width="462" height="309" alt="008" src="https://github.com/user-attachments/assets/67799afc-57c5-4bcb-adfd-ac7db707f9bc" /><br>

Chọn file ``BloodyRoar.txt`` rồi ấn "OK": <br>

Hoặc chép dòng mã sau vào khoảng trống : <br> 
```css

#==============================
#Sun Aug 03 15:41:22 GMT+07:00 2025
network.bootstrap.connectTo.0=222.255.238.138\:6666
network.bootstrap.connectTo.1=127.0.0.1\:6666
network.ip.network=10.6.0.0
network.ip.subnet=255.255.0.0
network.name=Bloody Roar Online Network Viet Nam
network.publicKey.0=MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEArSfOuveVIZdnlZ/pwepCw75wNwqdQ4w6
network.publicKey.1=owquVzjkNYmKOTnOZaF5sCj3gpLTSLV/6biiaG3T/OESIuYfmtL8Wntboj9PVgCdStyO54EkHzdD
network.publicKey.2=nLr3b+515g/37Ni0KUYZ/mF/Lkghq5kRWPizzY5jknYR3nQbuKKHsCtF2RkvSj6JHAEfmrt7mqKy
network.publicKey.3=RIArX+ywHZr2KsQ8DMWYruR8h7eL8iVW1Mk2bfdaB4k2bV7iqfiPTE6orf/wa7Yllhh4FhwOwq67
network.publicKey.4=Dr1lN4T1LbmWua9oFEKE0TdZPtDooCGXy8ku99mfyYb6Q5ZtuUrtt7pxZwcRNTSGO5Wh5+X+6/63
network.publicKey.5=JY5WHwIDAQAB
network.signature.0=izD/yRhFo8elsePCTBADu17dOR0JCB9DaQ7fCj8N2yu6u+LUAeeRKsc4rfYj07SO+i7340XCJuMF
network.signature.1=tW/7JPCaOKCKzCKutIVclQfGd19vFyrS0SKUmlkWBkjIoi44y6c2YE0vTQo8DoNwZl/wK5FwjV/D
network.signature.2=FjlVvv56Gxu3PjwaXs3jlNWJsDCWguDSvgCa24vvb8z/pGAXzUsm79N5tjSmt7WVgK8mN40MOSYG
network.signature.3=8lep/JE8CwwxLql07WqM0j7cl9xe/WwwpDJT1bSo7vJ0NN+AUR6wqvazp1TEfu+PomBZn9yxn4Iq
network.signature.4=TIVh63CGIWaMlzvaiEbqlmpPzICh8/nNtm3DXg\=\=
secret.network.privateKey.0=MIIEvgIBADANBgkqhkiG9w0BAQEFAASCBKgwggSkAgEAAoIBAQCtJ86695Uhl2eVn+nB6kLDvnA3
secret.network.privateKey.1=Cp1DjDqjCq5XOOQ1iYo5Oc5loXmwKPeCktNItX/puKJobdP84RIi5h+a0vxae1uiP09WAJ1K3I7n
secret.network.privateKey.2=gSQfN0Ocuvdv7nXmD/fs2LQpRhn+YX8uSCGrmRFY+LPNjmOSdhHedBu4ooewK0XZGS9KPokcAR+a
secret.network.privateKey.3=u3uaorJEgCtf7LAdmvYqxDwMxZiu5HyHt4vyJVbUyTZt91oHiTZtXuKp+I9MTqit//BrtiWWGHgW
secret.network.privateKey.4=HA7CrrsOvWU3hPUtuZa5r2gUQoTRN1k+0OigIZfLyS732Z/JhvpDlm25Su23unFnBxE1NIY7laHn
secret.network.privateKey.5=5f7r/rcljlYfAgMBAAECggEABAXJOTG4PrQIPYMeCJm7HFYHwFeYSLHwyMneO/t/3biIxASSRW0n
secret.network.privateKey.6=aQ7ClT949hb1VkYqS7fFdXn7FGF5OX0OTMHR4qaK3sob3VnbXghzgOAlS3ZSekC1b3dOgKuWH+FX
secret.network.privateKey.7=iD/Wlwoo8hYXv5PjhXJ54LSqfJsA69ymv1J6CG2b2iMo6sxEBEBDS0RM5xyBHQ+NWpw1uwuJYao8
secret.network.privateKey.8=BhuQKCC6h2F/BcQg5DX4t1P2Zp1PpjB1KMUggxbf4sdoX/5q3319R3/mhICQG0roik3Vmbur3j3X
secret.network.privateKey.9=AZvZmsyafwzSjDW0TWPRJZxqajz5/QBUu1sUEGzz/IJa7kx6NHtGaJ1QgGbAyQKBgQDvA/C3BzUE
secret.network.privateKey.a=c96Js+dPgZhBYpTuI7IEvcGvU/DXDxXqMdFj+T9X+jc9pIRrcoj4kmos8J4HtADMWwCwpalzBGoZ
secret.network.privateKey.b=vUjYUai7dWoP6fBDRl6sF5fFyVKihu8DAni74ghduiEOF8iuo5Nt9qRYZF3Cp36MWl6h5v4BItsd
secret.network.privateKey.c=jFvsVFg8VwKBgQC5dcYerIgjqaae3ow10JkiSBYIJyRNzl2ANRrHkot+lzZfGTjhgXos0IjqfnUE
secret.network.privateKey.d=07EhqxcQwZptLqxZ4m2ycQ5kKpydJKTprWu3k+2pRuEnRx65aBiibolRtPpkhmvm//3sKwyP8y1q
secret.network.privateKey.e=30QC7KhccNa4kMtkmUt1OiiTio8vFEIXeQKBgQCay2Z+YwCHHbOmYwkPiNLepcXmZN/KCksCDc8Q
secret.network.privateKey.f=uQhsYE9H/Ah2JerY1U+ddtQWiFyTNlJiksVhlB5iSSfxAY7llJ002833ehdyrwOXzl9J/Q2iXrxR
secret.network.privateKey.g=3im1PUiMBdt9OCpoQicKU44LzYyqYnYGtwtSQsS+/ibK/ZQDEwAFkqqCiQKBgQCV5ygYKwRvLvVK
secret.network.privateKey.h=fD+AT/c2ymVkeZ7SdPcGZeYbYcv2qmp8O3rKa0lBZ90DDOuw1xrZR90A4jvb/Fm63VYlYVRsijTE
secret.network.privateKey.i=n5XcexwR6jOzG2NpyAaBfi5LPGUp8cph7nTQ5iFr/u/MepY/R+9FHdyHu30S+ZYs3esr+bJKbziE
secret.network.privateKey.j=qS8yoQKBgDeum5/8QRTOM38nBLxrsHG/dOJkyGvZht3dlntekjxw/v4DTs3LCn9/hKo++qYtAtB9
secret.network.privateKey.k=rVBvnX9DLuitxOsQNq8hKbOyVzSA6djeI2aLFUW082PaO0OTl/W3LyFRFuvajfcS4Md2zSlQMMim
secret.network.privateKey.l=gifJFxQAIJ7wqsTCtVsnDTbAZP44
#==============================

```

<img width="599" height="379" alt="009" src="https://github.com/user-attachments/assets/96fa36e7-210d-40ce-a28e-c97e157e8cdd" /> <br>

<img width="462" height="309" alt="010" src="https://github.com/user-attachments/assets/ffdc0d44-1aeb-49b0-9bad-c31e88227610" /><br>

Tên server "Bloody Roar Viet Nam" sẽ hiện ra, bạn chuột phải vào tên rồi chép IP vào command prompt , ping thử và xem kết quả<br>
<img width="260" height="541" alt="011" src="https://github.com/user-attachments/assets/94ce7f14-321e-44c0-a9ae-cb5e15c2b49e" /><br>



<img width="825" height="835" alt="012" src="https://github.com/user-attachments/assets/28d01a74-0499-4d99-a6ca-3ed74189068b" /><br>

Như vậy là bạn đã thành công trong việc kết nối tới server Bloody Roar, chúc các bạn thành công


[Quay lại đầu trang](#bloody-roar-lan-emu-server)

## English Tutorial
How to use :

Step 1: Download the archive from Release pages:


[https://github.com/pftmclub/Bloody-Roar-Lan-Emu-Server/releases/download/1.0/BloodyRoar_LanEmuVpn.7z](https://github.com/pftmclub/Bloody-Roar-Lan-Emu-Server/releases/download/1.0/BloodyRoar_LanEmuVpn.7z)

<br>


<img width="969" height="571" alt="001" src="https://github.com/user-attachments/assets/5f2dae8a-6f5d-4585-a257-f0399c4b1190" /> <br>

Extract the archive, go to ``driver`` , right click ``tap-windows-9.24.7-I601-Win10.exe`` and choose ``Run as administrator`` : <br>


<img width="969" height="571" alt="002" src="https://github.com/user-attachments/assets/28649849-c49d-4828-b56e-55349cdab4f5" /><br>

When driver installation is finished , right click  ``set_use_tapv9`` and choose ``Merge`` <br>

<img width="969" height="571" alt="002a" src="https://github.com/user-attachments/assets/6a0c38ca-1a05-4841-a10d-9782b74d6ff2" /><br>

After registry files is done merg , go to ``hyper-nat`` folder , right click ``hyper-nat.exe`` and choose ``Run as administartor`` : <br>

<img width="969" height="571" alt="002c" src="https://github.com/user-attachments/assets/e33159b7-755b-46fd-95f8-36c7cee91750" /> <br>

Wait until hyper-nat establishes connection to the server <br>
The window closes if connection fails, you might have to retry several times  :<br>

<img width="979" height="512" alt="002d" src="https://github.com/user-attachments/assets/74897a09-5d61-4543-bf89-05316f1cfee6" /><br>

Go to ``build`` folder , right click ``Lanemu.exe`` and choose ``Properties`` : <br>

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
#Sun Aug 03 15:41:22 GMT+07:00 2025
network.bootstrap.connectTo.0=222.255.238.138\:6666
network.bootstrap.connectTo.1=127.0.0.1\:6666
network.ip.network=10.6.0.0
network.ip.subnet=255.255.0.0
network.name=Bloody Roar Online Network Viet Nam
network.publicKey.0=MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEArSfOuveVIZdnlZ/pwepCw75wNwqdQ4w6
network.publicKey.1=owquVzjkNYmKOTnOZaF5sCj3gpLTSLV/6biiaG3T/OESIuYfmtL8Wntboj9PVgCdStyO54EkHzdD
network.publicKey.2=nLr3b+515g/37Ni0KUYZ/mF/Lkghq5kRWPizzY5jknYR3nQbuKKHsCtF2RkvSj6JHAEfmrt7mqKy
network.publicKey.3=RIArX+ywHZr2KsQ8DMWYruR8h7eL8iVW1Mk2bfdaB4k2bV7iqfiPTE6orf/wa7Yllhh4FhwOwq67
network.publicKey.4=Dr1lN4T1LbmWua9oFEKE0TdZPtDooCGXy8ku99mfyYb6Q5ZtuUrtt7pxZwcRNTSGO5Wh5+X+6/63
network.publicKey.5=JY5WHwIDAQAB
network.signature.0=izD/yRhFo8elsePCTBADu17dOR0JCB9DaQ7fCj8N2yu6u+LUAeeRKsc4rfYj07SO+i7340XCJuMF
network.signature.1=tW/7JPCaOKCKzCKutIVclQfGd19vFyrS0SKUmlkWBkjIoi44y6c2YE0vTQo8DoNwZl/wK5FwjV/D
network.signature.2=FjlVvv56Gxu3PjwaXs3jlNWJsDCWguDSvgCa24vvb8z/pGAXzUsm79N5tjSmt7WVgK8mN40MOSYG
network.signature.3=8lep/JE8CwwxLql07WqM0j7cl9xe/WwwpDJT1bSo7vJ0NN+AUR6wqvazp1TEfu+PomBZn9yxn4Iq
network.signature.4=TIVh63CGIWaMlzvaiEbqlmpPzICh8/nNtm3DXg\=\=
secret.network.privateKey.0=MIIEvgIBADANBgkqhkiG9w0BAQEFAASCBKgwggSkAgEAAoIBAQCtJ86695Uhl2eVn+nB6kLDvnA3
secret.network.privateKey.1=Cp1DjDqjCq5XOOQ1iYo5Oc5loXmwKPeCktNItX/puKJobdP84RIi5h+a0vxae1uiP09WAJ1K3I7n
secret.network.privateKey.2=gSQfN0Ocuvdv7nXmD/fs2LQpRhn+YX8uSCGrmRFY+LPNjmOSdhHedBu4ooewK0XZGS9KPokcAR+a
secret.network.privateKey.3=u3uaorJEgCtf7LAdmvYqxDwMxZiu5HyHt4vyJVbUyTZt91oHiTZtXuKp+I9MTqit//BrtiWWGHgW
secret.network.privateKey.4=HA7CrrsOvWU3hPUtuZa5r2gUQoTRN1k+0OigIZfLyS732Z/JhvpDlm25Su23unFnBxE1NIY7laHn
secret.network.privateKey.5=5f7r/rcljlYfAgMBAAECggEABAXJOTG4PrQIPYMeCJm7HFYHwFeYSLHwyMneO/t/3biIxASSRW0n
secret.network.privateKey.6=aQ7ClT949hb1VkYqS7fFdXn7FGF5OX0OTMHR4qaK3sob3VnbXghzgOAlS3ZSekC1b3dOgKuWH+FX
secret.network.privateKey.7=iD/Wlwoo8hYXv5PjhXJ54LSqfJsA69ymv1J6CG2b2iMo6sxEBEBDS0RM5xyBHQ+NWpw1uwuJYao8
secret.network.privateKey.8=BhuQKCC6h2F/BcQg5DX4t1P2Zp1PpjB1KMUggxbf4sdoX/5q3319R3/mhICQG0roik3Vmbur3j3X
secret.network.privateKey.9=AZvZmsyafwzSjDW0TWPRJZxqajz5/QBUu1sUEGzz/IJa7kx6NHtGaJ1QgGbAyQKBgQDvA/C3BzUE
secret.network.privateKey.a=c96Js+dPgZhBYpTuI7IEvcGvU/DXDxXqMdFj+T9X+jc9pIRrcoj4kmos8J4HtADMWwCwpalzBGoZ
secret.network.privateKey.b=vUjYUai7dWoP6fBDRl6sF5fFyVKihu8DAni74ghduiEOF8iuo5Nt9qRYZF3Cp36MWl6h5v4BItsd
secret.network.privateKey.c=jFvsVFg8VwKBgQC5dcYerIgjqaae3ow10JkiSBYIJyRNzl2ANRrHkot+lzZfGTjhgXos0IjqfnUE
secret.network.privateKey.d=07EhqxcQwZptLqxZ4m2ycQ5kKpydJKTprWu3k+2pRuEnRx65aBiibolRtPpkhmvm//3sKwyP8y1q
secret.network.privateKey.e=30QC7KhccNa4kMtkmUt1OiiTio8vFEIXeQKBgQCay2Z+YwCHHbOmYwkPiNLepcXmZN/KCksCDc8Q
secret.network.privateKey.f=uQhsYE9H/Ah2JerY1U+ddtQWiFyTNlJiksVhlB5iSSfxAY7llJ002833ehdyrwOXzl9J/Q2iXrxR
secret.network.privateKey.g=3im1PUiMBdt9OCpoQicKU44LzYyqYnYGtwtSQsS+/ibK/ZQDEwAFkqqCiQKBgQCV5ygYKwRvLvVK
secret.network.privateKey.h=fD+AT/c2ymVkeZ7SdPcGZeYbYcv2qmp8O3rKa0lBZ90DDOuw1xrZR90A4jvb/Fm63VYlYVRsijTE
secret.network.privateKey.i=n5XcexwR6jOzG2NpyAaBfi5LPGUp8cph7nTQ5iFr/u/MepY/R+9FHdyHu30S+ZYs3esr+bJKbziE
secret.network.privateKey.j=qS8yoQKBgDeum5/8QRTOM38nBLxrsHG/dOJkyGvZht3dlntekjxw/v4DTs3LCn9/hKo++qYtAtB9
secret.network.privateKey.k=rVBvnX9DLuitxOsQNq8hKbOyVzSA6djeI2aLFUW082PaO0OTl/W3LyFRFuvajfcS4Md2zSlQMMim
secret.network.privateKey.l=gifJFxQAIJ7wqsTCtVsnDTbAZP44
#==============================

```

<img width="599" height="379" alt="009" src="https://github.com/user-attachments/assets/96fa36e7-210d-40ce-a28e-c97e157e8cdd" /> <br>

<img width="462" height="309" alt="010" src="https://github.com/user-attachments/assets/ffdc0d44-1aeb-49b0-9bad-c31e88227610" /><br>

The server name "Bloody Roar Viet Nam" will visiable below, Right click the user and click ```Copy VPN IP address``` , paste those IP into command prompt and ping those IP<br>
<img width="260" height="541" alt="011" src="https://github.com/user-attachments/assets/94ce7f14-321e-44c0-a9ae-cb5e15c2b49e" /><br>



<img width="825" height="835" alt="012" src="https://github.com/user-attachments/assets/28d01a74-0499-4d99-a6ca-3ed74189068b" /><br>

This tutorial is done, thanks for reading !

[Go back to top](#bloody-roar-lan-emu-server)










