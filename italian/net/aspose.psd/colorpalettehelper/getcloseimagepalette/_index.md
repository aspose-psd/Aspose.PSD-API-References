---
title: ColorPaletteHelper.GetCloseImagePalette
second_title: Aspose.PSD per riferimento API .NET
description: ColorPaletteHelper metodo. Ottiene la tavolozza dei colori dallimmagine raster palettizza limmagine nel caso in cui limmagine non ne abbia una. Nel caso in cui la tavolozza esista verrà utilizzata al posto dellesecuzione dei calcoli.
type: docs
weight: 60
url: /it/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Ottiene la tavolozza dei colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso in cui la tavolozza esista, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| entriesCount | Int32 | Le voci desiderate contano. |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti dal*image* e contiene*entriesCount* voci.

### Guarda anche

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* spazio dei nomi [Aspose.PSD](../../colorpalettehelper/)
* assemblea [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Ottiene la tavolozza dei colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso in cui la tavolozza esista, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| destBounds | Rectangle | I limiti dell'immagine di destinazione. |
| entriesCount | Int32 | Le voci desiderate contano. |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti dal*image* e contiene*entriesCount* voci.

### Guarda anche

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* spazio dei nomi [Aspose.PSD](../../colorpalettehelper/)
* assemblea [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Ottiene la tavolozza dei colori dall'immagine raster (palettizza l'immagine) nel caso in cui l'immagine non ne abbia una. Nel caso in cui la tavolozza esista, verrà utilizzata al posto dell'esecuzione dei calcoli.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | RasterImage | L'immagine raster. |
| destBounds | Rectangle | I limiti dell'immagine di destinazione. |
| entriesCount | Int32 | Le voci desiderate contano. |
| useImagePalette | Boolean | Se impostato, utilizzerà la propria tavolozza immagine, se disponibile |

### Valore di ritorno

La tavolozza dei colori che inizia con i colori più frequenti dal*image* e contiene*entriesCount* voci.

### Guarda anche

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* spazio dei nomi [Aspose.PSD](../../colorpalettehelper/)
* assemblea [Aspose.PSD](../../../)


