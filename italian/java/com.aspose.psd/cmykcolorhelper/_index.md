---
title: "CmykColorHelper"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno."
type: docs
weight: 18
url: /it/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno. Fornisce un'API simile a quella della struct  com.aspose.psd.CmykColor . È più leggero perché il colore CMYK è rappresentato semplicemente come Int32 anziché come una struttura con campi interni. Si consiglia di utilizzare i metodi statici di questa classe quando possibile invece della struct deprecata  com.aspose.psd.CmykColor .
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Crea un CMYK a partire da valori a 32 bit di ciano, magenta, giallo e nero. |
| [getC(int cmyk)](#getC-int-) | Restituisce il valore del componente ciano. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Restituisce il valore del componente nero. |
| [getM(int cmyk)](#getM-int-) | Restituisce il valore del componente magenta. |
| [getY(int cmyk)](#getY-int-) | Restituisce il valore del componente giallo. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | La conversione dal colore CMYK al colore ARGB. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | La conversione da colori CMYK a colori ARGB. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | La conversione da colori CMYK a colori ARGB. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | La conversione da colore CMYK a colore ARGB usando la conversione Icc con profili predefiniti. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | La conversione da colore CMYK a colore ARGB usando la conversione Icc con profilo personalizzato. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | La conversione da colore ARGB a colore CMYK. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | La conversione da colori ARGB a colori CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversione da colore ARGB a colore CMYK. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversione da colori ARGB a colori CMYK. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Converte RGB in CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Converte RGB in CMYK usando profili ICC personalizzati. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Crea un CMYK a partire da valori a 32 bit di ciano, magenta, giallo e nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ciano | int | Il componente ciano. I valori validi sono da 0 a 255. |
| magenta | int | Il componente magenta. I valori validi sono da 0 a 255. |
| giallo | int | Il componente giallo. I valori validi sono da 0 a 255. |
| nero | int | Il componente nero. I valori validi sono da 0 a 255. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Restituisce il valore del componente ciano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente ciano.
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


Restituisce il valore del componente nero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente nero.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Restituisce il valore del componente magenta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente magenta.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Restituisce il valore del componente giallo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmyk | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
int - Il valore del componente giallo.
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


La conversione dal colore CMYK al colore ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


La conversione da colori CMYK a colori ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns:**
com.aspose.psd.Color[] - I colori ARGB.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


La conversione da colori CMYK a colori ARGB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |

**Returns:**
int[] - I colori ARGB presentati come valori interi a 32 bit.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


La conversione da colore CMYK a colore ARGB usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | int | Il colore CMYK presentato come valore intero a 32 bit. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da colore CMYK a colore ARGB usando la conversione Icc con profilo personalizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | int | Il colore CMYK presentato come valore intero a 32 bit. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo CMYK Icc. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo RGB Icc. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

**Returns:**
com.aspose.psd.Color[] - I colori ARGB.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da colori CMYK a colori ARGB usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | int[] | I colori CMYK presentati come valori interi a 32 bit. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo CMYK Icc. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo RGB Icc. |

**Returns:**
com.aspose.psd.Color[] - I colori ARGB.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


La conversione da colore ARGB a colore CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Il colore ARGB. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


La conversione da colori ARGB a colori CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I colori ARGB. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


La conversione da colore ARGB a colore CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixel | int | Il colore ARGB presentato come valore intero a 32 bit. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


La conversione da colori ARGB a colori CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I colori ARGB presentati come valori interi a 32 bit. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Converte RGB in CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice iniziale del colore RGB. |
| lunghezza | int | Il numero di pixel RGB da convertire. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Il colore ARGB. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colore ARGB a colore CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Il colore ARGB. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo RGB Icc. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo CMYK Icc. |

**Returns:**
int - Il colore CMYK presentato come valore intero a 32 bit.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili predefiniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I colori ARGB. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


La conversione da colori ARGB a colori CMYK usando la conversione Icc con profili personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | I colori ARGB. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo RGB Icc. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo CMYK Icc. |

**Returns:**
int[] - I colori CMYK presentati come valori interi a 32 bit.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converte RGB in CMYK usando profili ICC personalizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] | I colori RGB presentati come valori interi a 32 bit. |
| startIndex | int | L'indice iniziale del colore RGB. |
| lunghezza | int | Il numero di pixel RGB da convertire. |
| rgbIccStream | java.io.InputStream | Il flusso del profilo RGB. |
| cmykIccStream | java.io.InputStream | Il flusso del profilo CMYK. |

**Returns:**
byte[] - I colori CMYK presentati come array di byte.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixel | int[] |  |
| startIndex | int |  |
| lunghezza | int |  |
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

