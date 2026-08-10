---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode PsdImage. Menambahkan lapisan penyesuaian invert"
type: docs
weight: 380
url: /id/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Menambahkan lapisan penyesuaian invers.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Nilai Kembalian

Lapisan invert yang dibuat

## Contoh

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

### Lihat Juga

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


