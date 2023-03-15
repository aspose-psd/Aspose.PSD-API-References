---
title: TiffOptions.ColorMap
second_title: Aspose.PSD for .NET API 参考
description: TiffOptions 财产. 获取或设置颜色图
type: docs
weight: 70
url: /zh/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
## TiffOptions.ColorMap property

获取或设置颜色图。

```csharp
public ushort[] ColorMap { get; set; }
```

### 适当的价值

颜色图.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 价值 |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | 可以为每像素等于 1 的样本定义颜色映射。 或 每个样本的位未定义。 |
| ArgumentOutOfRangeException | value;数组长度必须对应以下公式：3 * (2**BitsPerSample)。 |

### 也可以看看

* class [TiffOptions](../)
* 命名空间 [Aspose.PSD.ImageOptions](../../tiffoptions/)
* 部件 [Aspose.PSD](../../../)


