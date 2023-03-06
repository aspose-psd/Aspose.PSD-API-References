---
title: TiffOptions.ColorMap
second_title: Aspose.PSD for .NET API Referansı
description: TiffOptions mülk. Renk haritasını alır veya ayarlar.
type: docs
weight: 70
url: /tr/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Renk haritasını alır veya ayarlar.

```csharp
public ushort[] ColorMap { get; set; }
```

### Mülk değeri

Renk haritası.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | değer |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Renk haritası yalnızca 1'e eşit piksel başına örnekler için tanımlanabilir. veya Örnek başına bit tanımlanmamıştır. |
| ArgumentOutOfRangeException | value;Dizi uzunluğu aşağıdaki formüle karşılık gelmelidir: 3 * (2**BitsPerSample). |

### Ayrıca bakınız

* class [TiffOptions](../)
* ad alanı [Aspose.PSD.ImageOptions](../../tiffoptions/)
* toplantı [Aspose.PSD](../../../)


