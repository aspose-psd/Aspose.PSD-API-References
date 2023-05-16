---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD for .NET API Reference
description: ColorPaletteHelper method. Gets color palette from raster image palletizes image in case the image does not have one. In case palette exists it will be used instead performing calculations
type: docs
weight: 60
url: /net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| entriesCount | Int32 | The desired entries count. |

### Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../colorpalettehelper/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| destBounds | Rectangle | The destination image bounds. |
| entriesCount | Int32 | The desired entries count. |

### Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../colorpalettehelper/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| destBounds | Rectangle | The destination image bounds. |
| entriesCount | Int32 | The desired entries count. |
| useImagePalette | Boolean | If set, it will use its own image palette if available |

### Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../colorpalettehelper/)
* assembly [Aspose.PSD](../../../)


