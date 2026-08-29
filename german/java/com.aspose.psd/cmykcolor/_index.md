---
title: "CmykColor"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die CMYK-Farbe des Pixels."
type: docs
weight: 17
url: /de/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Die CMYK-Farbe des Pixels.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Erstellt eine  CmykColor  Struktur aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| [getC()](#getC--) | Liefert den Cyan‑Komponentenwert dieser com.aspose.psd.Color-Struktur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Liefert das Leere. |
| [getK()](#getK--) | Liefert den Schwarz‑Komponentenwert dieser com.aspose.psd.Color-Struktur. |
| [getM()](#getM--) | Liefert den Magenta‑Komponentenwert dieser com.aspose.psd.Color-Struktur. |
| [getY()](#getY--) | Liefert den Gelb‑Komponentenwert dieser com.aspose.psd.Color-Struktur. |
| [hashCode()](#hashCode--) | Der Hashcode wird abgerufen. |
| [isEmpty()](#isEmpty--) | Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur nicht initialisiert ist. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | Die Konvertierung von CMYKColor zu 32‑Bit‑ARGB‑Farbe mittels ICC‑Konvertierung mit Standardprofilen. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Die Konvertierung von 32‑Bit‑ARGB zu CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Die Konvertierung von 32‑Bit‑ARGB‑Farbe zu CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | Die Konvertierung von CMYKColor zu Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung mit Standardprofilen. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung mit Standardprofilen. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung mit Standardprofilen. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | Der Zielwert. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Erstellt eine  CmykColor  Struktur aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cyan | int | Die Cyan-Komponente. Gültige Werte sind 0 bis 255. |
| magenta | int | Die Magenta-Komponente. Gültige Werte sind 0 bis 255. |
| gelb | int | Die Gelb-Komponente. Gültige Werte sind 0 bis 255. |
| schwarz | int | Die Schwarz-Komponente. Gültige Werte sind 0 bis 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Liefert den Cyan‑Komponentenwert dieser com.aspose.psd.Color-Struktur.

**Returns:**
byte - Der Cyan‑Komponentenwert dieses  com.aspose.psd.Color .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


Liefert das Leere.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Liefert den Schwarz‑Komponentenwert dieser com.aspose.psd.Color-Struktur.

Wert: Der Schwarz‑Komponentenwert dieses  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Liefert den Magenta‑Komponentenwert dieser com.aspose.psd.Color-Struktur.

**Returns:**
byte - Der Magenta‑Komponentenwert dieses  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Liefert den Gelb‑Komponentenwert dieser com.aspose.psd.Color-Struktur.

**Returns:**
byte - Der Gelb‑Komponentenwert dieses  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Der Hashcode wird abgerufen.

**Returns:**
int - Der int.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Liefert einen Wert, der angibt, ob diese  com.aspose.psd.Color  Struktur nicht initialisiert ist.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn diese Farbe nicht initialisiert ist; andernfalls false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.psd.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


Die Konvertierung von CMYKColor zu 32‑Bit‑ARGB‑Farbe mittels ICC‑Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK‑Format. |

**Returns:**
int[] - Das Array der 32‑Bit‑ARGB‑Farbe.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Die Konvertierung von 32‑Bit‑ARGB zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper.toCmyk(int) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixel | int | Der Pixel des 32‑Bit‑ARGB‑Formats. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Die Konvertierung von 32‑Bit‑ARGB‑Farbe zu CMYKColor. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die Pixel des 32‑Bit‑ARGB‑Formats. |

**Returns:**
com.aspose.psd.CmykColor[] - Die Aspose:Imaging:CmykColor[].
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Die Konvertierung von CMYKColor zu Color. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toArgb(int) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK‑Format. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK‑Format. |

**Returns:**
com.aspose.psd.Color[] - Das Array der ARGB‑Farben.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Der Pixel vom Typ CMYKColor im CMYK‑Format. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toArgbIcc(int, Stream, Stream) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Der Pixel vom Typ CMYKColor im CMYK‑Format. |
| cmykIccStream | java.io.InputStream | Der Stream, der das ICC-CMYK-Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das ICC-RGB-Profil enthält. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung mit Standardprofilen. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK‑Format. |

**Returns:**
com.aspose.psd.Color[] - Das  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Konvertierung von CMYKColor zu Color mittels ICC-Konvertierung. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK‑Format. |
| cmykIccStream | java.io.InputStream | Der Stream, der das ICC-CMYK-Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das ICC-RGB-Profil enthält. |

**Returns:**
com.aspose.psd.Color[] - Das  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Der Pixel vom Typ CMYKColor im CMYK‑Format. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Der Stream, der das ICC-CMYK-Profil enthält. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Der Stream, der das ICC-RGB-Profil enthält. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Die Konvertierung von CMYKColor zu Color mittels ICC‑Konvertierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Die Pixel des Typs CMYKColor im CMYK‑Format. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Der Stream, der das ICC-CMYK-Profil enthält. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Der Stream, der das ICC-RGB-Profil enthält. |

**Returns:**
com.aspose.psd.Color[] - Das  Aspose.Imaging.Color[] .
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toValue() {#toValue--}
```
public long toValue()
```


Der Zielwert.

**Returns:**
long - Das  long .
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

