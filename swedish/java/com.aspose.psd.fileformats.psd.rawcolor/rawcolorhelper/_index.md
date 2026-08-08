---
title: "RawColorHelper"
second_title: "Aspose.PSD för Java API-referens"
description: "Raw Color Helper-klass hjälper till att skapa RawColor snabbare med hjälp av fördefinierad kanalmetadata"
type: docs
weight: 12
url: /sv/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class hjälper till att skapa RawColor snabbare, genom att använda fördefinierad kanalmetadata
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Skapar en 16-bitars per kanal ARGB-färg. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Skapar en 8-bitars per kanal ARGB-färg. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Skapar en 8-bitars per kanal ARGB-färg från Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Skapar en 16-bitars per kanal CMYK-färg. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Skapar en 8-bitars per kanal CMYK-färg. |
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


Skapar en 16-bitars per kanal ARGB-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | int | Alfakomponentens värde (0-65535). |
| r | int | Det röda komponentvärdet (0-65535). |
| g | int | Det gröna komponentvärdet (0-65535). |
|  | b | int | Det blåa komponentvärdet (0-65535). |

--------------------

Färgkomponenterna packas in i ett 64-bitars heltal i följande ordning: alfa (bitar 48-63), röd (bitar 32-47), grön (bitar 16-31) och blå (bitar 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Skapar en 8-bitars per kanal ARGB-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | byte | Det alfa komponentvärdet (0-255). |
| r | byte | Det röda komponentvärdet (0-255). |
| g | byte | Det gröna komponentvärdet (0-255). |
|  | b | byte | Det blåa komponentvärdet (0-255). |

--------------------

Färgkomponenterna packas in i ett 32-bitars heltal i följande ordning: alfa (bitar 24-31), röd (bitar 16-23), grön (bitar 8-15) och blå (bitar 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Skapar en 8-bitars per kanal ARGB-färg från Drawing.Color

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | System.Drawing Color |

--------------------

Färgkomponenterna packas in i ett 32-bitars heltal i följande ordning: alfa (bitar 24-31), röd (bitar 16-23), grön (bitar 8-15) och blå (bitar 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Skapar en 16-bitars per kanal CMYK-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | int | Det cyan komponentvärdet (0-65535). |
| m | int | Det magenta komponentvärdet (0-65535). |
| y | int | Det gula komponentvärdet (0-65535). |
|  | k | int | Det nyckel (svart) komponentvärdet (0-65535). |

--------------------

Färgkomponenterna packas in i ett 64-bitars heltal i följande ordning: cyan (bitar 48-63), magenta (bitar 32-47), gul (bitar 16-31) och nyckel/svart (bitar 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Skapar en 8-bitars per kanal CMYK-färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c | byte | Det cyan komponentvärdet (0-255). |
| m | byte | Det magenta komponentvärdet (0-255). |
| y | byte | Det gula komponentvärdet (0-255). |
|  | k | byte | Det nyckel (svart) komponentvärdet (0-255). |

--------------------

Färgkomponenterna packas in i ett 32-bitars heltal i följande ordning: cyan (bitar 24-31), magenta (bitar 16-23), gul (bitar 8-15) och nyckel/svart (bitar 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

