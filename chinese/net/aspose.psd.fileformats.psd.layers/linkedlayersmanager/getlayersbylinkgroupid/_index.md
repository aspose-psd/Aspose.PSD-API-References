---
title: "LinkedLayersManager.GetLayersByLinkGroupId"
second_title: "Aspose.PSD for .NET API 参考"
description: "LinkedLayersManager 方法。按链接组 ID 获取图层"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLayersByLinkGroupId method

根据链接组 ID 获取图层。

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| linkGroupId | Int16 | 链接组 ID。 |

### 返回值

图层数组。

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


