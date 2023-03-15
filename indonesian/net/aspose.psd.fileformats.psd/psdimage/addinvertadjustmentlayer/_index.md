---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdImage metode. Menambahkan lapisan penyesuaian terbalik.
type: docs
weight: 360
url: /id/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Menambahkan lapisan penyesuaian terbalik.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Nilai Pengembalian

Lapisan pembalik yang dibuat

### Contoh

Kode berikut menunjukkan dukungan untuk InvertAdjustmentLayer dan cara menambahkan InvertAdjustmentLayer.

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### Lihat juga

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)


