---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 方法。添加反相调整图层"
type: docs
weight: 380
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

添加反相调整图层。

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### 返回值

创建的反相图层

## 示例

以下代码演示了对 InvertAdjustmentLayer 的支持以及如何添加 InvertAdjustmentLayer。

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### 另请参阅

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


