---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Helperklasse voor manipulatie van kleurenpaletten."
type: docs
weight: 28
url: /nl/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Helperklasse voor manipulatie van kleurenpaletten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create4Bit()](#create4Bit--) | Maakt het 4 bit kleurenpalet. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Maakt het 4 bit grijstintenpalet. |
| [create8Bit()](#create8Bit--) | Maakt het 8 bit kleurenpalet. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Maakt het 8 bit grijstintenpalet. |
| [createMonochrome()](#createMonochrome--) | Maakt een monochroom kleurenpalet dat slechts 2 kleuren bevat. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert de afbeelding) voor het geval de afbeelding er geen heeft. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert de afbeelding) voor het geval de afbeelding er geen heeft. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Haalt het kleurenpalet op uit een rasterafbeelding (paletiseert de afbeelding) voor het geval de afbeelding er geen heeft. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Haal een 256-kleurenpalet op, samengesteld uit de hogere bits van de oorspronkelijke afbeeldingskleurwaarden. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Haal een uniform 256-kleurenpalet op. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Bepaalt of het opgegeven palet transparante kleuren bevat. |
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


Maakt het 4 bit kleurenpalet.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Maakt het 4 bit grijstintenpalet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| minIsWhite | boolean | indien ingesteld op  true  begint het palet met witte kleur, anders begint het met zwarte kleur. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Maakt het 8 bit kleurenpalet.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Maakt het 8 bit grijstintenpalet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| minIsWhite | boolean | indien ingesteld op  true  begint het palet met witte kleur, anders begint het met zwarte kleur. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Maakt een monochroom kleurenpalet dat slechts 2 kleuren bevat.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt het kleurenpalet op uit rasterafbeelding (palettiseert afbeelding) als de afbeelding er geen heeft. Als het palet bestaat, wordt het gebruikt in plaats van berekeningen uit te voeren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De rasterafbeelding. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | De grenzen van de doelafbeelding. |
| entriesCount | int | Het gewenste aantal vermeldingen. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Haalt het kleurenpalet op uit rasterafbeelding (palettiseert afbeelding) als de afbeelding er geen heeft. Als het palet bestaat, wordt het gebruikt in plaats van berekeningen uit te voeren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De rasterafbeelding. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | De grenzen van de doelafbeelding. |
| entriesCount | int | Het gewenste aantal vermeldingen. |
| useImagePalette | boolean | Indien ingesteld, zal het zijn eigen afbeeldingspalet gebruiken indien beschikbaar |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Haalt het kleurenpalet op uit rasterafbeelding (palettiseert afbeelding) als de afbeelding er geen heeft. Als het palet bestaat, wordt het gebruikt in plaats van berekeningen uit te voeren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De rasterafbeelding. |
| entriesCount | int | Het gewenste aantal vermeldingen. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Haal een 256-kleurenpalet op, samengesteld uit de hogere bits van de oorspronkelijke afbeeldingskleurwaarden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Haal een uniform 256-kleurenpalet op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | De afbeelding. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Bepaalt of het opgegeven palet transparante kleuren bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het palet. |

**Returns:**
boolean -  true  als het opgegeven palet transparante kleuren bevat; anders,  false .
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

