---
title: Class LinkResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource 班级. 定义 LinkResource 类其中包含有关 PSD 格式图像中链接或嵌入文件的信息 链接资源可能包含几个LinkDataSource任何派生类中的索引器都可以访问的实例
type: docs
weight: 2710
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

定义 LinkResource 类，其中包含有关 PSD 格式图像中链接或嵌入文件的信息。 链接资源可能包含几个[`LinkDataSource`](../linkdatasource/)任何派生类中的索引器都可以访问的实例。

```csharp
public abstract class LinkResource : LayerResource
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | 获取索引器可以访问的链接数据源的个数。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | 获取该链接资源实例是否为空的值。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | 获取[`LinkDataSource`](../linkdatasource/)在指定的索引处，它是链接数据源的唯一标识符.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | 获取以字节为单位的 PSD 全局链接资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | 获取 PSD 格式版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | 获取 PSD 全局链接资源签名。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | 保存资源块数据。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


