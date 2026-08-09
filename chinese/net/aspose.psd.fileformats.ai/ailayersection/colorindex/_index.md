---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD for .NET API 参考"
description: "AiLayerSection 属性。获取或设置颜色的索引。此参数的取值范围为 1 到 26。每个整数代表一种颜色，可分配给图层用于用户识别目的"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

获取或设置颜色的索引。此参数的取值范围为 –1 到 26。每个整数代表一种颜色，可分配给图层以供用户识别。

```csharp
public int ColorIndex { get; set; }
```

### Property Value

颜色的索引。

## 示例

以下代码演示了 AiLayerSection 中对 HasMultiLayerMasks 和 ColorIndex 属性的支持。

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### 另请参阅

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


