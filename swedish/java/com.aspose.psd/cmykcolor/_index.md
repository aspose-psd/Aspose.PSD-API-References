---
title: "CmykColor"
second_title: "Aspose.PSD för Java API-referens"
description: "CMYK-färgen för pixeln."
type: docs
weight: 17
url: /sv/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

CMYK-färgen för pixeln.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Skapar en  CmykColor  struktur från 32‑bitars cyan-, magenta-, gul- och svartvärden. |
| [getC()](#getC--) | Hämtar cyan‑komponentvärdet för denna  com.aspose.psd.Color  struktur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Hämtar den tomma. |
| [getK()](#getK--) | Hämtar svart‑komponentvärdet för denna  com.aspose.psd.Color  struktur. |
| [getM()](#getM--) | Hämtar magenta‑komponentvärdet för denna  com.aspose.psd.Color  struktur. |
| [getY()](#getY--) | Hämtar gul‑komponentvärdet för denna  com.aspose.psd.Color  struktur. |
| [hashCode()](#hashCode--) | Den hämtar hash‑koden. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är oinitierad. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | Konverteringen från CMYKColor till 32‑bitars ARGB Color med icc‑konvertering och standardprofiler. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Konverteringen från 32‑bitars ARGB till CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Konverteringen från 32‑bitars ARGB‑färg till CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | Konverteringen från CMYKColor till Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYKColor till Color med icc‑konvertering. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | Konverteringen från CMYKColor till Color med icc‑konvertering och standardprofiler. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYKColor till Color med icc‑konvertering. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konverteringen från CMYKColor till Color med icc‑konvertering. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Konverteringen från CMYKColor till Color med icc‑konvertering. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | Till‑värdet. |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Skapar en  CmykColor  struktur från 32‑bitars cyan-, magenta-, gul- och svartvärden. Denna metod är föråldrad. Använd den mer effektiva CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cyan | int | Cyan-komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Magenta-komponenten. Giltiga värden är 0 till 255. |
| gul | int | Gul-komponenten. Giltiga värden är 0 till 255. |
| svart | int | Svart-komponenten. Giltiga värden är 0 till 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Hämtar cyan‑komponentvärdet för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Cyan‑komponentvärdet för denna  com.aspose.psd.Color .
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


Hämtar den tomma.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Hämtar svart‑komponentvärdet för denna  com.aspose.psd.Color  struktur.

Värde: Svart‑komponentvärdet för denna  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Hämtar magenta‑komponentvärdet för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Magenta‑komponentvärdet för denna  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Hämtar gul‑komponentvärdet för denna  com.aspose.psd.Color  struktur.

**Returns:**
byte - Gul‑komponentvärdet för denna  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Den hämtar hash‑koden.

**Returns:**
int - Den  int .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om denna  com.aspose.psd.Color  struktur är oinitierad.

**Returns:**
boolean - Denna egenskap returnerar true om denna färg är oinitierad; annars false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Konverteringen från CMYKColor till 32‑bitars ARGB Color med icc‑konvertering och standardprofiler. Denna metod är föråldrad. Använd den mer effektiva  CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
int[] - Arrayen av 32‑bitars ARGB‑färgen.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


Konverteringen från 32‑bitars ARGB till CMYKColor. Denna metod är föråldrad. Använd den mer effektiva  CmykColorHelper.toCmyk(int) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixel | int | Pixeln i 32‑bitars ARGB‑format. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


Konverteringen från 32-bitars ARGB-färg till CMYKColor. Denna metod är föråldrad. Använd en mer effektiv  CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | Pixlarna i 32-bitars ARGB-format. |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


Konverteringen från CMYKColor till Color. Denna metod är föråldrad. Använd en mer effektiv  CmykColorHelper.toArgb(int) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler. Denna metod är föråldrad. Använd en mer effektiv  CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
com.aspose.psd.Color[] - Arrayen av ARGB-färgerna.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler. Denna metod är föråldrad. Använd en mer effektiv  CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixeln av typen CMYKColor i CMYK-format. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYKColor till Color med icc-konvertering. Denna metod är föråldrad. Använd en mer effektiv  CmykColorHelper.toArgbIcc(int, Stream, Stream) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixeln av typen CMYKColor i CMYK-format. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller icc cmyk-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller icc rgb-profilen. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


Konverteringen från CMYKColor till Color med icc-konvertering och standardprofiler. Denna metod är föråldrad. Använd en mer effektiv CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |

**Returns:**
com.aspose.psd.Color[] - Den  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYKColor till Color med icc-konvertering. Denna metod är föråldrad. Använd en mer effektiv  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller icc cmyk-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller icc rgb-profilen. |

**Returns:**
com.aspose.psd.Color[] - Den  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Konverteringen från CMYKColor till Color med icc‑konvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Pixeln av typen CMYKColor i CMYK-format. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Strömmen som innehåller icc cmyk-profilen. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Strömmen som innehåller icc rgb-profilen. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


Konverteringen från CMYKColor till Color med icc‑konvertering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Pixlarna av typen CMYKColor i CMYK‑format. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Strömmen som innehåller icc cmyk-profilen. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Strömmen som innehåller icc rgb-profilen. |

**Returns:**
com.aspose.psd.Color[] - Den  Aspose.Imaging.Color[] .
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


Till‑värdet.

**Returns:**
long - Den  long .
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

