---
title: BlackWhiteAdjustmentLayer.Magentas
second_title: Справочник по Aspose.PSD для .NET API
description: BlackWhiteAdjustmentLayer свойство. Получает или задает значение пурпурного цвета.
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/magentas/
---
## BlackWhiteAdjustmentLayer.Magentas property

Получает или задает значение пурпурного цвета.

```csharp
public int Magentas { get; set; }
```

### Стоимость имущества

Значение пурпурного цвета.

### Примеры

В следующем примере показано, как добавить черно-белый корректирующий слой во время выполнения в Aspose.PSD.

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

В следующем примере показано, как вы можете манипулировать свойствами корректирующего слоя «черно-белый» в Aspose.PSD.

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

### Смотрите также

* class [BlackWhiteAdjustmentLayer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* сборка [Aspose.PSD](../../../)


