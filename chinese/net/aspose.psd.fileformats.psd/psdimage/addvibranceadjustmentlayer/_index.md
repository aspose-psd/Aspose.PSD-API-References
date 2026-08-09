---
title: "PsdImage.AddVibranceAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 方法。添加 Vibrance 调整图层"
type: docs
weight: 490
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddVibranceAdjustmentLayer method

添加活力调整图层。

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### 返回值

新创建的 Vibrance 图层。

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

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


