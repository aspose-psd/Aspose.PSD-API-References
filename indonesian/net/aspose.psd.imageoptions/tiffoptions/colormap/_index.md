---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti TiffOptions. Mendapatkan atau mengatur peta warna"
type: docs
weight: 70
url: /id/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Mendapatkan atau mengatur peta warna.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

Peta warna.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | nilai |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Peta warna hanya dapat didefinisikan untuk sampel per piksel sama dengan 1. atau Bit per sampel tidak didefinisikan. |
| ArgumentOutOfRangeException | value;Panjang array harus sesuai dengan rumus berikut: 3 * (2**BitsPerSample). |

### Lihat Juga

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


