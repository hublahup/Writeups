## Scan Surprise

![Verify](../../AssetImage/Picture6.png)

I've gotten bored of handing out flags as text. Wouldn't it be cool if they were an image instead?

Hints
1. QR codes are a way of encoding data. While they're most known for storing URLs, they can store other things too.
2. Mobile phones have included native QR code scanners in their cameras since version 8 (Oreo) and iOS 11
3. If you don't have access to a phone, you can also use zbar-tools to convert an image to text

Untuk tantangan ini kita diminta untuk melihat isi dari QRcode tersebut

![Verify](../../AssetImage/Picture7.png)

Untuk menyelesaikannya, kita bisa menggunakan tools Zbar untuk mengkonversi gambar ke text

```
zbarimg flag.png
```

![Verify](../../AssetImage/Picture8.png)
