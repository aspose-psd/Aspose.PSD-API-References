---
title: "PsdImage.AddThresholdAdjustmentLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 方法。添加阈值调整图层"
type: docs
weight: 480
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddThresholdAdjustmentLayer method

添加阈值调整图层。

```csharp
public ThresholdLayer AddThresholdAdjustmentLayer()
```

### 返回值

已创建的阈值调整图层。

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

* class [ThresholdLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


