---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD for .NET API 参考"
description: "TiffOptions 属性。获取或设置颜色映射"
type: docs
weight: 70
url: /zh/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

获取或设置颜色映射。

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

颜色映射。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 值 |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | 颜色映射只能在每像素样本数等于 1 时定义。或位深未定义。 |
| ArgumentOutOfRangeException | value;数组长度必须符合以下公式：3 * (2**BitsPerSample)。 |

### 另请参阅

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


