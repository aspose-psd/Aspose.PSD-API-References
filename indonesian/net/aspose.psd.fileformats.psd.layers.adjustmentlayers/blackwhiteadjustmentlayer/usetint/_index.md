---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD untuk Referensi .NET API
description: BlackWhiteAdjustmentLayer Properti. Mendapat atau menetapkan nilai yang menunjukkan apakah tint color digunakan.
type: docs
weight: 120
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

Mendapat atau menetapkan nilai yang menunjukkan apakah [tint color] digunakan.

```csharp
public bool UseTint { get; set; }
```

### Nilai properti

`BENAR` jika digunakan [warna tint]; jika tidak,`PALSU` .

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat memanipulasi properti lapisan penyesuaian hitam putih di Aspose.PSD

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### Lihat juga

* class [BlackWhiteAdjustmentLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* perakitan [Aspose.PSD](../../../)


