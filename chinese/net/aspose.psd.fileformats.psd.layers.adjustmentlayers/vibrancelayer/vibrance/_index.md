---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD for .NET API 参考"
description: "VibranceLayer 属性。获取或设置活力"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

获取或设置活力。

```csharp
public int Vibrance { get; set; }
```

### Property Value

鲜艳度。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 鲜艳度必须在 -180 到 +180 的范围内 |

## 示例

以下代码示例演示了对 VibranceLayer 图层的支持以及编辑此调整的能力。

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // 创建新的 VibranceLayer
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### 另请参阅

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


