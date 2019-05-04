# Admin panel
`                   Crypto (250 points)
Can you enter to my admin panel? I will give you my username and password. Just use the login file to log in.`

Đề cho 3 file là `login`, `shadow`, `shadow`

![](https://i.imgur.com/9OVWip3.png)

Dựa theo `https://null-byte.wonderhowto.com/how-to/crack-shadow-hashes-after-getting-root-linux-system-0186386/` ta có được

![](https://i.imgur.com/JZ8QkFm.png)

Sau đó dùng lệnh `john --wordlist=/mnt/e/tool/rockyou.txt hash.txt` để crack pass. Sau đó ta có được password là: `hellokitty`

Sau đó đăng nhập vào và có flag thôi.

![](https://i.imgur.com/4IbY7cc.png)

#### Flag: `ALLMN{G00DJ0B_Y0U_AR3_T00_G00D_SHD8WK}`
