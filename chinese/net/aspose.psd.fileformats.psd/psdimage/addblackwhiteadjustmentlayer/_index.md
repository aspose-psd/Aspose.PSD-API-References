---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD for .NET API 参考
description: PsdImage 方法. 添加黑白调整图层
type: docs
weight: 290
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

添加黑白调整图层。

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### 返回值

创建的黑白调整层。

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

### 也可以看看

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 部件 [Aspose.PSD](../../../)


