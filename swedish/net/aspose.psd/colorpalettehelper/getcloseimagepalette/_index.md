---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ColorPaletteHelper-metod. Hämtar färgpalett från rasterbild och palettiserar bilden om den inte har en. Om en palett redan finns används den istället för att utföra beräkningar."
type: docs
weight: 60
url: /sv/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | RasterImage | Rasterbilden. |
| entriesCount | Int32 | Önskat antal poster. |

### Returvärde

Färgpaletten som börjar med de mest frekventa färgerna från *bilden* och innehåller *entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbildernas gränser. |
| entriesCount | Int32 | Önskat antal poster. |

### Returvärde

Färgpaletten som börjar med de mest frekventa färgerna från *bilden* och innehåller *entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns används den istället för att utföra beräkningar.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | RasterImage | Rasterbilden. |
| destBounds | Rectangle | Målbildernas gränser. |
| entriesCount | Int32 | Önskat antal poster. |
| useImagePalette | Boolean | Om den är satt kommer den att använda sin egen bildpalett om den finns tillgänglig. |

### Returvärde

Färgpaletten som börjar med de mest frekventa färgerna från *bilden* och innehåller *entriesCount* poster.

### Se även

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


