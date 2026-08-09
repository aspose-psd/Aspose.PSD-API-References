---
title: "OSTypeStructuresRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 参考"
description: "OSTypeStructuresRegistry 方法。获取第一个受支持的打开器描述符。"
type: docs
weight: 20
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry.GetFirstSupportedDescriptor method

获取第一个受支持的打开器描述符。

```csharp
public static IOSTypeStructureLoader GetFirstSupportedDescriptor(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |

### 返回值

层资源加载器描述符，如果该流没有支持的加载器描述符则返回 null。

## 备注

第一个加载器实际上是最后注册的。

### 另请参阅

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


