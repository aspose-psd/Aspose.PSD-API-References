---
title: VibranceLayer.Saturation
second_title: Aspose.PSD for .NET API 参考
description: VibranceLayer 财产. 获取或设置饱和度
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
## VibranceLayer.Saturation property

获取或设置饱和度。

```csharp
public int Saturation { get; set; }
```

### 适当的价值

饱和度.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | 饱和度必须在 -100 到 +100 的范围内 |

### 例子

以下代码示例演示了对 VibranceLayer 层的支持以及编辑此调整的能力。

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // 创建一个新的 VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### 也可以看看

* class [VibranceLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* 部件 [Aspose.PSD](../../../)


