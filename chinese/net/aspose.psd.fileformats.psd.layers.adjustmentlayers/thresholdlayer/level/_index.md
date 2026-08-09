---
title: "ThresholdLayer.Level"
second_title: "Aspose.PSD for .NET API 参考"
description: "ThresholdLayer 属性。获取和设置阈值水平"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/level/
---
{{< psd/tize >}}
## ThresholdLayer.Level property

获取并设置阈值级别。

```csharp
public short Level { get; set; }
```

### Property Value

该级别。

## 示例

以下代码演示了 ThresholdLayer 调整图层的支持。

```csharp
[C#]

string sourceFileWithThresholdLayer = "flowers_threshold_source.psd";
string outputPsdWithThresholdLayer = "flowers_threshold_output.psd";
string outputPngWithThresholdLayer = "flowers_threshold_output.png";

string sourceFileWithoutThresholdLayer = "flowers_source.psd";
string outputPsdWithoutThresholdLayer = "flowers_output.psd";
string outputPngWithoutThresholdLayer = "flowers_output.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// 获取、检查并更改图像中的 Threshold 调整图层。
using (var image = (PsdImage)Image.Load(sourceFileWithThresholdLayer))
{
    foreach (var layer in image.Layers)
    {
        if (layer is ThresholdLayer)
        {
            // 获取 Threshold 调整图层。
            ThresholdLayer thrsLayer = (ThresholdLayer)layer;
            var level = thrsLayer.Level;

            // 检查图层参数。
            AssertAreEqual(level, (short)115);

            // 设置图层参数。
            thrsLayer.Level = 50;

            image.Save(outputPsdWithThresholdLayer);
            image.Save(outputPngWithThresholdLayer, new PngOptions());
        }
    }
}

// 添加并设置 Threshold 调整图层到图像中。
using (var image = (PsdImage)Image.Load(sourceFileWithoutThresholdLayer))
{
    // 添加 Threshold 调整图层。
    ThresholdLayer thresholdLayer = image.AddThresholdAdjustmentLayer();

    // 设置图层参数。
    thresholdLayer.Level = 115;

    image.Save(outputPsdWithoutThresholdLayer);
    image.Save(outputPngWithoutThresholdLayer, new PngOptions());
}
```

### 另请参阅

* class [ThresholdLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


