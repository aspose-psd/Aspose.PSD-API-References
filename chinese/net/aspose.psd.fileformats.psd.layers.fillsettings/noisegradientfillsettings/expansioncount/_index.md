---
title: "NoiseGradientFillSettings.ExpansionCount"
second_title: "Aspose.PSD for .NET API 参考"
description: "NoiseGradientFillSettings 属性。获取或设置扩展计数 2（适用于 Photoshop 6.0）."
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/expansioncount/
---
{{< psd/tize >}}
## NoiseGradientFillSettings.ExpansionCount property

获取或设置扩展计数（= 2，适用于 Photoshop 6.0）。

```csharp
public short ExpansionCount { get; set; }
```

## 示例

以下代码演示了对渐变映射图层的支持。

```csharp
[C#]

string sourceFile = "gradient_map_src.psd";
string outputFile = "gradient_map_src_output.psd";

using (PsdImage im = (PsdImage)Image.Load(sourceFile))
{
    // 添加渐变映射调整图层。
    GradientMapLayer layer = im.AddGradientMapAdjustmentLayer();
    layer.GradientSettings.Reverse = true;
    layer.Update();

    im.Save(outputFile);
}

// 检查已保存的更改
using (PsdImage im = (PsdImage)Image.Load(outputFile))
{
    GradientMapLayer gradientMapLayer = im.Layers[1] as GradientMapLayer;
    GradientFillSettings gradientSettings = (GradientFillSettings)gradientMapLayer.GradientSettings;

    AssertAreEqual(90.0, gradientSettings.Angle);
    AssertAreEqual((short)4096, gradientSettings.Interpolation);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(true, gradientSettings.AlignWithLayer);
    AssertAreEqual(false, gradientSettings.Dither);
    AssertAreEqual(GradientType.Linear, gradientSettings.GradientType);
    AssertAreEqual(100, gradientSettings.Scale);
    AssertAreEqual(0.0, gradientSettings.HorizontalOffset);
    AssertAreEqual(0.0, gradientSettings.VerticalOffset);
    AssertAreEqual("Custom", gradientSettings.GradientName);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 另请参阅

* class [NoiseGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


