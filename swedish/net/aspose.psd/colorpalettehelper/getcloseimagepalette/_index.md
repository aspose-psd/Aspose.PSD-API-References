---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD för .NET API-referens
description: ColorPaletteHelper metod. Hämtar färgpalett från rasterbild palleterar bild om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.
type: docs
weight: 60
url: /sv/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| entriesCount | Int32 | De önskade posterna räknas. |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namnutrymme [Aspose.PSD](../../colorpalettehelper/)
* hopsättning [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbilden gränsar. |
| entriesCount | Int32 | De önskade posterna räknas. |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namnutrymme [Aspose.PSD](../../colorpalettehelper/)
* hopsättning [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Hämtar färgpalett från rasterbild (palleterar bild) om bilden inte har någon. Om palett finns kommer den att användas istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbilden gränsar. |
| entriesCount | Int32 | De önskade posterna räknas. |
| useImagePalette | Boolean | Om den är inställd kommer den att använda sin egen bildpalett om tillgänglig |

### Returvärde

Färgpaletten som börjar med de vanligaste färgerna från*image* och innehåller*entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namnutrymme [Aspose.PSD](../../colorpalettehelper/)
* hopsättning [Aspose.PSD](../../../)


