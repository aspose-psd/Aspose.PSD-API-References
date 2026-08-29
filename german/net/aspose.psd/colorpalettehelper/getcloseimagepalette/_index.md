---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ColorPaletteHelper-Methode. Ermittelt die Farbpalette aus einem Rasterbild, palettiert das Bild, falls es keine Palette hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen."
type: docs
weight: 60
url: /de/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Liefert die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, um Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| entriesCount | Int32 | Die gewünschte Anzahl von Einträgen. |

### Rückgabewert

Die Farbpalette, die mit den am häufigsten vorkommenden Farben aus dem *Bild* beginnt und *entriesCount* Einträge enthält.

### Siehe auch

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Liefert die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, um Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Begrenzungen des Zielbildes. |
| entriesCount | Int32 | Die gewünschte Anzahl von Einträgen. |

### Rückgabewert

Die Farbpalette, die mit den am häufigsten vorkommenden Farben aus dem *Bild* beginnt und *entriesCount* Einträge enthält.

### Siehe auch

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Liefert die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, um Berechnungen durchzuführen.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | RasterImage | Das Rasterbild. |
| destBounds | Rectangle | Die Begrenzungen des Zielbildes. |
| entriesCount | Int32 | Die gewünschte Anzahl von Einträgen. |
| useImagePalette | Boolean | Falls gesetzt, wird die eigene Bildpalette verwendet, sofern verfügbar. |

### Rückgabewert

Die Farbpalette, die mit den am häufigsten vorkommenden Farben aus dem *Bild* beginnt und *entriesCount* Einträge enthält.

### Siehe auch

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


