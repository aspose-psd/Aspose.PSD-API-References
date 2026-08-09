---
title: "类 PrintFlagsResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Resources.PrintFlagsResource 类。打印标志资源"
type: docs
weight: 4300
url: /zh/net/aspose.psd.fileformats.psd.resources/printflagsresource/
---
{{< psd/tize >}}
## PrintFlagsResource class

Print flags 资源

```csharp
public sealed class PrintFlagsResource : ResourceBlock
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PrintFlagsResource](printflagsresource/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BleedScale](../../aspose.psd.fileformats.psd.resources/printflagsresource/bleedscale/) { get; set; } | 获取或设置出血比例。 |
| [BleedWidth](../../aspose.psd.fileformats.psd.resources/printflagsresource/bleedwidth/) { get; set; } | 获取或设置出血宽度。 |
| [CenterCropMark](../../aspose.psd.fileformats.psd.resources/printflagsresource/centercropmark/) { get; set; } | 获取或设置中心裁剪标记。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/printflagsresource/datasize/) { get; } | 获取资源数据的字节大小。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 获取或设置资源的唯一标识符。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/printflagsresource/minimalversion/) { get; } | 获取所需的最低 PSD 版本。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 获取或设置资源名称。Pascal 字符串，填充以使大小为偶数（空名称由两个字节的 0 组成）。 |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 获取资源签名。应始终为 '8BIM'。 |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 获取资源块的字节大小（包括其数据）。 |
| [Version](../../aspose.psd.fileformats.psd.resources/printflagsresource/version/) { get; set; } | 获取或设置版本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 将资源块保存到指定的流。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 验证资源值。 |

### 另请参阅

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


