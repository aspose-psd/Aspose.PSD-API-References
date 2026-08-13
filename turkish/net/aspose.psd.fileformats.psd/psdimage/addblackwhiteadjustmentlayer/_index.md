---
title: "PsdImage.AddBlackWhiteAdjustmentLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage metodu. Siyah beyaz ayar katmanını ekler"
type: docs
weight: 300
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddBlackWhiteAdjustmentLayer method

Siyah beyaz ayar katmanını ekler.

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### Dönüş Değeri

Oluşturulan siyah beyaz ayar katmanı.

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde çalışma zamanında siyah beyaz ayar katmanını nasıl ekleyebileceğinizi gösterir.

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

### Ayrıca Bakınız

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


