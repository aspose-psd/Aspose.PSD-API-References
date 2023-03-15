---
title: Class ColorTransferFunctionsResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Resources.ColorTransferFunctionsResource 班级. 颜色转移资源
type: docs
weight: 3680
url: /zh/net/aspose.psd.fileformats.psd.resources/colortransferfunctionsresource/
---
## ColorTransferFunctionsResource class

颜色转移资源

```csharp
public sealed class ColorTransferFunctionsResource : ResourceBlock
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ColorTransferFunctionsResource](colortransferfunctionsresource/)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ColorTransferData](../../aspose.psd.fileformats.psd.resources/colortransferfunctionsresource/colortransferdata/) { get; set; } | 获取或设置颜色传输数据。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/colortransferfunctionsresource/datasize/) { get; } | 获取以字节为单位的资源数据大小。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/colortransferfunctionsresource/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。 Pascal 字符串，填充以使大小均匀（空名称由两个字节 0 组成）. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为“8BIM”. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 获取以字节为单位的资源块大小，包括其数据。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流中。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 验证资源值。 |

### 也可以看看

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 部件 [Aspose.PSD](../../)


