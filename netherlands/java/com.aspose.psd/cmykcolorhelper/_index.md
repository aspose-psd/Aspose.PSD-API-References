---
title: "CmykColorHelper"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Helpermethoden om te werken met CMYK-kleur gepresenteerd als een ondertekend 32-bit geheel getal."
type: docs
weight: 18
url: /nl/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Hulpmethoden om te werken met CMYK-kleur gepresenteerd als een ondertekende 32-bit gehele getalwaarde. Biedt een vergelijkbare API als de  com.aspose.psd.CmykColor  struct. Het is lichter omdat CMYK-kleur alleen als Int32 wordt gepresenteerd in plaats van als een structuur met interne velden. Gebruik bij voorkeur de statische methoden van deze klasse wanneer mogelijk in plaats van de verouderde  com.aspose.psd.CmykColor  struct.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Maakt CMYK aan vanuit 32-bit cyaan-, magenta-, geel- en zwartwaarden. |
| [getC(int cmyk)](#getC-int-) | Haalt de cyaancomponentwaarde op. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Haalt de zwartcomponentwaarde op. |
| [getM(int cmyk)](#getM-int-) | Haalt de magentacomponentwaarde op. |
| [getY(int cmyk)](#getY-int-) | Haalt de geelcomponentwaarde op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | De conversie van CMYK-kleur naar ARGB-kleur. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | De conversie van CMYK-kleuren naar ARGB-kleuren. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | De conversie van CMYK-kleuren naar ARGB-kleuren. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | De conversie van een CMYK-kleur naar een ARGB-kleur met Icc-conversie en standaardprofielen. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | De conversie van een CMYK-kleur naar een ARGB-kleur met Icc-conversie en aangepast profiel. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en standaardprofielen. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en aangepaste profielen. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | De conversie van een ARGB-kleur naar een CMYK-kleur. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | De conversie van ARGB-kleuren naar CMYK-kleuren. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | De conversie van een ARGB-kleur naar een CMYK-kleur. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | De conversie van ARGB-kleuren naar CMYK-kleuren. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Converteert RGB naar CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | De conversie van een ARGB-kleur naar een CMYK-kleur met Icc-conversie en standaardprofielen. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | De conversie van een ARGB-kleur naar een CMYK-kleur met Icc-conversie en aangepaste profielen. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en standaardprofielen. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en aangepaste profielen. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Converteert RGB naar CMYK met aangepaste ICC-profielen. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Maakt CMYK aan vanuit 32-bit cyaan-, magenta-, geel- en zwartwaarden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cyaan | int | Het cyaancomponent. Geldige waarden zijn 0 tot en met 255. |
| magenta | int | Het magentacomponent. Geldige waarden zijn 0 tot en met 255. |
| geel | int | Het gele component. Geldige waarden zijn 0 tot en met 255. |
| zwart | int | Het zwarte component. Geldige waarden zijn 0 tot en met 255. |

**Returns:**
int - De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Haalt de cyaancomponentwaarde op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |

**Returns:**
int - De cyaancomponentwaarde.
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


Haalt de zwartcomponentwaarde op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |

**Returns:**
int - De zwarte componentwaarde.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Haalt de magentacomponentwaarde op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |

**Returns:**
int - De magentacomponentwaarde.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Haalt de geelcomponentwaarde op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmyk | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |

**Returns:**
int - De gele componentwaarde.
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


De conversie van CMYK-kleur naar ARGB-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


De conversie van CMYK-kleuren naar ARGB-kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | int[] | De CMYK-kleuren gepresenteerd als 32-bits gehele getallen. |

**Returns:**
com.aspose.psd.Color[] - De ARGB-kleuren.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


De conversie van CMYK-kleuren naar ARGB-kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | int[] | De CMYK-kleuren gepresenteerd als 32-bits gehele getallen. |

**Returns:**
int[] - De ARGB-kleuren gepresenteerd als 32-bits gehele getallen.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


De conversie van een CMYK-kleur naar een ARGB-kleur met Icc-conversie en standaardprofielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


De conversie van een CMYK-kleur naar een ARGB-kleur met Icc-conversie en aangepast profiel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixel | int | De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde. |
| cmykIccStream | java.io.InputStream | De stroom die het CMYK Icc-profiel bevat. |
| rgbIccStream | java.io.InputStream | De stroom die het RGB Icc-profiel bevat. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en standaardprofielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | int[] | De CMYK-pixels gepresenteerd als 32-bits gehele getallen. |

**Returns:**
com.aspose.psd.Color[] - De ARGB-kleuren.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


De conversie van CMYK-kleuren naar ARGB-kleuren met Icc-conversie en aangepaste profielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cmykPixels | int[] | De CMYK-kleuren gepresenteerd als 32-bits gehele getallen. |
| cmykIccStream | java.io.InputStream | De stroom die het CMYK Icc-profiel bevat. |
| rgbIccStream | java.io.InputStream | De stroom die het RGB Icc-profiel bevat. |

**Returns:**
com.aspose.psd.Color[] - De ARGB-kleuren.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


De conversie van een ARGB-kleur naar een CMYK-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | De ARGB-kleur. |

**Returns:**
int - De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


De conversie van ARGB-kleuren naar CMYK-kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De ARGB-kleuren. |

**Returns:**
int[] - De CMYK-kleuren gepresenteerd als 32-bits gehele getallen.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


De conversie van een ARGB-kleur naar een CMYK-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argbPixel | int | De ARGB-kleur gepresenteerd als een 32-bits geheel getal. |

**Returns:**
int - De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


De conversie van ARGB-kleuren naar CMYK-kleuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argbPixels | int[] | De ARGB-kleuren gepresenteerd als 32-bits gehele getallen. |

**Returns:**
int[] - De CMYK-kleuren gepresenteerd als 32-bits gehele getallen.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Converteert RGB naar CMYK.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argbPixels | int[] | De RGB-kleuren gepresenteerd als 32-bits gehele getallen. |
| startIndex | int | De startindex van de RGB-kleur. |
| lengte | int | Het aantal RGB-pixels om te converteren. |

**Returns:**
byte[] - De CMYK-kleuren gepresenteerd als een byte-array.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


De conversie van een ARGB-kleur naar een CMYK-kleur met Icc-conversie en standaardprofielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | De ARGB-kleur. |

**Returns:**
int - De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


De conversie van een ARGB-kleur naar een CMYK-kleur met Icc-conversie en aangepaste profielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | De ARGB-kleur. |
| rgbIccStream | java.io.InputStream | De stroom die het RGB Icc-profiel bevat. |
| cmykIccStream | java.io.InputStream | De stroom die het CMYK Icc-profiel bevat. |

**Returns:**
int - De CMYK-kleur gepresenteerd als een 32-bits geheel getalwaarde.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en standaardprofielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De ARGB-kleuren. |

**Returns:**
int[] - De CMYK-kleuren gepresenteerd als 32-bits gehele getallen.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


De conversie van ARGB-kleuren naar CMYK-kleuren met Icc-conversie en aangepaste profielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De ARGB-kleuren. |
| rgbIccStream | java.io.InputStream | De stroom die het RGB Icc-profiel bevat. |
| cmykIccStream | java.io.InputStream | De stroom die het CMYK Icc-profiel bevat. |

**Returns:**
int[] - De CMYK-kleuren gepresenteerd als 32-bits gehele getallen.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converteert RGB naar CMYK met aangepaste ICC-profielen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] | De RGB-kleuren gepresenteerd als 32-bits gehele getallen. |
| startIndex | int | De startindex van de RGB-kleur. |
| lengte | int | Het aantal RGB-pixels om te converteren. |
| rgbIccStream | java.io.InputStream | De RGB-profielstroom. |
| cmykIccStream | java.io.InputStream | De CMYK-profielstroom. |

**Returns:**
byte[] - De CMYK-kleuren gepresenteerd als een byte-array.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixels | int[] |  |
| startIndex | int |  |
| lengte | int |  |
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

