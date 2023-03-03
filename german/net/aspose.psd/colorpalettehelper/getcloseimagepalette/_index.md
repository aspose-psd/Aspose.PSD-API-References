---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD für .NET-API-Referenz
description: ColorPaletteHelper methode. Ruft die Farbpalette vom Rasterbild ab palettiert das Bild falls das Bild keine hat. Falls eine Palette vorhanden ist wird sie verwendet anstatt Berechnungen durchzuführen.
type: docs
weight: 60
url: /de/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Siehe auch

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namensraum [Aspose.PSD](../../colorpalettehelper/)
* Montage [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Zielbildgrenzen. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Siehe auch

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namensraum [Aspose.PSD](../../colorpalettehelper/)
* Montage [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Ruft die Farbpalette vom Rasterbild ab (palettiert das Bild), falls das Bild keine hat. Falls eine Palette vorhanden ist, wird sie verwendet, anstatt Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Zielbildgrenzen. |
| entriesCount | Int32 | Es zählen die gewünschten Einträge. |
| useImagePalette | Boolean | Wenn gesetzt, wird eine eigene Bildpalette verwendet, falls verfügbar |

### Rückgabewert

Die Farbpalette, die mit den häufigsten Farben aus dem beginnt*image* und enthält*entriesCount* Einträge.

### Siehe auch

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namensraum [Aspose.PSD](../../colorpalettehelper/)
* Montage [Aspose.PSD](../../../)


