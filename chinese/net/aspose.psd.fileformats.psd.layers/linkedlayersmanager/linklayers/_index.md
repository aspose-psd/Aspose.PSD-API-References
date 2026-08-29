---
title: "LinkedLayersManager.LinkLayers"
second_title: "Aspose.PSD for .NET API 参考"
description: "LinkedLayersManager 方法。链接输入图层并返回 LingGroupId"
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
{{< psd/tize >}}
## LinkedLayersManager.LinkLayers method

链接输入图层并返回 LingGroupId。

```csharp
public short LinkLayers(Layer[] layers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layers | Layer[] | 图层。 |

### 返回值

链接组 ID。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 层为 null。 |
| ArgumentException | 层的数量必须大于 1。 |
| ArgumentException | 每个层的容器应与当前的 PsdImage 相同。 |

## 示例

以下示例演示如何在 Aspose.PSD 中操作链接图层。

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // 将所有图层链接到一个链接组。
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // 获取单个图层的 ID。
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // 根据链接组 ID 获取所有链接图层。
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // 从组中取消链接每个图层。
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // 对于组中没有图层的链接组 ID，返回 NULL。
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### 另请参阅

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


