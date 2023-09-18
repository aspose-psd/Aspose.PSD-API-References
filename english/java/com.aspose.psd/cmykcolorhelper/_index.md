---
title: CmykColorHelper
second_title: Aspose.PSD for Java API Reference
description: Helper methods to work with CMYK color presented as a signed 32-bit integer value.
type: docs
weight: 18
url: /java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Helper methods to work with CMYK color presented as a signed 32-bit integer value. Provides the similar API as the  com.aspose.psd.CmykColor  struct. It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated  com.aspose.psd.CmykColor  struct.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| [getC(int cmyk)](#getC-int-) | Gets the cyan component value. |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | Gets the black component value. |
| [getM(int cmyk)](#getM-int-) | Gets the magenta component value. |
| [getY(int cmyk)](#getY-int-) | Gets the yellow component value. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | The conversion from CMYK color to ARGB color. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | The conversion from CMYK colors to ARGB colors. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | The conversion from CMYK colors to ARGB colors. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | The conversion from CMYK color to ARGB Color using Icc conversion with default profiles. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | The conversion from CMYK color to ARGB color using Icc conversion with custom profile. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | The conversion from ARGB color to CMYK color. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | The conversion from ARGB colors to CMYK colors. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | The conversion from ARGB color to CMYK color. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | The conversion from ARGB colors to CMYK colors. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Converts RGB to CMYK. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Converts RGB to CMYK using custom ICC profiles. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Creates CMYK from a 32-bit cyan, magenta, yellow and black values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cyan | int | The cyan component. Valid values are 0 through 255. |
| magenta | int | The magenta component. Valid values are 0 through 255. |
| yellow | int | The yellow component. Valid values are 0 through 255. |
| black | int | The black component. Valid values are 0 through 255. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Gets the cyan component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The cyan component value.
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


Gets the black component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The black component value.
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Gets the magenta component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The magenta component value.
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Gets the yellow component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The yellow component value.
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


The conversion from CMYK color to ARGB color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


The conversion from CMYK colors to ARGB colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns:**
com.aspose.psd.Color[] - The ARGB colors.
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


The conversion from CMYK colors to ARGB colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns:**
int[] - The ARGB colors presented as 32-bit integer values.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


The conversion from CMYK color to ARGB Color using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYK color to ARGB color using Icc conversion with custom profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | int | The CMYK color presented as a 32-bit integer value. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK pixels presented as 32-bit integer values. |

**Returns:**
com.aspose.psd.Color[] - The ARGB colors.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK colors presented as 32-bit integer values. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |

**Returns:**
com.aspose.psd.Color[] - The ARGB colors.
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


The conversion from ARGB color to CMYK color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | The ARGB color. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


The conversion from ARGB colors to CMYK colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | The ARGB colors. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


The conversion from ARGB color to CMYK color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixel | int | The ARGB color presented as a 32-bit integer value. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


The conversion from ARGB colors to CMYK colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | The ARGB colors presented as 32-bit integer values. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Converts RGB to CMYK.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | The RGB colors presented as 32-bit integer values. |
| startIndex | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns:**
byte[] - The CMYK colors presented as a byte array.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | The ARGB color. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | The ARGB color. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | The ARGB colors. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | The ARGB colors. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converts RGB to CMYK using custom ICC profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The RGB colors presented as 32-bit integer values. |
| startIndex | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgbIccStream | java.io.InputStream | The RGB profile stream. |
| cmykIccStream | java.io.InputStream | The CMYK profile stream. |

**Returns:**
byte[] - The CMYK colors presented as a byte array.
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] |  |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

