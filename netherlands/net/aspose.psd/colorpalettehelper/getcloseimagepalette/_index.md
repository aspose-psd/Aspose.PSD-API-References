---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD voor .NET API-referentie
description: ColorPaletteHelper methode. Haalt kleurenpalet op van rasterafbeelding palletiseert afbeelding voor het geval de afbeelding er geen heeft. Als er een palet bestaat wordt het gebruikt in plaats van berekeningen uit te voeren.
type: docs
weight: 60
url: /nl/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Haalt kleurenpalet op van rasterafbeelding (palletiseert afbeelding) voor het geval de afbeelding er geen heeft. Als er een palet bestaat, wordt het gebruikt in plaats van berekeningen uit te voeren.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | RasterImage | De rasterafbeelding. |
| entriesCount | Int32 | De gewenste inzendingen tellen. |

### Winstwaarde

Het kleurenpalet dat begint met de meest voorkomende kleuren uit de*image* en bevat*entriesCount* inzendingen.

### Zie ook

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* naamruimte [Aspose.PSD](../../colorpalettehelper/)
* montage [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Haalt kleurenpalet op van rasterafbeelding (palletiseert afbeelding) voor het geval de afbeelding er geen heeft. Als er een palet bestaat, wordt het gebruikt in plaats van berekeningen uit te voeren.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | RasterImage | De rasterafbeelding. |
| destBounds | Rectangle | De grenzen van het bestemmingsbeeld. |
| entriesCount | Int32 | De gewenste inzendingen tellen. |

### Winstwaarde

Het kleurenpalet dat begint met de meest voorkomende kleuren uit de*image* en bevat*entriesCount* inzendingen.

### Zie ook

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* naamruimte [Aspose.PSD](../../colorpalettehelper/)
* montage [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Haalt kleurenpalet op van rasterafbeelding (palletiseert afbeelding) voor het geval de afbeelding er geen heeft. Als er een palet bestaat, wordt het gebruikt in plaats van berekeningen uit te voeren.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | RasterImage | De rasterafbeelding. |
| destBounds | Rectangle | De grenzen van het bestemmingsbeeld. |
| entriesCount | Int32 | De gewenste inzendingen tellen. |
| useImagePalette | Boolean | Indien ingesteld, zal het zijn eigen afbeeldingspalet gebruiken, indien beschikbaar |

### Winstwaarde

Het kleurenpalet dat begint met de meest voorkomende kleuren uit de*image* en bevat*entriesCount* inzendingen.

### Zie ook

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* naamruimte [Aspose.PSD](../../colorpalettehelper/)
* montage [Aspose.PSD](../../../)


