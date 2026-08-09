---
title: "PostResource.Levels"
second_title: "Aspose.PSD for .NET API 参考"
description: "PostResource 属性。Posterize 图层的层级"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/
---
{{< psd/tize >}}
## PostResource.Levels property

Posterize 图层的级别。

```csharp
public short Levels { get; set; }
```

### 返回值

Levels 整型值

## 示例

以下代码演示了对 PostResource 的操作能力。

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### 另请参阅

* class [PostResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


