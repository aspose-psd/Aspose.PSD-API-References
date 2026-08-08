---
title: "CmykColor"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De CMYK-kleur van de pixel."
type: docs
weight: 17
url: /nl/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

De CMYK-kleur van de pixel.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Maakt een  CmykColor  structuur aan vanuit 32-bit cyaan-, magenta-, geel- en zwartwaarden. |
| [getC()](#getC--) | Haalt de cyaancomponentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Haalt het lege op. |
| [getK()](#getK--) | Haalt de zwartcomponentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getM()](#getM--) | Haalt de magentacomponentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [getY()](#getY--) | Haalt de geelcomponentwaarde op van deze  com.aspose.psd.Color  structuur. |
| [hashCode()](#hashCode--) | De hashcode ophalen. |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur niet is geïnitialiseerd. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | De conversie van CMYKColor naar 32-bit ARGB Color met icc-conversie en standaardprofielen. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | De conversie van 32-bit ARGB naar CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | De conversie van 32-bit ARGB-kleur naar CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | De conversie van CMYKColor naar Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | De conversie van CMYKColor naar Color met icc-conversie. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | De conversie van CMYKColor naar Color met icc-conversie. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | De conversie van CMYKColor naar Color met icc-conversie. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | De conversie van CMYKColor naar Color met icc-conversie. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | De to-waarde. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Maakt een  CmykColor  structuur aan vanuit 32-bit cyaan-, magenta-, geel- en zwartwaarden. Deze methode is verouderd. Gebruik a.u.b. effectievere CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cyaan | int | Het cyaancomponent. Geldige waarden zijn 0 tot en met 255. |
| magenta | int | Het magentacomponent. Geldige waarden zijn 0 tot en met 255. |
| geel | int | Het gele component. Geldige waarden zijn 0 tot en met 255. |
| zwart | int | Het zwarte component. Geldige waarden zijn 0 tot en met 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Haalt de cyaancomponentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De cyaancomponentwaarde van deze  com.aspose.psd.Color .
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


Haalt het lege op.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Haalt de zwartcomponentwaarde op van deze  com.aspose.psd.Color  structuur.

Waarde: De zwartcomponentwaarde van deze  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Haalt de magentacomponentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De magentacomponentwaarde van deze  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Haalt de geelcomponentwaarde op van deze  com.aspose.psd.Color  structuur.

**Returns:**
byte - De geelcomponentwaarde van deze  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


De hashcode ophalen.

**Returns:**
int - De  int .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Haalt een waarde op die aangeeft of deze  com.aspose.psd.Color  structuur niet is geïnitialiseerd.

**Returns:**
boolean - Deze eigenschap retourneert true als deze kleur niet is geïnitialiseerd; anders false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


De conversie van CMYKColor naar 32-bit ARGB Color met icc-conversie en standaardprofielen. Deze methode is verouderd. Gebruik a.u.b. effectievere  CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | De pixels van het CMYKColor-type in CMYK-indeling. |

**Returns:**
int[] - De array van de 32-bit ARGB-kleur.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


De conversie van 32-bit ARGB naar CMYKColor. Deze methode is verouderd. Gebruik a.u.b. effectievere  CmykColorHelper.toCmyk(int) .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argbPixel | int | De pixel van 32-bit ARGB-indeling. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


De conversie van 32-bit ARGB-kleur naar CMYKColor. Deze methode is verouderd. Gebruik a.u.b. effectievere  CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argbPixels | int[] | De pixels van het 32-bits ARGB-formaat. |

**Returns:**
com.aspose.psd.CmykColor[] - De Aspose:Imaging:CmykColor[].
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


De conversie van CMYKColor naar Color. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toArgb(int).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | De pixels van het CMYKColor-type in CMYK-indeling. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toArgb(int[]).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | De pixels van het CMYKColor-type in CMYK-indeling. |

**Returns:**
com.aspose.psd.Color[] - De array van de ARGB-kleuren.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toArgbIcc(int).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | De pixel van het type CMYKColor in CMYK-formaat. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


De conversie van CMYKColor naar Color met icc-conversie. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toArgbIcc(int, Stream, Stream).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | De pixel van het type CMYKColor in CMYK-formaat. |
| cmykIccStream | java.io.InputStream | De stream die een icc cmyk-profiel bevat. |
| rgbIccStream | java.io.InputStream | De stream die het icc rgb-profiel bevat. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


De conversie van CMYKColor naar Color met icc-conversie en standaardprofielen. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | De pixels van het CMYKColor-type in CMYK-indeling. |

**Returns:**
com.aspose.psd.Color[] - De  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


De conversie van CMYKColor naar Color met icc-conversie. Deze methode is verouderd. Gebruik a.u.b. de effectievere CmykColorHelper.toArgbIcc(int[], InputStream, InputStream).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | De pixels van het CMYKColor-type in CMYK-indeling. |
| cmykIccStream | java.io.InputStream | De stream die een icc cmyk-profiel bevat. |
| rgbIccStream | java.io.InputStream | De stream die het icc rgb-profiel bevat. |

**Returns:**
com.aspose.psd.Color[] - De  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


De conversie van CMYKColor naar Color met icc-conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | De pixel van het type CMYKColor in CMYK-formaat. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | De stream die een icc cmyk-profiel bevat. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | De stream die het icc rgb-profiel bevat. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


De conversie van CMYKColor naar Color met icc-conversie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | De pixels van het CMYKColor-type in CMYK-indeling. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | De stream die een icc cmyk-profiel bevat. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | De stream die het icc rgb-profiel bevat. |

**Returns:**
com.aspose.psd.Color[] - De  Aspose.Imaging.Color[] .
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


De to-waarde.

**Returns:**
long - De  long .
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

