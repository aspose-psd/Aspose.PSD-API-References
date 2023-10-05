---
title: CmykColor
second_title: Aspose.PSD for Java API Reference
description: The CMYK color of pixel.
type: docs
weight: 17
url: /java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

The CMYK color of pixel.
## Constructors

| Constructor | Description |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Creates a  CmykColor  structure from a 32-bit cyan, magenta, yellow and black values. |
| [getC()](#getC--) | Gets the cyan component value of this  com.aspose.psd.Color  structure. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Gets the empty. |
| [getK()](#getK--) | Gets the black component value of this  com.aspose.psd.Color  structure. |
| [getM()](#getM--) | Gets the magenta component value of this  com.aspose.psd.Color  structure. |
| [getY()](#getY--) | Gets the yellow component value of this  com.aspose.psd.Color  structure. |
| [hashCode()](#hashCode--) | The get hash code. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this  com.aspose.psd.Color  structure is uninitialized. |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | The conversion from CMYKColor to 32-bit ARGB Color using icc conversion with default profiles. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | The conversion from 32-bit ARGB to CMYKColor. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | The conversion from 32-bit ARGB color to CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | The conversion from CMYKColor to Color. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | The conversion from CMYKColor to Color using icc conversion with default profiles. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | The conversion from CMYKColor to Color using icc conversion with default profiles. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | The conversion from CMYKColor to Color using icc conversion. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | The conversion from CMYKColor to Color using icc conversion with default profiles. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | The conversion from CMYKColor to Color using icc conversion. |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | The conversion from CMYKColor to Color using icc conversion. |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | The conversion from CMYKColor to Color using icc conversion. |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | The to value. |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Creates a  CmykColor  structure from a 32-bit cyan, magenta, yellow and black values. This method is deprecated. Please use more effective CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cyan | int | The cyan component. Valid values are 0 through 255. |
| magenta | int | The magenta component. Valid values are 0 through 255. |
| yellow | int | The yellow component. Valid values are 0 through 255. |
| black | int | The black component. Valid values are 0 through 255. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


Gets the cyan component value of this  com.aspose.psd.Color  structure.

**Returns:**
byte - The cyan component value of this  com.aspose.psd.Color .
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


Gets the empty.

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


Gets the black component value of this  com.aspose.psd.Color  structure.

Value: The black component value of this  com.aspose.psd.Color .

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


Gets the magenta component value of this  com.aspose.psd.Color  structure.

**Returns:**
byte - The magenta component value of this  com.aspose.psd.Color .
### getY() {#getY--}
```
public byte getY()
```


Gets the yellow component value of this  com.aspose.psd.Color  structure.

**Returns:**
byte - The yellow component value of this  com.aspose.psd.Color .
### hashCode() {#hashCode--}
```
public int hashCode()
```


The get hash code.

**Returns:**
int - The  int .
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this  com.aspose.psd.Color  structure is uninitialized.

**Returns:**
boolean - This property returns true if this color is uninitialized; otherwise, false.
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Type | Description |
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


The conversion from CMYKColor to 32-bit ARGB Color using icc conversion with default profiles. This method is deprecated. Please use more effective  CmykColorHelper.toArgb32(int[]) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
int[] - The array of the 32-bit ARGB color.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


The conversion from 32-bit ARGB to CMYKColor. This method is deprecated. Please use more effective  CmykColorHelper.toCmyk(int) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixel | int | The pixel of 32-bit ARGB format. |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


The conversion from 32-bit ARGB color to CMYKColor. This method is deprecated. Please use more effective  CmykColorHelper.toCmyk(int[]) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | The pixels of 32-bit ARGB format. |

**Returns:**
com.aspose.psd.CmykColor[] - The  Aspose:Imaging:CmykColor[] .
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


The conversion from CMYKColor to Color. This method is deprecated. Please use more effective  CmykColorHelper.toArgb(int) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective  CmykColorHelper.toArgb(int[]) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
com.aspose.psd.Color[] - The array of the ARGB colors.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective  CmykColorHelper.toArgbIcc(int) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | The pixel of CMYKColor type in CMYK format. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYKColor to Color using icc conversion. This method is deprecated. Please use more effective  CmykColorHelper.toArgbIcc(int, Stream, Stream) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | The pixel of CMYKColor type in CMYK format. |
| cmykIccStream | java.io.InputStream | The stream containing icc cmyk profile. |
| rgbIccStream | java.io.InputStream | The stream containing icc rgb profile. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
com.aspose.psd.Color[] - The  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYKColor to Color using icc conversion. This method is deprecated. Please use more effective  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |
| cmykIccStream | java.io.InputStream | The stream containing icc cmyk profile. |
| rgbIccStream | java.io.InputStream | The stream containing icc rgb profile. |

**Returns:**
com.aspose.psd.Color[] - The  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


The conversion from CMYKColor to Color using icc conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | The pixel of CMYKColor type in CMYK format. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | The stream containing icc cmyk profile. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | The stream containing icc rgb profile. |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


The conversion from CMYKColor to Color using icc conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | The pixels of CMYKColor type in CMYK format. |
| cmykIccStream | com.aspose.ms.System.IO.Stream | The stream containing icc cmyk profile. |
| rgbIccStream | com.aspose.ms.System.IO.Stream | The stream containing icc rgb profile. |

**Returns:**
com.aspose.psd.Color[] - The  Aspose.Imaging.Color[] .
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


The to value.

**Returns:**
long - The  long .
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

