---
title: VibranceLayer.Saturation
second_title: Aspose.PSD untuk Referensi .NET API
description: VibranceLayer Properti. Mendapat atau mengatur saturasi.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

Mendapat atau mengatur saturasi.

```csharp
public int Saturation { get; set; }
```

### Nilai properti

Saturasi.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Saturasi harus berkisar dari -100 hingga +100 |

### Contoh

Contoh kode berikut menunjukkan dukungan lapisan VibranceLayer dan kemampuan untuk mengedit penyesuaian ini.

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // Membuat VibranceLayer baru
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### Lihat juga

* class [VibranceLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* perakitan [Aspose.PSD](../../../)


