# mvps
VPS Wordpress Management, dengan mesin EasyEngine dan WP-CLI

Ini kerjaan iseng, lalu seneng, meski lama-lama puyeng, karna harus testing, baca dokumentasi, karena memang bukan expert. (curcol)

Lebay ih deskripsinyah yah, cuma scripting biasa aja, karna kerjaannya repetitif, kalau manual bikin repot, jadi dibikin aja script bash biasa biar memudahkan.

Karena ini maenannya dengan EasyEngine, so kalau mau pake script ini ya ngikutin requirement si EasyEngine lah.

Supported distributions

    Ubuntu 12.04 and 14.04
    Debian 7 and 8

Port requirements

    22/TCP (Inbound/Outbound) : Standard SSH port
    80/TCP (Inbound/Outbound) : Standard HTTP port
    443/TCP(Inbound/Outbound) : Standard HTTPS port
    22222/TCP (Inboud) : To access EasyEngine admin tools
    11371/TCP (Outbound) : To connect to GPG Key Server

### Cara Pake

Login root, tinggal eksekusi saja perintah dibawah yah ...

```sh
wget https://raw.githubusercontent.com/idL3akZ/mvps/master/mvps && chmod +x mvps
mv mvps /usr/local/bin
```

Kalo ada error, soal sertificate yg ngg valid, pake yg ini

```sh
wget --no-check-certificate https://raw.githubusercontent.com/idL3akZ/mvps/master/mvps && chmod +x mvps
mv mvps /usr/local/bin
```

Selanjutnya tinggal run dengan perintah, dan tggal jalankan saja optionnya .. :D
```sh
mvps
```

### ScreenCrot

![Task Option](http://i.imgur.com/rR9hM5q.png)

### Version
3.0

### Change Log

![Chaneg LOg](http://i.imgur.com/SHRawqv.png)

Udah ah itu saja, ngg jelas kan ? makanya ngg usah dibaca ... :D
