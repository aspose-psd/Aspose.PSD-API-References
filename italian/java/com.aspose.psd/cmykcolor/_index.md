---
title: "CmykColor"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il colore CMYK del pixel."
type: docs
weight: 17
url: /it/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

Il colore CMYK del pixel.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Crea una struttura  CmykColor  da valori ciano, magenta, giallo e nero a 32-bit. |
| [getC()](#getC--) | Ottiene il valore del componente ciano di questa  com.aspose.psd.Color  struttura. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Ottiene il vuoto. |
| [getK()](#getK--) | Ottiene il valore del componente nero di questa  com.aspose.psd.Color  struttura. |
| [getM()](#getM--) | Ottiene il valore del componente magenta di questa  com.aspose.psd.Color  struttura. |
| [getY()](#getY--) | Ottiene il valore del componente giallo di questa  com.aspose.psd.Color  struttura. |
| [hashCode()](#hashCode--) | Il get hash code. |
| [isEmpty()](#isEmpty--) | Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è non inizializzata. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | La conversione da CMYKColor a 32-bit ARGB Color usando la conversione icc con profili predefiniti. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | La conversione da 32-bit ARGB a CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | La conversione da colore 32-bit ARGB a CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | La conversione da CMYKColor a Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | La conversione da CMYKColor a Color usando la conversione icc. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | La conversione da CMYKColor a Color usando la conversione icc. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | La conversione da CMYKColor a Color usando la conversione icc. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | La conversione da CMYKColor a Color usando la conversione icc. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | Il valore to. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Crea una struttura  CmykColor  da valori ciano, magenta, giallo e nero a 32-bit. Questo metodo è deprecato. Si prega di utilizzare CmykColorHelper\#fromComponents(int, int, int, int) più efficace.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ciano | int | Il componente ciano. I valori validi sono da 0 a 255. |
| magenta | int | Il componente magenta. I valori validi sono da 0 a 255. |
| giallo | int | Il componente giallo. I valori validi sono da 0 a 255. |
| nero | int | Il componente nero. I valori validi sono da 0 a 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Ottiene il valore del componente ciano di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente ciano di questa  com.aspose.psd.Color .
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


Ottiene il vuoto.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Ottiene il valore del componente nero di questa  com.aspose.psd.Color  struttura.

Valore: Il valore del componente nero di questa  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Ottiene il valore del componente magenta di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente magenta di questa  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Ottiene il valore del componente giallo di questa  com.aspose.psd.Color  struttura.

**Returns:**
byte - Il valore del componente giallo di questa  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Il get hash code.

**Returns:**
int - Il  int .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Restituisce un valore che indica se questa  com.aspose.psd.Color  struttura è non inizializzata.

**Returns:**
boolean - Questa proprietà restituisce true se questo colore non è inizializzato; altrimenti, false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


La conversione da CMYKColor a 32-bit ARGB Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare  CmykColorHelper.toArgb32(int[])  più efficace.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
int[] - L'array del colore 32-bit ARGB.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


La conversione da 32-bit ARGB a CMYKColor. Questo metodo è deprecato. Si prega di utilizzare  CmykColorHelper.toCmyk(int)  più efficace.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixel | int | Il pixel del formato 32-bit ARGB. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


La conversione da colore 32-bit ARGB a CMYKColor. Questo metodo è deprecato. Si prega di utilizzare  CmykColorHelper.toCmyk(int[])  più efficace.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argbPixels | int[] | I pixel del formato ARGB a 32 bit. |

**Returns:**
com.aspose.psd.CmykColor[] - Il  Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


La conversione da CMYKColor a Color. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toArgb(int) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
com.aspose.psd.Color[] - L'array dei colori ARGB.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Il pixel di tipo CMYKColor nel formato CMYK. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da CMYKColor a Color usando la conversione icc. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toArgbIcc(int, Stream, Stream) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Il pixel di tipo CMYKColor nel formato CMYK. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo icc cmyk. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


La conversione da CMYKColor a Color usando la conversione icc con profili predefiniti. Questo metodo è deprecato. Si prega di utilizzare il più efficace CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |

**Returns:**
com.aspose.psd.Color[] - Il  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


La conversione da CMYKColor a Color usando la conversione icc. Questo metodo è deprecato. Si prega di utilizzare il più efficace  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |
| cmykIccStream | java.io.InputStream | Il flusso contenente il profilo icc cmyk. |
| rgbIccStream | java.io.InputStream | Il flusso contenente il profilo icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Il  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


La conversione da CMYKColor a Color usando la conversione icc.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | Il pixel di tipo CMYKColor nel formato CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Il flusso contenente il profilo icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Il flusso contenente il profilo icc rgb. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


La conversione da CMYKColor a Color usando la conversione icc.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | I pixel del tipo CMYKColor in formato CMYK. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | Il flusso contenente il profilo icc cmyk. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | Il flusso contenente il profilo icc rgb. |

**Returns:**
com.aspose.psd.Color[] - Il  Aspose.Imaging.Color[] .
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


Il valore to.

**Returns:**
long - Il  long .
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

