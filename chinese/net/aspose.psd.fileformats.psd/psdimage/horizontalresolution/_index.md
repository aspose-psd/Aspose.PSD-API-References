---
title: "PsdImage.HorizontalResolution"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 属性。获取或设置此 PsdImage 的水平分辨率（每英寸像素数）"
type: docs
weight: 170
url: /zh/net/aspose.psd.fileformats.psd/psdimage/horizontalresolution/
---
{{< psd/tize >}}
## PsdImage.HorizontalResolution property

获取或设置此 [`PsdImage`](../) 的水平分辨率（每英寸像素数）。

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

水平分辨率。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 未找到 ResolutionInfo 资源，无法设置正确的分辨率 |

## 备注

PSD 的默认值为 72，因此如果未找到 [`ResolutionInfoResource`](../../../aspose.psd.fileformats.psd.resources/resolutioninforesource/)，则返回此值。

### 另请参阅

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


