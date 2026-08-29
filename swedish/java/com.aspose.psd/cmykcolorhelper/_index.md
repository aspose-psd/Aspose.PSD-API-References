---
title: "CmykColorHelper"
second_title: "Aspose.PSD för Java API-referens"
description: "Hjälpmetoder för att arbeta med CMYK-färg presenterad som ett signerat 32-bitars heltalsvärde."
type: docs
weight: 18
url: /sv/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Hjälpmetoder för att arbeta med CMYK-färg som presenteras som ett signerat 32-bitars heltal. Tillhandahåller ett liknande API som strukturen  com.aspose.psd.CmykColor . Den är mer lättviktig eftersom CMYK-färgen presenteras bara som Int32 snarare än en struktur med interna fält. Använd gärna de statiska metoderna i denna klass när det är möjligt istället för den föråldrade strukturen  com.aspose.psd.CmykColor .
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden. |
| [getC(int cmyk)](#getC-int-) | Hämtar cyan-komponentens värde. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Hämtar svartkomponentens värde. |
| [getM(int cmyk)](#getM-int-) | Hämtar magentakomponentens värde. |
| [getY(int cmyk)](#getY-int-) | Hämtar gulkomponentens värde. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | Konverteringen från CMYK-färg till ARGB-färg. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Konverteringen från CMYK-färger till ARGB-färger. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Konverteringen från CMYK-färger till ARGB-färger. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Konverteringen från ARGB-färg till CMYK-färg. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Konverteringen från ARGB-färger till CMYK-färger. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Konverteringen från ARGB-färg till CMYK-färg. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Konverteringen från ARGB-färger till CMYK-färger. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Konverterar RGB till CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Konverterar RGB till CMYK med anpassade ICC-profiler. |
| [toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)](#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Skapar CMYK från 32-bitars cyan-, magenta-, gul- och svartvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cyan | int | Cyan-komponenten. Giltiga värden är 0 till 255. |
| magenta | int | Magenta-komponenten. Giltiga värden är 0 till 255. |
| gul | int | Gul-komponenten. Giltiga värden är 0 till 255. |
| svart | int | Svart-komponenten. Giltiga värden är 0 till 255. |

**Returns:**
int - CMYK-färgen presenterad som ett 32-bitars heltalsvärde.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Hämtar cyan-komponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
int - Cyan-komponentens värde.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Hämtar svartkomponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
int - Svart-komponentens värde.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Hämtar magentakomponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
int - Magenta-komponentens värde.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Hämtar gulkomponentens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
int - Gul-komponentens värde.
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




### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


Konverteringen från CMYK-färg till ARGB-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns:**
com.aspose.psd.Color[] - ARGB-färgerna.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Konverteringen från CMYK-färger till ARGB-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns:**
int[] - ARGB-färgerna presenterade som 32-bitars heltalsvärden.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYK-färg till ARGB-färg med Icc-konvertering och anpassad profil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixel | int | CMYK-färgen presenterad som ett 32-bitars heltalsvärde. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-pixlarna presenterade som 32-bitars heltalsvärden. |

**Returns:**
com.aspose.psd.Color[] - ARGB-färgerna.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Konverteringen från CMYK-färger till ARGB-färger med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmykPixels | int[] | CMYK-färgerna presenterade som 32-bitars heltalsvärden. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |

**Returns:**
com.aspose.psd.Color[] - ARGB-färgerna.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


Konverteringen från ARGB-färg till CMYK-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB-färgen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32-bitars heltalsvärde.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB-färgerna. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32-bitars heltalsvärden.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Konverteringen från ARGB-färg till CMYK-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixel | int | ARGB-färgen presenterad som ett 32-bitars heltalsvärde. |

**Returns:**
int - CMYK-färgen presenterad som ett 32-bitars heltalsvärde.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Konverteringen från ARGB-färger till CMYK-färger.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | ARGB-färgerna presenterade som 32-bitars heltalsvärden. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32-bitars heltalsvärden.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Konverterar RGB till CMYK.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argbPixels | int[] | RGB-färgerna presenterade som 32-bitars heltalsvärden. |
| startIndex | int | Startindexet för RGB-färgen. |
| längd | int | Antalet RGB-pixlar att konvertera. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB-färgen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32-bitars heltalsvärde.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färg till CMYK-färg med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB-färgen. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int - CMYK-färgen presenterad som ett 32-bitars heltalsvärde.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och standardprofiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB-färgerna. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32-bitars heltalsvärden.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverteringen från ARGB-färger till CMYK-färger med Icc-konvertering och anpassade profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB-färgerna. |
| rgbIccStream | java.io.InputStream | Strömmen som innehåller RGB Icc-profilen. |
| cmykIccStream | java.io.InputStream | Strömmen som innehåller CMYK Icc-profilen. |

**Returns:**
int[] - CMYK-färgerna presenterade som 32-bitars heltalsvärden.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konverterar RGB till CMYK med anpassade ICC-profiler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] | RGB-färgerna presenterade som 32-bitars heltalsvärden. |
| startIndex | int | Startindexet för RGB-färgen. |
| längd | int | Antalet RGB-pixlar att konvertera. |
| rgbIccStream | java.io.InputStream | RGB-profilströmmen. |
| cmykIccStream | java.io.InputStream | CMYK-profilströmmen. |

**Returns:**
byte[] - CMYK-färgerna presenterade som en byte-array.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixlar | int[] |  |
| startIndex | int |  |
| längd | int |  |
| rgbIccStream | com.aspose.ms.System.IO.Stream |  |
| cmykIccStream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
byte[]
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

