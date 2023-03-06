---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage yöntem. Siyah beyaz ayarlama katmanını ekler.
type: docs
weight: 290
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

Siyah beyaz ayarlama katmanını ekler.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Geri dönüş değeri

Oluşturulan siyah beyaz ayar katmanı.

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

### Ayrıca bakınız

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


