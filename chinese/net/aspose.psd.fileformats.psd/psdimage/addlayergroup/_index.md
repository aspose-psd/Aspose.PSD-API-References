---
title: "PsdImage.AddLayerGroup"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 方法。 添加图层组"
type: docs
weight: 400
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

添加图层组。

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| groupName | String | 组的名称。 |
| index | Int32 | 要在其后插入的图层的索引。 |
| startBehaviour | 布尔 | 如果设置为 `true` [start behaviour]，则组在启动时将处于打开状态，否则为最小化状态。 |

### 返回值

打开组图层

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 索引必须在图层计数的范围内 |

### 另请参阅

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


