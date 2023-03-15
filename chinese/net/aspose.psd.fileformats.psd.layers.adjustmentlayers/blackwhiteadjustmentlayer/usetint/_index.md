---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD for .NET API 参考
description: BlackWhiteAdjustmentLayer 财产. 获取或设置一个值指示是否使用 tint color
type: docs
weight: 120
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

获取或设置一个值，指示是否使用 [tint color]。

```csharp
public bool UseTint { get; set; }
```

### 适当的价值

`真的`如果使用[色调]；否则，`错误的` .

### 例子

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


