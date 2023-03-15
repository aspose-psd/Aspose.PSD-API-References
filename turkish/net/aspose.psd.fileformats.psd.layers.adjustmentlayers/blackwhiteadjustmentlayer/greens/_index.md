---
title: BlackWhiteAdjustmentLayer.Greens
second_title: Aspose.PSD for .NET API Referansı
description: BlackWhiteAdjustmentLayer mülk. Yeşiller değerini alır veya ayarlar.
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/greens/
---
## BlackWhiteAdjustmentLayer.Greens property

Yeşiller değerini alır veya ayarlar.

```csharp
public int Greens { get; set; }
```

### Mülk değeri

Yeşiller değeri.

### Örnekler

Aşağıdaki örnek, çalışma zamanında Aspose.PSD'de siyah beyaz ayarlama katmanını nasıl ekleyebileceğinizi gösterir.

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

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


