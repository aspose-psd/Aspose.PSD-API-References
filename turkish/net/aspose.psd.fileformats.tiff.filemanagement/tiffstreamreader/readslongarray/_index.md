---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD for .NET API Referansı"
description: "TiffStreamReader yöntemi. Akıştan imzalı tam sayı değerlerinin bir dizisini okur."
type: docs
weight: 140
url: /tr/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Akıştan imzalı tamsayı değerlerinden oluşan bir dizi okur.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | Int64 | Okunacak konum. |
| sayı | Int64 | Öğe sayısı. |

### Dönüş Değeri

İmzalı tam sayı değerlerinin dizisi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | count;Toplam bayt sayısı negatif. + count + x4= + totalBytes |

### Ayrıca Bakınız

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


