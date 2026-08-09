---
title: "Layer.IsVisible"
second_title: "Aspose.PSD for .NET API 参考"
description: "Layer 属性。获取或设置指示图层是否可见的值"
type: docs
weight: 180
url: /zh/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

获取或设置一个值，指示图层是否可见

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` 表示此实例可见；否则为 `false`。

## 示例

以下示例演示如何在 Aspose.PSD 中更改 LayerGroup 的可见性

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// 对图层名称进行更改并保存
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // 关闭组内的所有内容
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### 另请参阅

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


