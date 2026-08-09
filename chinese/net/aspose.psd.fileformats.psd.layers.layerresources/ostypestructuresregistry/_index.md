---
title: "类 OSTypeStructuresRegistry"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry 类。表示 OSTypeStructure 资源注册表"
type: docs
weight: 3200
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

表示 [`OSTypeStructure`](../ostypestructure/) 资源注册表。

```csharp
public static class OSTypeStructuresRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | 获取已注册的描述符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | 获取第一个受支持的打开器描述符。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | 通过类型名称获取第一个受支持的描述符。 |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | 加载 [`OSTypeStructure`](../ostypestructure/) 使用首次找到的适用于指定 *stream* 的打开器。 |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | 注册打开器。 |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | 注销打开器。 |

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


