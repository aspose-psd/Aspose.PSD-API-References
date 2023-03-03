---
title: Class LinkedLayersManager
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager 班级. 链接层管理器类
type: docs
weight: 3400
url: /zh/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

链接层管理器类。

```csharp
public sealed class LinkedLayersManager
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | 通过链接组 id 获取图层。 |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | 获取与层关联的链接组 ID。 |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | 链接输入层并返回 LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | 取消链接图层.. |

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

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* 部件 [Aspose.PSD](../../)


