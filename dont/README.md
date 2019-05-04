![](https://i.imgur.com/Ltha91k.jpg)

Ta có một tấm ảnh như vậy, thử `strings` xem thì có rất nhiều file ở trong

![](https://i.imgur.com/9bP8KJ5.png)

Dùng lệnh `binwalk -e dont.jpg` để trích xuất cái file bên trong thì có được rất nhiều thư mục.

![](https://i.imgur.com/4oveAO3.png)
Hầu hết các thư mục đều trống, dò theo `Size` thì thấy có một thư mục có `Size` là `78 bytes (78 bytes)`, dò theo đường dẫn `\_dont.jpg-0.extracted\allmn\my cpp - Copy (11)\try hard - Copy (2)\try hard - Copy (22)`
Ta có được file `wow.txt`.
ta được `flag is: NYYZA{J3_Y0I3_Z0AT0Y1N_2UAQ8W}` -> Rot13


#### Flag: `ROT-13: ALLMN{W3_L0V3_M0NG0L1A_2HND8J}`


