---
title: Class ResourceBlock
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.ResourceBlock 班级. 资源块
type: docs
weight: 3610
url: /zh/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

资源块。

```csharp
public abstract class ResourceBlock
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | 获取以字节为单位的资源数据大小。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。 Pascal 字符串，填充以使大小均匀（空名称由两个字节 0 组成）. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为“8BIM”. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 获取以字节为单位的资源块大小，包括其数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流中。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 验证资源值。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | ImageReady 的资源签名。 |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | 常规 Photoshop 资源签名。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | 表示资源块状态。 |

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 部件 [Aspose.PSD](../../)


