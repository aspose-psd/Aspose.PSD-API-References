---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD for .NET API 参考"
description: "AiLayerSection 属性。获取或设置一个值，指示此实例是否具有多图层蒙版"
type: docs
weight: 60
url: /zh/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

获取或设置一个值，指示此实例是否具有多图层蒙版。

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` 如果此实例具有多图层蒙版；否则为 `false`。

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


