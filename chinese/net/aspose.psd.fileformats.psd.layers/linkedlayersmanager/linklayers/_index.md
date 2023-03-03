---
title: LinkedLayersManager.LinkLayers
second_title: Aspose.PSD for .NET API 参考
description: LinkedLayersManager 方法. 链接输入层并返回 LingGroupId.
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
## LinkedLayersManager.LinkLayers method

链接输入层并返回 LingGroupId.

```csharp
public short LinkLayers(Layer[] layers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| layers | Layer[] | 图层。 |

### 返回值

链接组 ID。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 图层为空。 |
| ArgumentException | 层数必须大于1。 |
| ArgumentException | 每层的容器要和当前的PsdImage一样。 |

### 例子

以下示例演示了如何在 Aspose.PSD 中操作链接层

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// 将现有图像加载到 PsdImage 类的实例中
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // 将所有图层链接到一个链接组中
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    //获取一层的id
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // 通过链接组 ID 获取所有链接层。
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // 从组中取消链接每一层
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // 为组中没有层的链接组 ID 检索 NULL。
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### 也可以看看

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* 部件 [Aspose.PSD](../../../)


