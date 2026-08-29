---
title: "CmykColor"
second_title: "Aspose.PSD 的 Java API 参考"
description: "像素的 CMYK 颜色。"
type: docs
weight: 17
url: /zh/java/com.aspose.psd/cmykcolor/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

像素的 CMYK 颜色。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.psd.CmykColor-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | 从 32 位青色、品红、黄色和黑色值创建一个 CmykColor 结构。 |
| [getC()](#getC--) | 获取此 com.aspose.psd.Color 结构的青色分量值。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取空值。 |
| [getK()](#getK--) | 获取此 com.aspose.psd.Color 结构的黑色分量值。 |
| [getM()](#getM--) | 获取此 com.aspose.psd.Color 结构的品红分量值。 |
| [getY()](#getY--) | 获取此 com.aspose.psd.Color 结构的黄色分量值。 |
| [hashCode()](#hashCode--) | 获取哈希码。 |
| [isEmpty()](#isEmpty--) | 获取一个值，指示此  com.aspose.psd.Color  结构是否未初始化。 |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.psd.CmykColor---) | 使用默认配置文件的 ICC 转换，将 CMYKColor 转换为 32 位 ARGB 颜色。 |
| [toCmyk(int argbPixel)](#toCmyk-int-) | 将 32 位 ARGB 转换为 CMYKColor。 |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | 从 32 位 ARGB 颜色到 CMYKColor 的转换。 |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.psd.CmykColor-) | 从 CMYKColor 到 Color 的转换。 |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.psd.CmykColor---) | 使用默认配置文件的 icc 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.psd.CmykColor-) | 使用默认配置文件的 icc 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-) | 使用 icc 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.psd.CmykColor---) | 使用默认配置文件的 icc 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-) | 使用 icc 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | 使用 icc 转换将 CMYKColor 转换为 Color。 |
| [toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)](#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | 使用 icc 转换将 CMYKColor 转换为 Color。 |
| [toString()](#toString--) |  |
| [toValue()](#toValue--) | to 值。 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(CmykColor that) {#CloneTo-com.aspose.psd.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.psd/cmykcolor) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


从 32 位青色、品红、黄色和黑色值创建 CmykColor 结构。此方法已弃用。请使用更有效的 CmykColorHelper\#fromComponents(int, int, int, int)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 青色 | int | 青色分量。有效值范围为 0 到 255。 |
| 品红 | int | 品红分量。有效值范围为 0 到 255。 |
| 黄色 | int | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | int | 黑色分量。有效值范围为 0 到 255。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  CmykColor .
### getC() {#getC--}
```
public byte getC()
```


获取此 com.aspose.psd.Color 结构的青色分量值。

**Returns:**
byte - 此 com.aspose.psd.Color 的青色分量值。
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


获取空值。

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor)
### getK() {#getK--}
```
public byte getK()
```


获取此 com.aspose.psd.Color 结构的黑色分量值。

Value: 此 com.aspose.psd.Color 的黑色分量值。

**Returns:**
byte
### getM() {#getM--}
```
public byte getM()
```


获取此 com.aspose.psd.Color 结构的品红分量值。

**Returns:**
byte - 此 com.aspose.psd.Color 的品红分量值。
### getY() {#getY--}
```
public byte getY()
```


获取此 com.aspose.psd.Color 结构的黄色分量值。

**Returns:**
byte - 此 com.aspose.psd.Color 的黄色分量值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取哈希码。

**Returns:**
int - int。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，指示此  com.aspose.psd.Color  结构是否未初始化。

**Returns:**
boolean - 如果此颜色未初始化，则返回 true；否则返回 false。
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.psd.CmykColor-com.aspose.psd.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Type | 描述 |
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


使用默认配置文件的 icc 转换，将 CMYKColor 转换为 32 位 ARGB Color。此方法已弃用。请使用更有效的 CmykColorHelper.toArgb32(int[])。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
int[] - 32 位 ARGB 颜色的数组。
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


将 32 位 ARGB 转换为 CMYKColor。此方法已弃用。请使用更有效的 CmykColorHelper.toCmyk(int)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argbPixel | int | 32 位 ARGB 格式的像素。 |

**Returns:**
[CmykColor](../../com.aspose.psd/cmykcolor) - The  Aspose:Imaging:CmykColor .
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


将 32 位 ARGB 颜色转换为 CMYKColor。此方法已弃用。请使用更有效的 CmykColorHelper.toCmyk(int[])。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argbPixels | int[] | 32 位 ARGB 格式的像素。 |

**Returns:**
com.aspose.psd.CmykColor[] - Aspose:Imaging:CmykColor[]。
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.psd.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 CmykColorHelper.toArgb(int)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Aspose.Imaging.Color[] .
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.psd.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


使用默认配置文件的 icc 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 CmykColorHelper.toArgb(int[])。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
com.aspose.psd.Color[] - ARGB 颜色的数组。
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.psd.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


使用默认配置文件的 icc 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 CmykColorHelper.toArgbIcc(int)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用 icc 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 CmykColorHelper.toArgbIcc(int, Stream, Stream)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmykIccStream | java.io.InputStream | 包含 ICC CMYK 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 ICC RGB 配置文件的流。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.psd.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


使用默认配置文件的 icc 转换，将 CMYKColor 转换为 Color。此方法已弃用。请使用更有效的 CmykColorHelper\#toArgbIcc(int[])。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |

**Returns:**
com.aspose.psd.Color[] - 该  com.aspose.psd.Color[] .
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.psd.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用 ICC 转换将 CMYKColor 转换为 Color 的过程。此方法已弃用。请使用更有效的  CmykColorHelper.toArgbIcc(int[], InputStream, InputStream) .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmykIccStream | java.io.InputStream | 包含 ICC CMYK 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 ICC RGB 配置文件的流。 |

**Returns:**
com.aspose.psd.Color[] - 该  Aspose.Imaging.Color[] .
### toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color toColorIcc_internalized(CmykColor cmykPixel, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


使用 icc 转换将 CMYKColor 转换为 Color。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmykIccStream | com.aspose.ms.System.IO.Stream | 包含 ICC CMYK 配置文件的流。 |
| rgbIccStream | com.aspose.ms.System.IO.Stream | 包含 ICC RGB 配置文件的流。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The  Color .
### toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream) {#toColorIcc-internalized-com.aspose.psd.CmykColor---com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static Color[] toColorIcc_internalized(CmykColor[] cmykPixels, System.IO.Stream cmykIccStream, System.IO.Stream rgbIccStream)
```


使用 icc 转换将 CMYKColor 转换为 Color。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | CMYK 格式中 CMYKColor 类型的像素。 |
| cmykIccStream | com.aspose.ms.System.IO.Stream | 包含 ICC CMYK 配置文件的流。 |
| rgbIccStream | com.aspose.ms.System.IO.Stream | 包含 ICC RGB 配置文件的流。 |

**Returns:**
com.aspose.psd.Color[] - 该  Aspose.Imaging.Color[] .
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


to 值。

**Returns:**
long - 该  long .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

