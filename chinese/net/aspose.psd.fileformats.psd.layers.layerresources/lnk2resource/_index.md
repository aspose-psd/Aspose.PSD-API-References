---
title: "Lnk2Resource 类"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.Lnk2Resource 类。定义了包含 PSD 格式图像中嵌入文件信息的类。链接资源可能包含多个 LiFdDataSource 实例，可通过索引器访问。"
type: docs
weight: 3030
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---
{{< psd/tize >}}
## Lnk2Resource class

定义了包含 PSD 格式图像中嵌入文件信息的类。链接资源可能包含多个 [`LiFdDataSource`](../lifddatasource/) 实例，可通过索引器访问。

```csharp
public class Lnk2Resource : LinkResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Lnk2Resource](lnk2resource/)() | 初始化 `Lnk2Resource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | 获取可通过索引器访问的链接数据源的计数。 |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | 获取一个值，指示此链接资源实例是否为空。 |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/item/) { get; } | 获取指定索引处的 [`LiFdDataSource`](../lifddatasource/)。（2 个索引器） |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | 获取 PSD 全局链接资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | 保存资源块数据。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/typetoolkey/) | 类型工具信息键。 |

### 另请参阅

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [LinkResource](../linkresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


