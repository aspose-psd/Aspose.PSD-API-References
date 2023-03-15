---
title: Enum CompressionMethod
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.CompressionMethod Sıralama. Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar.
type: docs
weight: 1620
url: /tr/net/aspose.psd.fileformats.psd/compressionmethod/
---
## CompressionMethod enumeration

Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar.

```csharp
public enum CompressionMethod : short
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Raw | `0` | Sıkıştırma yok. Görüntü verileri, RGBA düzlemsel düzeninde ham bayt olarak depolanır. Bu, önce tüm R verilerinin yazıldığı, ardından tüm G verilerinin, ardından tüm B ve son olarak tüm A verilerinin yazıldığı anlamına gelir. |
| RLE | `1` | RLE sıkıştırılmış görüntü verileri, iki baytlık bir değer olarak depolanan her sayısıyla tüm tarama satırları (satırlar * kanallar) için bayt sayımlarıyla başlar. RLE sıkıştırılmış verileri, her bir tarama satırı ayrı ayrı sıkıştırılarak takip eder. RLE sıkıştırması, Macintosh ROM rutini PackBits ve TIFF standardı tarafından kullanılan sıkıştırma algoritmasının aynısıdır. |
| ZipWithoutPrediction | `2` | Tahminsiz ZIP. |
| ZipWithPrediction | `3` | Tahminli ZIP. |

### Ayrıca bakınız

* ad alanı [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* toplantı [Aspose.PSD](../../)


