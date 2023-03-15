---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: Aspose.PSD for .NET API Referansı
description: BlackWhiteAdjustmentLayer mülk. Siyah beyaz önceden ayarlanmış tür değerini alır veya ayarlar.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
## BlackWhiteAdjustmentLayer.BwPresetKind property

Siyah beyaz önceden ayarlanmış tür değerini alır veya ayarlar.

```csharp
public int BwPresetKind { get; set; }
```

### Mülk değeri

Siyah beyaz önceden ayarlanmış tür değeri.

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de siyah beyaz ayarlama katmanı özelliklerini nasıl değiştirebileceğinizi gösterir.

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

### Ayrıca bakınız

* class [BlackWhiteAdjustmentLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* toplantı [Aspose.PSD](../../../)


