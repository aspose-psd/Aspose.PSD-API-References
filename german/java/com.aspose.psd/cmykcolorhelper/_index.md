---
title: "CmykColorHelper"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Hilfsmethoden zur Arbeit mit CMYK-Farbe, dargestellt als vorzeichenbehafteter 32‑Bit‑Integerwert."
type: docs
weight: 18
url: /de/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Hilfsmethoden zur Arbeit mit CMYK-Farben, die als vorzeichenbehafteter 32‑Bit‑Integerwert dargestellt werden. Bietet eine ähnliche API wie die Struktur com.aspose.psd.CmykColor. Sie ist leichter, weil die CMYK‑Farbe nur als Int32 und nicht als Struktur mit internen Feldern dargestellt wird. Bitte bevorzugen Sie nach Möglichkeit die statischen Methoden dieser Klasse anstelle der veralteten Struktur com.aspose.psd.CmykColor.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten. |
| [getC(int cmyk)](#getC-int-) | Liefert den Cyan‑Komponentenwert. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Liefert den Schwarz‑Komponentenwert. |
| [getM(int cmyk)](#getM-int-) | Liefert den Magenta‑Komponentenwert. |
| [getY(int cmyk)](#getY-int-) | Liefert den Gelb‑Komponentenwert. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | Die Umwandlung von CMYK‑Farbe zu ARGB‑Farbe. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | Die Umwandlung von CMYK‑Farben zu ARGB‑Farben. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | Die Umwandlung von CMYK‑Farben zu ARGB‑Farben. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | Die Umwandlung von CMYK‑Farbe zu ARGB‑Farbe mittels ICC‑Konvertierung mit Standardprofilen. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | Die Umwandlung von CMYK‑Farbe zu ARGB‑Farbe mittels ICC‑Konvertierung mit benutzerdefiniertem Profil. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | Die Umwandlung von CMYK‑Farben zu ARGB‑Farben mittels ICC‑Konvertierung mit Standardprofilen. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Konvertiert RGB zu CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile. |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Erstellt CMYK aus 32‑Bit‑Cyan-, Magenta-, Gelb- und Schwarzwerten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cyan | int | Die Cyan-Komponente. Gültige Werte sind 0 bis 255. |
| magenta | int | Die Magenta-Komponente. Gültige Werte sind 0 bis 255. |
| gelb | int | Die Gelb-Komponente. Gültige Werte sind 0 bis 255. |
| schwarz | int | Die Schwarz-Komponente. Gültige Werte sind 0 bis 255. |

**Returns:**
int - Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Liefert den Cyan‑Komponentenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |

**Returns:**
int - Der Cyan-Komponentenwert.
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


Liefert den Schwarz‑Komponentenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |

**Returns:**
int - Der Schwarz-Komponentenwert.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Liefert den Magenta‑Komponentenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |

**Returns:**
int - Der Magenta-Komponentenwert.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Liefert den Gelb‑Komponentenwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |

**Returns:**
int - Der Gelb-Komponentenwert.
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


Die Umwandlung von CMYK‑Farbe zu ARGB‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


Die Umwandlung von CMYK‑Farben zu ARGB‑Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben dargestellt als 32-bit-Ganzzahlwerte. |

**Returns:**
com.aspose.psd.Color[] - Die ARGB-Farben.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


Die Umwandlung von CMYK‑Farben zu ARGB‑Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben dargestellt als 32-bit-Ganzzahlwerte. |

**Returns:**
int[] - Die ARGB-Farben dargestellt als 32-bit-Ganzzahlwerte.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


Die Umwandlung von CMYK‑Farbe zu ARGB‑Farbe mittels ICC‑Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Umwandlung von CMYK‑Farbe zu ARGB‑Farbe mittels ICC‑Konvertierung mit benutzerdefiniertem Profil.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixel | int | Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK‑Icc‑Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB‑Icc‑Profil enthält. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


Die Umwandlung von CMYK‑Farben zu ARGB‑Farben mittels ICC‑Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns:**
com.aspose.psd.Color[] - Die ARGB-Farben.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


Die Umwandlung von CMYK-Farben zu ARGB-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmykPixels | int[] | Die CMYK-Farben dargestellt als 32-bit-Ganzzahlwerte. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK‑Icc‑Profil enthält. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB‑Icc‑Profil enthält. |

**Returns:**
com.aspose.psd.Color[] - Die ARGB-Farben.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Die ARGB‑Farbe. |

**Returns:**
int - Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die ARGB‑Farben. |

**Returns:**
int[] – Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixel | int | Die ARGB‑Farbe, dargestellt als 32‑Bit‑Ganzzahlwert. |

**Returns:**
int - Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die ARGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |

**Returns:**
int[] – Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Konvertiert RGB zu CMYK.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argbPixels | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |

**Returns:**
byte[] – Die CMYK‑Farben, dargestellt als Byte‑Array.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Die ARGB‑Farbe. |

**Returns:**
int - Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farbe zu CMYK-Farbe mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | Die ARGB‑Farbe. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB‑Icc‑Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK‑Icc‑Profil enthält. |

**Returns:**
int - Die CMYK-Farbe dargestellt als 32-bit-Ganzzahlwert.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit Standardprofilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die ARGB‑Farben. |

**Returns:**
int[] – Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


Die Umwandlung von ARGB-Farben zu CMYK-Farben mittels Icc-Konvertierung mit benutzerdefinierten Profilen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die ARGB‑Farben. |
| rgbIccStream | java.io.InputStream | Der Stream, der das RGB‑Icc‑Profil enthält. |
| cmykIccStream | java.io.InputStream | Der Stream, der das CMYK‑Icc‑Profil enthält. |

**Returns:**
int[] – Die CMYK‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Konvertiert RGB zu CMYK mittels benutzerdefinierter ICC-Profile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] | Die RGB‑Farben, dargestellt als 32‑Bit‑Ganzzahlwerte. |
| startIndex | int | Der Startindex der RGB‑Farbe. |
| length | int | Die Anzahl der zu konvertierenden RGB‑Pixel. |
| rgbIccStream | java.io.InputStream | Der RGB‑Profil‑Stream. |
| cmykIccStream | java.io.InputStream | Der CMYK‑Profil‑Stream. |

**Returns:**
byte[] – Die CMYK‑Farben, dargestellt als Byte‑Array.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pixel | int[] |  |
| startIndex | int |  |
| length | int |  |
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

