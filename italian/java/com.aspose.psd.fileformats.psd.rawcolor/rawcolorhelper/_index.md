---
title: "RawColorHelper"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe Raw Color Helper aiuta a creare RawColor più velocemente usando i metadati di canale predefiniti."
type: docs
weight: 12
url: /it/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class aiuta a creare RawColor più velocemente, usando metadati di canale predefiniti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Crea un colore ARGB a 16 bit per canale. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Crea un colore ARGB a 8 bit per canale. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Crea un colore ARGB a 8 bit per canale da Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Crea un colore CMYK a 16 bit per canale. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Crea un colore CMYK a 8 bit per canale. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


Crea un colore ARGB a 16 bit per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | int | Il valore del componente alfa (0-65535). |
| r | int | Il valore del componente rosso (0-65535). |
| g | int | Il valore del componente verde (0-65535). |
|  | b | int | Il valore del componente blu (0-65535). |

--------------------

I componenti di colore sono impacchettati in un intero a 64 bit nell'ordine: alfa (bit 48-63), rosso (bit 32-47), verde (bit 16-31) e blu (bit 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Crea un colore ARGB a 8 bit per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | byte | Il valore del componente alfa (0-255). |
| r | byte | Il valore del componente rosso (0-255). |
| g | byte | Il valore del componente verde (0-255). |
|  | b | byte | Il valore del componente blu (0-255). |

--------------------

I componenti di colore sono impacchettati in un intero a 32 bit nell'ordine: alfa (bit 24-31), rosso (bit 16-23), verde (bit 8-15) e blu (bit 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Crea un colore ARGB a 8 bit per canale da Drawing.Color

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | Il colore System.Drawing |

--------------------

I componenti di colore sono impacchettati in un intero a 32 bit nell'ordine: alfa (bit 24-31), rosso (bit 16-23), verde (bit 8-15) e blu (bit 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Crea un colore CMYK a 16 bit per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | int | Il valore del componente ciano (0-65535). |
| m | int | Il valore del componente magenta (0-65535). |
| y | int | Il valore del componente giallo (0-65535). |
|  | k | int | Il valore del componente chiave (nero) (0-65535). |

--------------------

I componenti di colore sono impacchettati in un intero a 64 bit nell'ordine: ciano (bit 48-63), magenta (bit 32-47), giallo (bit 16-31) e chiave/nero (bit 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Crea un colore CMYK a 8 bit per canale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | byte | Il valore del componente ciano (0-255). |
| m | byte | Il valore del componente magenta (0-255). |
| y | byte | Il valore del componente giallo (0-255). |
|  | k | byte | Il valore del componente chiave (nero) (0-255). |

--------------------

I componenti di colore sono impacchettati in un intero a 32 bit nell'ordine: ciano (bit 24-31), magenta (bit 16-23), giallo (bit 8-15) e chiave/nero (bit 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

