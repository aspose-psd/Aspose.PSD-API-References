---
title: Class ThumbnailResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Resources.ThumbnailResource 班级. 缩略图资源块
type: docs
weight: 3910
url: /zh/net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---
## ThumbnailResource class

缩略图资源块。

```csharp
public class ThumbnailResource : ResourceBlock
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | 获取或设置位像素。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | 获取以字节为单位的资源数据大小。 |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | 获取或设置缩略图数据格式。 |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | 获取或设置缩略图的高度（以像素为单位）。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | 获取或设置 JPEG 选项。适用于仅将缩略图资源保存为 JPEG 文件格式的情况。当定义了 RAW 格式时，此选项无效。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | 获取所需的最低 psd 版本。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。 Pascal 字符串，填充以使大小均匀（空名称由两个字节 0 组成）. |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | 获取或设置平面计数。 |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为“8BIM”. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 获取以字节为单位的资源块大小，包括其数据。 |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | 获取或设置压缩后的大小。用于一致性检查。 |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | 获取或设置 32 位 ARGB 缩略图数据。 |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | 获取或设置缩略图数据。 |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | 获取总数据大小。 |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | 获取或设置缩略图的宽度（以像素为单位）。 |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | 获取以字节为单位的行宽。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流中。 |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | 验证资源值。 |

### 也可以看看

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 部件 [Aspose.PSD](../../)


