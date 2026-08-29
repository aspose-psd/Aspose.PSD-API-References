---
title: "BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство BlackWhiteAdjustmentLayer. Получает или задает имя файла предустановки черно-белого режима."
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blackandwhitepresetfilename/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName property

Получает или задает имя файла предустановки черно‑белого.

```csharp
public string BlackAndWhitePresetFileName { get; set; }
```

### Property Value

Имя файла предустановки черно-белого режима.

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


