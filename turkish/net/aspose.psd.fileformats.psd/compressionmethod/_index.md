---
title: "Enum CompressionMethod"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.CompressionMethod enum. Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar."
type: docs
weight: 1630
url: /tr/net/aspose.psd.fileformats.psd/compressionmethod/
---
{{< psd/tize >}}
## CompressionMethod enumeration

Görüntü verileri için kullanılan sıkıştırma yöntemini tanımlar.

```csharp
public enum CompressionMethod : short
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Raw | `0` | Sıkıştırma yok. Görüntü verileri RGBA düzlemsel sırada ham baytlar olarak depolanır. Bu, önce tüm R verisinin, ardından tüm G, sonra tüm B ve sonunda tüm A verisinin yazıldığı anlamına gelir. |
| RLE | `1` | RLE sıkıştırılmış görüntü verileri, tüm tarama satırları (satırlar * kanallar) için bayt sayılarıyla başlar; her sayı iki baytlık bir değer olarak saklanır. RLE sıkıştırılmış veri ardından gelir ve her tarama satırı ayrı ayrı sıkıştırılır. RLE sıkıştırması, Macintosh ROM rutini PackBits ve TIFF standardı tarafından kullanılan aynı sıkıştırma algoritmasıdır. |
| ZipWithoutPrediction | `2` | Tahmin olmadan ZIP. |
| ZipWithPrediction | `3` | Tahminli ZIP. |

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


