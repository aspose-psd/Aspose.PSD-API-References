---
title: "CompressionMethod Sıralaması"
type: docs
weight: 2410
url: /tr/python-net/aspose.psd.fileformats.psd/compressionmethod/
---

Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.CompressionMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| RAW | Sıkıştırma yok. Görüntü verileri RGBA düzlemsel sırada ham baytlar olarak depolanır.<br/>            Bu, önce tüm R verisinin, ardından tüm G verisinin, sonra tüm B ve sonunda tüm A verisinin yazıldığı anlamına gelir. |
| RLE | RLE sıkıştırmalı görüntü verileri, tüm tarama satırları (satırlar * kanallar) için bayt sayılarıyla başlar ve her<br/>            sayı iki baytlık bir değer olarak depolanır. RLE sıkıştırmalı veri ardından gelir ve her tarama satırı ayrı ayrı sıkıştırılır.<br/>            RLE sıkıştırması, Macintosh ROM rutin PackBits ve TIFF standardı tarafından kullanılan aynı sıkıştırma algoritmasıdır. |
| ZIP_WITHOUT_PREDICTION | Tahmin olmadan ZIP. |
| ZIP_WITH_PREDICTION | Tahminli ZIP. |
