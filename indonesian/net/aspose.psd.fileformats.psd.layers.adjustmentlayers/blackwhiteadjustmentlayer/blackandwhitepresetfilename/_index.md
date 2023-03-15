---
title: BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName
second_title: Aspose.PSD untuk Referensi .NET API
description: BlackWhiteAdjustmentLayer Properti. Mendapat atau menyetel nama file prasetel hitam putih.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blackandwhitepresetfilename/
---
## BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName property

Mendapat atau menyetel nama file prasetel hitam putih.

```csharp
public string BlackAndWhitePresetFileName { get; set; }
```

### Nilai properti

Nama file preset hitam putih.

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


