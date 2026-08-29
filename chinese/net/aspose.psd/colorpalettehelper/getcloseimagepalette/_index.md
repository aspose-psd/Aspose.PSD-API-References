---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD for .NET API 参考"
description: "ColorPaletteHelper 方法。获取光栅图像的颜色调色板；如果图像没有调色板，则对图像进行调色；如果调色板已存在，则直接使用它，而不进行计算。"
type: docs
weight: 60
url: /zh/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

从光栅图像获取调色板（对图像进行调色），如果图像没有调色板。若调色板已存在，则直接使用而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| entriesCount | Int32 | 所需的条目数量。 |

### 返回值

颜色调色板，以 *image* 中出现频率最高的颜色开始，并包含 *entriesCount* 条目。

### 另请参阅

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

从光栅图像获取调色板（对图像进行调色），如果图像没有调色板。若调色板已存在，则直接使用而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像的边界。 |
| entriesCount | Int32 | 所需的条目数量。 |

### 返回值

颜色调色板，以 *image* 中出现频率最高的颜色开始，并包含 *entriesCount* 条目。

### 另请参阅

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

从光栅图像获取调色板（对图像进行调色），如果图像没有调色板。若调色板已存在，则直接使用而不进行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像的边界。 |
| entriesCount | Int32 | 所需的条目数量。 |
| useImagePalette | 布尔 | 如果设置，将在可用时使用其自身的图像调色板 |

### 返回值

颜色调色板，以 *image* 中出现频率最高的颜色开始，并包含 *entriesCount* 条目。

### 另请参阅

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


