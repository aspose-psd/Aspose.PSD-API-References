---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Référence de l'API Aspose.PSD pour .NET
description: ColorPaletteHelper méthode. Obtient la palette de couleurs de limage raster palettise limage au cas où limage nen aurait pas. Si la palette existe elle sera utilisée à la place pour effectuer des calculs.
type: docs
weight: 60
url: /fr/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Voir également

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* espace de noms [Aspose.PSD](../../colorpalettehelper/)
* Assemblée [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| destBounds | Rectangle | L'image de destination délimite. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Voir également

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* espace de noms [Aspose.PSD](../../colorpalettehelper/)
* Assemblée [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Obtient la palette de couleurs de l'image raster (palettise l'image) au cas où l'image n'en aurait pas. Si la palette existe, elle sera utilisée à la place pour effectuer des calculs.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| image | RasterImage | L'image tramée. |
| destBounds | Rectangle | L'image de destination délimite. |
| entriesCount | Int32 | Les entrées souhaitées comptent. |
| useImagePalette | Boolean | S'il est défini, il utilisera sa propre palette d'images si disponible |

### Return_Value

La palette de couleurs qui commence par les couleurs les plus fréquentes de la*image* et contient*entriesCount* entrées.

### Voir également

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* espace de noms [Aspose.PSD](../../colorpalettehelper/)
* Assemblée [Aspose.PSD](../../../)


