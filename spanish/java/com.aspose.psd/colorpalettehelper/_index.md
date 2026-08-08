---
title: "ColorPaletteHelper"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase auxiliar para la manipulación de paletas de colores."
type: docs
weight: 28
url: /es/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Clase auxiliar para la manipulación de paletas de colores.
## Métodos

| Método | Descripción |
| --- | --- |
| [create4Bit()](#create4Bit--) | Crea la paleta de colores de 4 bits. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Crea la paleta de escala de grises de 4 bits. |
| [create8Bit()](#create8Bit--) | Crea la paleta de colores de 8 bits. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Crea la paleta de escala de grises de 8 bits. |
| [createMonochrome()](#createMonochrome--) | Crea una paleta de colores monocromática que contiene solo 2 colores. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Obtener paleta de 256 colores, compuesta por los bits superiores de los valores de color de la imagen inicial. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Obtener paleta uniforme de 256 colores. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Determina si la paleta especificada tiene colores transparentes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


Crea la paleta de colores de 4 bits.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Crea la paleta de escala de grises de 4 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minIsWhite | boolean | si se establece en  true  la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Crea la paleta de colores de 8 bits.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Crea la paleta de escala de grises de 8 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minIsWhite | boolean | si se establece en  true  la paleta comienza con color blanco, de lo contrario comienza con color negro. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Crea una paleta de colores monocromática que contiene solo 2 colores.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen de destino. |
| entriesCount | int | El recuento de entradas deseado. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de la imagen de destino. |
| entriesCount | int | El recuento de entradas deseado. |
| useImagePalette | boolean | Si está configurado, usará su propia paleta de imagen si está disponible |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Obtiene la paleta de colores de una imagen raster (paletiza la imagen) en caso de que la imagen no tenga una. Si la paleta existe, se usará en lugar de realizar cálculos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen raster. |
| entriesCount | int | El recuento de entradas deseado. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Obtener paleta de 256 colores, compuesta por los bits superiores de los valores de color de la imagen inicial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Obtener paleta uniforme de 256 colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | La imagen. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Determina si la paleta especificada tiene colores transparentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta. |

**Returns:**
booleano -  true  si la paleta especificada tiene colores transparentes; de lo contrario,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

