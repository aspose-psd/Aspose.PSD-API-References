---
title: "ColorPaletteHelper"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe di supporto per la manipolazione delle tavolozze di colori."
type: docs
weight: 28
url: /it/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Classe di supporto per la manipolazione delle tavolozze di colori.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create4Bit()](#create4Bit--) | Crea la palette di colori a 4 bit. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Crea la palette in scala di grigi a 4 bit. |
| [create8Bit()](#create8Bit--) | Crea la palette di colori a 8 bit. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Crea la palette in scala di grigi a 8 bit. |
| [createMonochrome()](#createMonochrome--) | Crea una palette di colori monocromatica contenente solo 2 colori. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Ottiene la palette di colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Ottiene la palette di colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Ottiene la palette di colori da un'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Ottieni una palette di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Ottieni una palette uniforme di 256 colori. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Determina se la palette specificata contiene colori trasparenti. |
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


Crea la palette di colori a 4 bit.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Crea la palette in scala di grigi a 4 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minIsWhite | boolean | se impostato su  true  la palette inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Crea la palette di colori a 8 bit.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Crea la palette in scala di grigi a 8 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minIsWhite | boolean | se impostato su  true  la palette inizia con il colore bianco, altrimenti inizia con il colore nero. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Crea una palette di colori monocromatica contenente solo 2 colori.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Ottiene la palette di colori dall'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la palette esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine di destinazione. |
| entriesCount | int | Il numero desiderato di voci. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Ottiene la palette di colori dall'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la palette esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine raster. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | I limiti dell'immagine di destinazione. |
| entriesCount | int | Il numero desiderato di voci. |
| useImagePalette | boolean | Se impostato, utilizzerà la propria palette dell'immagine se disponibile |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Ottiene la palette di colori dall'immagine raster (palletizza l'immagine) nel caso in cui l'immagine non ne abbia una. Se la palette esiste, verrà utilizzata invece di eseguire i calcoli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine raster. |
| entriesCount | int | Il numero desiderato di voci. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Ottieni una palette di 256 colori, composta dai bit più alti dei valori di colore dell'immagine iniziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Ottieni una palette uniforme di 256 colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'immagine. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Determina se la palette specificata contiene colori trasparenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza. |

**Returns:**
boolean -  true  se la palette specificata ha colori trasparenti; altrimenti,  false .
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

