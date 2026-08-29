---
title: "RasterImage.GetPixel"
second_title: "Aspose.PSD for .NET API 参考"
description: "RasterImage 方法。获取图像像素。性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。为更高效的像素操作，请使用 LoadArgb32Pixels 方法一次性检索整个像素数组。"
type: docs
weight: 320
url: /zh/net/aspose.psd/rasterimage/getpixel/
---
{{< psd/tize >}}
## RasterImage.GetPixel method

获取图像像素。性能警告：避免使用此方法遍历所有图像像素，因为这可能导致显著的性能问题。为了更高效的像素操作，请使用 `LoadArgb32Pixels` 方法一次性检索整个像素数组。

```csharp
public Color GetPixel(int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 像素的 x 坐标位置。 |
| y | Int32 | 像素的 y 坐标位置。 |

### 返回值

指定位置的像素颜色。

### 另请参阅

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


