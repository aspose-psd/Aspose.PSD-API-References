---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD för Java API-referens"
description: "Hjälparklass för manipulation av färgpaletter."
type: docs
weight: 28
url: /sv/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Hjälparklass för manipulation av färgpaletter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create4Bit()](#create4Bit--) | Skapar 4-bitars färgpaletten. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Skapar 4-bitars gråskalepaletten. |
| [create8Bit()](#create8Bit--) | Skapar 8-bitars färgpaletten. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Skapar 8‑bit gråskalepaletten. |
| [createMonochrome()](#createMonochrome--) | Skapar en monokrom färgpalett som endast innehåller 2 färger. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Hämta 256‑färgers palett, sammansatt av de övre bitarna i den ursprungliga bildens färgvärden. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Hämta enhetlig 256‑färgers palett. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Bestämmer om den angivna paletten har transparenta färger. |
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


Skapar 4-bitars färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Skapar 4-bitars gråskalepaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minIsWhite | boolean | Om den är inställd på  true  startar paletten med vit färg, annars startar den med svart färg. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Skapar 8-bitars färgpaletten.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Skapar 8‑bit gråskalepaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minIsWhite | boolean | Om den är inställd på  true  startar paletten med vit färg, annars startar den med svart färg. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Skapar en monokrom färgpalett som endast innehåller 2 färger.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Rasterbilden. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas gränser. |
| entriesCount | int | Det önskade antalet poster. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Rasterbilden. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Målbildernas gränser. |
| entriesCount | int | Det önskade antalet poster. |
| useImagePalette | boolean | Om den är inställd, kommer den att använda sin egen bildpalett om den finns tillgänglig |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Hämtar färgpalett från rasterbild (palettiserar bilden) om bilden inte har någon. Om en palett redan finns kommer den att användas istället för att utföra beräkningar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Rasterbilden. |
| entriesCount | int | Det önskade antalet poster. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Hämta 256‑färgers palett, sammansatt av de övre bitarna i den ursprungliga bildens färgvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Hämta enhetlig 256‑färgers palett.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Bilden. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Bestämmer om den angivna paletten har transparenta färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Paletten. |

**Returns:**
boolesk -  true  om den angivna paletten har transparenta färger; annars,  false .
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

