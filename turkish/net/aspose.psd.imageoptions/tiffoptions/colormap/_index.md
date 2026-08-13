---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD for .NET API Referansı"
description: "TiffOptions özelliği. Renk haritasını alır veya ayarlar"
type: docs
weight: 70
url: /tr/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Renk haritasını alır veya ayarlar.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

Renk haritası.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | değer |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Renk haritası yalnızca piksel başına örnek sayısı 1 olduğunda tanımlanabilir. veya örnek başına bit değeri tanımlı değildir. |
| ArgumentOutOfRangeException | değer;Dizi uzunluğu aşağıdaki formüle uygun olmalıdır: 3 * (2**BitsPerSample). |

### Ayrıca Bakınız

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


