---
title: "BlackWhiteAdjustmentLayer.Magentas"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство BlackWhiteAdjustmentLayer. Получает или задает значение маджент."
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/magentas/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.Magentas property

Получает или задает значение пурпурного.

```csharp
public int Magentas { get; set; }
```

### Property Value

Значение маджент.

## Примеры

В следующем примере показано, как можно добавить слой коррекции черно-белого изображения во время выполнения в Aspose.PSD

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


