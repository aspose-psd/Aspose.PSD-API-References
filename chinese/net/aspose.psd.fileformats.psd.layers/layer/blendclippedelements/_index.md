---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD for .NET API 参考"
description: "Layer 属性。获取或设置裁剪元素的混合"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

获取或设置裁剪元素的混合方式。

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

裁剪元素的混合。

## 示例

以下代码演示了对 BlendClippedElements 属性的支持。

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


