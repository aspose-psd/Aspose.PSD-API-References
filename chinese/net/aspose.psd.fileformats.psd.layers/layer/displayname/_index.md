---
title: "Layer.DisplayName"
second_title: "Aspose.PSD for .NET API 参考"
description: "Layer 属性。获取或设置图层的显示名称"
type: docs
weight: 110
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

获取或设置图层的显示名称。

```csharp
public string DisplayName { get; set; }
```

### Property Value

图层的显示名称。

## 示例

以下示例演示了设置 DisplayName 值的能力，使图层名称正确显示。

```csharp
[C#]

// 对图层名称进行更改并保存
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // 将新值设置到 DisplayName 属性
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


