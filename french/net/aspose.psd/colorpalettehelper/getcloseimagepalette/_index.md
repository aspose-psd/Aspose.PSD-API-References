---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode ColorPaletteHelper. Obtient la palette de couleurs à partir d'une image raster qui palette l'image si celle‑ci n'en possède pas. Si la palette existe, elle sera utilisée à la place d'effectuer des calculs."
type: docs
weight: 60
url: /fr/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | RasterImage | L'image raster. |
| entriesCount | Int32 | Le nombre d'entrées souhaité. |

### Valeur de retour

La palette de couleurs qui commence par les couleurs les plus fréquentes de l'*image* et contient *entriesCount* entrées.

### Voir aussi

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | RasterImage | L'image raster. |
| destBounds | Rectangle | Les limites de l'image de destination. |
| entriesCount | Int32 | Le nombre d'entrées souhaité. |

### Valeur de retour

La palette de couleurs qui commence par les couleurs les plus fréquentes de l'*image* et contient *entriesCount* entrées.

### Voir aussi

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Obtient la palette de couleurs à partir d'une image raster (palettise l'image) si l'image n'en possède pas. Si une palette existe, elle sera utilisée au lieu d'effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| image | RasterImage | L'image raster. |
| destBounds | Rectangle | Les limites de l'image de destination. |
| entriesCount | Int32 | Le nombre d'entrées souhaité. |
| useImagePalette | Booléen | Si défini, il utilisera sa propre palette d'image si disponible |

### Valeur de retour

La palette de couleurs qui commence par les couleurs les plus fréquentes de l'*image* et contient *entriesCount* entrées.

### Voir aussi

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


