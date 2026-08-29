---
title: "RawColorHelper"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Raw Color Helper Class helpt bij het sneller maken van RawColor met behulp van vooraf gedefinieerde kanaalmetadata"
type: docs
weight: 12
url: /nl/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class helpt bij het sneller creëren van RawColor, met gebruik van vooraf gedefinieerde kanaalmetadata
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Maakt een 16-bit per kanaal ARGB-kleur. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Maakt een 8-bit per kanaal ARGB-kleur. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Maakt een 8-bit per kanaal ARGB-kleur van Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Maakt een 16-bit per kanaal CMYK-kleur. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Maakt een 8-bit per kanaal CMYK-kleur. |
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


Maakt een 16-bit per kanaal ARGB-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | int | De alfa-componentwaarde (0-65535). |
| r | int | De rode componentwaarde (0-65535). |
| g | int | De groene componentwaarde (0-65535). |
|  | b | int | De blauwe componentwaarde (0-65535). |

--------------------

De kleurcomponenten worden verpakt in een 64-bit integer in de volgorde: alfa (bits 48-63), rood (bits 32-47), groen (bits 16-31) en blauw (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Maakt een 8-bit per kanaal ARGB-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | byte | De alfa-componentwaarde (0-255). |
| r | byte | De rode componentwaarde (0-255). |
| g | byte | De groene componentwaarde (0-255). |
|  | b | byte | De blauwe componentwaarde (0-255). |

--------------------

De kleurcomponenten worden verpakt in een 32-bit integer in de volgorde: alfa (bits 24-31), rood (bits 16-23), groen (bits 8-15) en blauw (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Maakt een 8-bit per kanaal ARGB-kleur van Drawing.Color

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | De System.Drawing Color |

--------------------

De kleurcomponenten worden verpakt in een 32-bit integer in de volgorde: alfa (bits 24-31), rood (bits 16-23), groen (bits 8-15) en blauw (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Maakt een 16-bit per kanaal CMYK-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | int | De cyaan-componentwaarde (0-65535). |
| m | int | De magentacomponentwaarde (0-65535). |
| y | int | De geelcomponentwaarde (0-65535). |
|  | k | int | De sleutel (zwart) componentwaarde (0-65535). |

--------------------

De kleurcomponenten worden verpakt in een 64-bits geheel getal in de volgorde: cyaan (bits 48-63), magenta (bits 32-47), geel (bits 16-31), en sleutel/zwart (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Maakt een 8-bit per kanaal CMYK-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| c | byte | De cyaancomponentwaarde (0-255). |
| m | byte | De magentacomponentwaarde (0-255). |
| y | byte | De geelcomponentwaarde (0-255). |
|  | k | byte | De sleutel (zwart) componentwaarde (0-255). |

--------------------

De kleurcomponenten worden verpakt in een 32-bits geheel getal in de volgorde: cyaan (bits 24-31), magenta (bits 16-23), geel (bits 8-15), en sleutel/zwart (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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

