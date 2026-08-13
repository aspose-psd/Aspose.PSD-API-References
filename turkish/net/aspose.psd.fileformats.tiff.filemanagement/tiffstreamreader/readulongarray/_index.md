---
title: "TiffStreamReader.ReadULongArray"
second_title: "Aspose.PSD for .NET API Referansı"
description: "TiffStreamReader yöntemi. Akıştan işaretsiz tam sayı değerlerinin bir dizisini okur"
type: docs
weight: 200
url: /tr/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadULongArray method

Akıştan işaretsiz tam sayı değerlerinden oluşan bir dizi okur.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum | Int64 | Okunacak konum. |
| sayı | Int64 | Öğe sayısı. |

### Dönüş Değeri

İşaretsiz tam sayı değerlerinin dizisi.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | count;Toplam bayt sayısı negatif. + count + x4= + totalBytes |

### Ayrıca Bakınız

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


