---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 参考"
description: "LayerResourcesRegistry 方法。使用第一个适用于指定流的找到的打开器加载 LayerResource"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

使用第一个适用于指定 *stream* 的找到的打开器加载 [`LayerResource`](../../layerresource/)。

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |
| psdVersion | Int32 | PSD 版本。 |

### 返回值

已加载的 [`LayerResource`](../../layerresource/) ，如果未找到打开器则为 null。

## 备注

第一个打开器实际上是最后注册的。

### 另请参阅

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


