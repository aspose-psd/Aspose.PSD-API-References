---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD for .NET API 参考"
description: "VibranceLayer 属性。获取或设置饱和度"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

获取或设置饱和度。

```csharp
public int Saturation { get; set; }
```

### Property Value

饱和度。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 饱和度必须在 -100 到 +100 的范围内 |

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


