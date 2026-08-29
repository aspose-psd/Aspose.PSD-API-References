---
title: "BlackWhiteAdjustmentLayer.BwPresetKind"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство BlackWhiteAdjustmentLayer. Получает или задает значение типа предустановки черно‑белого"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.BwPresetKind property

Получает или задает значение типа предустановки черно‑белого.

```csharp
public int BwPresetKind { get; set; }
```

### Property Value

Значение типа предустановки черно‑белого.

## Примеры

В следующем примере демонстрируется, как можно управлять свойствами слоя черно-белой коррекции в Aspose.PSD

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

### См. также

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


