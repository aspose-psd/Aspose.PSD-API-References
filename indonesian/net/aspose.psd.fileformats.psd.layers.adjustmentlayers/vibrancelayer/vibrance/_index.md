---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti VibranceLayer. Mendapatkan atau mengatur vibransi"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

Mendapatkan atau mengatur vibrance.

```csharp
public int Vibrance { get; set; }
```

### Property Value

Vibransi.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Vibransi harus berada dalam rentang dari -180 hingga +180 |

## Contoh

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

### Lihat Juga

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


