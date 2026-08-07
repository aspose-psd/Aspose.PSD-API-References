---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Hilfsklasse zur Manipulation von Farbpaletten."
type: docs
weight: 28
url: /de/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

Hilfsklasse zur Manipulation von Farbpaletten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [create4Bit()](#create4Bit--) | Erstellt die 4‑Bit‑Farbpalette. |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | Erstellt die 4‑Bit‑Graustufen‑Palette. |
| [create8Bit()](#create8Bit--) | Erstellt die 8‑Bit‑Farbpalette. |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | Erstellt die 8‑Bit‑Graustufenpalette. |
| [createMonochrome()](#createMonochrome--) | Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | Erhalte eine 256‑Farben‑Palette, zusammengesetzt aus den oberen Bits der ursprünglichen Bildfarbwerte. |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | Erhalte eine einheitliche 256‑Farben‑Palette. |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | Bestimmt, ob die angegebene Palette transparente Farben enthält. |
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


Erstellt die 4‑Bit‑Farbpalette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


Erstellt die 4‑Bit‑Graustufen‑Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minIsWhite | boolean | Wenn auf  true  gesetzt, beginnt die Palette mit weißer Farbe, andernfalls beginnt sie mit schwarzer Farbe. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


Erstellt die 8‑Bit‑Farbpalette.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


Erstellt die 8‑Bit‑Graustufenpalette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| minIsWhite | boolean | Wenn auf  true  gesetzt, beginnt die Palette mit weißer Farbe, andernfalls beginnt sie mit schwarzer Farbe. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


Erstellt eine monochrome Farbpalette, die nur 2 Farben enthält.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
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


Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Rasterbild. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen des Zielbildes. |
| entriesCount | int | Die gewünschte Anzahl von Einträgen. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Rasterbild. |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | Die Grenzen des Zielbildes. |
| entriesCount | int | Die gewünschte Anzahl von Einträgen. |
| useImagePalette | boolean | Wenn gesetzt, verwendet es seine eigene Bildpalette, falls verfügbar. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


Liest die Farbpalette aus einem Rasterbild (palettisiert das Bild), falls das Bild keine hat. Falls eine Palette existiert, wird sie stattdessen verwendet, anstatt Berechnungen durchzuführen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Rasterbild. |
| entriesCount | int | Die gewünschte Anzahl von Einträgen. |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


Erhalte eine 256‑Farben‑Palette, zusammengesetzt aus den oberen Bits der ursprünglichen Bildfarbwerte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


Erhalte eine einheitliche 256‑Farben‑Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Das Bild. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


Bestimmt, ob die angegebene Palette transparente Farben enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Palette. |

**Returns:**
boolescher Wert –  true  wenn die angegebene Palette transparente Farben enthält; andernfalls  false .
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

