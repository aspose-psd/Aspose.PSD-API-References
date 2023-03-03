---
title: BlackWhiteAdjustmentLayer.Greens
second_title: Aspose.PSD for .NET API 参考
description: BlackWhiteAdjustmentLayer 财产. 获取或设置果岭值
type: docs
weight: 50
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/greens/
---
## BlackWhiteAdjustmentLayer.Greens property

获取或设置果岭值。

```csharp
public int Greens { get; set; }
```

### 适当的价值

果岭值。

### 例子

以下示例演示了如何在运行时在 Aspose.PSD 中添加黑白调整层

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

以下示例演示了如何在 Aspose.PSD 中操作黑白调整图层属性

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

### 也可以看看

* class [BlackWhiteAdjustmentLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* 部件 [Aspose.PSD](../../../)


