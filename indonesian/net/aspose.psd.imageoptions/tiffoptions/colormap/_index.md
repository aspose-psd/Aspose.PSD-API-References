---
title: TiffOptions.ColorMap
second_title: Aspose.PSD untuk Referensi .NET API
description: TiffOptions Properti. Mendapat atau menyetel peta warna.
type: docs
weight: 70
url: /id/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

Mendapat atau menyetel peta warna.

```csharp
public ushort[] ColorMap { get; set; }
```

### Nilai properti

Peta warna.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | nilai |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Peta warna dapat ditentukan untuk sampel per piksel sama dengan 1 saja. or Bit per sampel tidak ditentukan. |
| ArgumentOutOfRangeException | nilai;Panjang array harus sesuai dengan rumus berikut: 3 * (2**BitsPerSample). |

### Lihat juga

* class [TiffOptions](../)
* ruang nama [Aspose.PSD.ImageOptions](../../tiffoptions/)
* perakitan [Aspose.PSD](../../../)


