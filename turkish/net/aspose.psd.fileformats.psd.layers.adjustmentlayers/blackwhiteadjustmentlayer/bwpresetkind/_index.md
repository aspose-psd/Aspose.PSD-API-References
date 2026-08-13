---
title: "BlackWhiteAdjustmentLayer.BwPresetKind"
second_title: "Aspose.PSD for .NET API Referansı"
description: "BlackWhiteAdjustmentLayer özelliği. Siyah ve beyaz ön ayar türü değerini alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.BwPresetKind property

Siyah ve Beyaz ön ayar tür değerini alır veya ayarlar.

```csharp
public int BwPresetKind { get; set; }
```

### Property Value

Siyah ve beyaz ön ayar türü değeri.

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde siyah beyaz ayar katmanı özelliklerini nasıl manipüle edebileceğinizi gösterir.

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

### Ayrıca Bakınız

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


