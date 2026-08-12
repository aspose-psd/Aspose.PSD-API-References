---
title: "ColorPaletteHelper.GetCloseImagePalette"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ColorPaletteHelper. Obtiene la paleta de colores de la imagen raster y paletiza la imagen en caso de que no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos."
type: docs
weight: 60
url: /es/net/aspose.psd/colorpalettehelper/getcloseimagepalette/
---
{{< psd/tize >}}
## GetCloseImagePalette(RasterImage, int) {#getcloseimagepalette_2}

Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | RasterImage | La imagen raster. |
| entriesCount | Int32 | El número deseado de entradas. |

### Valor devuelto

La paleta de colores que comienza con los colores más frecuentes de la *imagen* y contiene *entriesCount* entradas.

### Ver también

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int) {#getcloseimagepalette}

Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | RasterImage | La imagen raster. |
| destBounds | Rectangle | Los límites de la imagen de destino. |
| entriesCount | Int32 | El número deseado de entradas. |

### Valor devuelto

La paleta de colores que comienza con los colores más frecuentes de la *imagen* y contiene *entriesCount* entradas.

### Ver también

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetCloseImagePalette(RasterImage, Rectangle, int, bool) {#getcloseimagepalette_1}

Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | RasterImage | La imagen raster. |
| destBounds | Rectangle | Los límites de la imagen de destino. |
| entriesCount | Int32 | El número deseado de entradas. |
| useImagePalette | Boolean | Si está establecido, usará su propia paleta de imagen si está disponible. |

### Valor devuelto

La paleta de colores que comienza con los colores más frecuentes de la *imagen* y contiene *entriesCount* entradas.

### Ver también

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../../rasterimage/)
* struct [Rectangle](../../rectangle/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


