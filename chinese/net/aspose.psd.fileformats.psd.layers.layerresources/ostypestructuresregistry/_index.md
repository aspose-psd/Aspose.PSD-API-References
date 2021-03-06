---
title: OSTypeStructuresRegistry
second_title: Aspose.PSD for .NET API 参考
description: 表示OSTypeStructure./ostypestructure资源注册表
type: docs
weight: 2790
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
## OSTypeStructuresRegistry class

表示[`OSTypeStructure`](../ostypestructure)资源注册表。

```csharp
public static class OSTypeStructuresRegistry
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors) { get; } | 获取注册的描述符。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor)(Stream) | 获取第一个支持的开启器描述符。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename)(string) | 通过类型名称获取第一个支持的描述符。 |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor)(Stream) | 加载[`OSTypeStructure`](../ostypestructure)使用第一个找到的适合指定*stream*的打开器。 |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener)(IOSTypeStructureLoader) | 注册开启者。 |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener)(IOSTypeStructureLoader) | 取消注册开启程序。 |

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
