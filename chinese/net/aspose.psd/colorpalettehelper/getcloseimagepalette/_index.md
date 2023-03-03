---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD for .NET API 参考
description: ColorPaletteHelper 方法. 如果图像没有调色板则从光栅图像调色板图像获取调色板如果调色板存在它将被用来代替执行计算
type: docs
weight: 60
url: /zh/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

如果图像没有调色板，则从光栅图像（调色板图像）获取调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| entriesCount | Int32 | 所需的条目计数。 |

### 返回值

以最常见的颜色开始的调色板*image*并包含*entriesCount*条目.

### 也可以看看

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* 命名空间 [Aspose.PSD](../../colorpalettehelper/)
* 部件 [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

如果图像没有调色板，则从光栅图像（调色板图像）获取调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像边界。 |
| entriesCount | Int32 | 所需的条目计数。 |

### 返回值

以最常见的颜色开始的调色板*image*并包含*entriesCount*条目.

### 也可以看看

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* 命名空间 [Aspose.PSD](../../colorpalettehelper/)
* 部件 [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

如果图像没有调色板，则从光栅图像（调色板图像）获取调色板。如果调色板存在，它将被用来代替执行计算。

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 光栅图像。 |
| destBounds | Rectangle | 目标图像边界。 |
| entriesCount | Int32 | 所需的条目计数。 |
| useImagePalette | Boolean | 如果设置，它将使用自己的图像调色板（如果可用） |

### 返回值

以最常见的颜色开始的调色板*image*并包含*entriesCount*条目.

### 也可以看看

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* 命名空间 [Aspose.PSD](../../colorpalettehelper/)
* 部件 [Aspose.PSD](../../../)


