---
title: "ColorPaletteHelper"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Classe d'aide pour la manipulation des palettes de couleurs."
type: docs
weight: 28
url: /fr/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Classe d'aide pour la manipulation des palettes de couleurs.
## Méthodes

| Méthode | Description |
| --- | --- |
| [create4Bit()](#create4Bit--) | Crée la palette de couleurs 4 bits. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Crée la palette de niveaux de gris 4 bits. |
| [create8Bit()](#create8Bit--) | Crée la palette de couleurs 8 bits. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Crée la palette de niveaux de gris 8 bits. |
| [createMonochrome()](#createMonochrome--) | Crée une palette de couleurs monochrome contenant uniquement 2 couleurs. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Obtient une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Obtient une palette uniforme de 256 couleurs. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Détermine si la palette spécifiée possède des couleurs transparentes. |
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


Crée la palette de couleurs 4 bits.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Crée la palette de niveaux de gris 4 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minIsWhite | booléen | si réglé sur  true , la palette commence par la couleur blanche, sinon elle commence par la couleur noire. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Crée la palette de couleurs 8 bits.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Crée la palette de niveaux de gris 8 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minIsWhite | booléen | si réglé sur  true , la palette commence par la couleur blanche, sinon elle commence par la couleur noire. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Crée une palette de couleurs monochrome contenant uniquement 2 couleurs.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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


Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image de destination. |
| entriesCount | int | Le nombre d'entrées souhaité. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image de destination. |
| entriesCount | int | Le nombre d'entrées souhaité. |
| useImagePalette | booléen | Si défini, il utilisera sa propre palette d'images si disponible |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Obtient la palette de couleurs à partir d'une image raster (palettise l'image) au cas où l'image n'en possède pas. Si la palette existe, elle sera utilisée au lieu d'effectuer des calculs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image raster. |
| entriesCount | int | Le nombre d'entrées souhaité. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Obtient une palette de 256 couleurs, composée des bits supérieurs des valeurs de couleur de l'image initiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Obtient une palette uniforme de 256 couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Détermine si la palette spécifiée possède des couleurs transparentes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette. |

**Returns:**
booléen -  true  si la palette spécifiée possède des couleurs transparentes ; sinon,  false .
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

