---
title: "RawColorHelper"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Raw Color Helper Class hilft, RawColor schneller zu erstellen, indem vordefinierte Kanal-Metadaten verwendet werden"
type: docs
weight: 12
url: /de/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Die Raw-Color-Hilfsklasse hilft, RawColor schneller zu erstellen, indem vordefinierte Kanal-Metadaten verwendet werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Erstellt eine 16-Bit-pro-Kanal ARGB-Farbe. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Erstellt eine 8-Bit-pro-Kanal ARGB-Farbe. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Erstellt eine 8-Bit-pro-Kanal ARGB-Farbe aus Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Erstellt eine 16-Bit-pro-Kanal CMYK-Farbe. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Erstellt eine 8‑Bit‑pro‑Kanal‑CMYK‑Farbe. |
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


Erstellt eine 16-Bit-pro-Kanal ARGB-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | int | Der Alphakomponentenwert (0‑65535). |
| r | int | Der Rotkomponentenwert (0‑65535). |
| g | int | Der Grünkomponentenwert (0‑65535). |
|  | b | int | Der Blaukomponentenwert (0‑65535). |

--------------------

Die Farbkomponenten werden in einem 64‑Bit‑Integer in folgender Reihenfolge gepackt: Alpha (Bits 48‑63), Rot (Bits 32‑47), Grün (Bits 16‑31) und Blau (Bits 0‑15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Erstellt eine 8-Bit-pro-Kanal ARGB-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | byte | Der Alphakomponentenwert (0‑255). |
| r | byte | Der Rotkomponentenwert (0‑255). |
| g | byte | Der Grünkomponentenwert (0‑255). |
|  | b | byte | Der Blaukomponentenwert (0‑255). |

--------------------

Die Farbkomponenten werden in einem 32‑Bit‑Integer in folgender Reihenfolge gepackt: Alpha (Bits 24‑31), Rot (Bits 16‑23), Grün (Bits 8‑15) und Blau (Bits 0‑7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Erstellt eine 8-Bit-pro-Kanal ARGB-Farbe aus Drawing.Color

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | Das System.Drawing Color |

--------------------

Die Farbkomponenten werden in einem 32‑Bit‑Integer in folgender Reihenfolge gepackt: Alpha (Bits 24‑31), Rot (Bits 16‑23), Grün (Bits 8‑15) und Blau (Bits 0‑7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Erstellt eine 16-Bit-pro-Kanal CMYK-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | int | Der Cyan‑Komponentenwert (0‑65535). |
| m | int | Der Magenta‑Komponentenwert (0‑65535). |
| y | int | Der Gelb‑Komponentenwert (0‑65535). |
|  | k | int | Der Schlüssel‑(Schwarz)‑Komponentenwert (0‑65535). |

--------------------

Die Farbkomponenten werden in einem 64‑Bit‑Integer in folgender Reihenfolge gepackt: Cyan (Bits 48‑63), Magenta (Bits 32‑47), Gelb (Bits 16‑31) und Schlüssel/Schwarz (Bits 0‑15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Erstellt eine 8‑Bit‑pro‑Kanal‑CMYK‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c | byte | Der Cyan‑Komponentenwert (0‑255). |
| m | byte | Der Magenta‑Komponentenwert (0‑255). |
| y | byte | Der Gelb‑Komponentenwert (0‑255). |
|  | k | byte | Der Schlüssel‑(Schwarz)‑Komponentenwert (0‑255). |

--------------------

Die Farbkomponenten werden in einen 32-bit Integer gepackt in der Reihenfolge: cyan (Bits 24-31), magenta (Bits 16-23), yellow (Bits 8-15) und key/black (Bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

