---
title: "CmykColorHelper"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于处理以有符号 32 位整数表示的 CMYK 颜色的辅助方法。"
type: docs
weight: 18
url: /zh/java/com.aspose.psd/cmykcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

帮助方法用于处理以有符号 32 位整数值表示的 CMYK 颜色。提供与  com.aspose.psd.CmykColor  结构体类似的 API。它更轻量，因为 CMYK 颜色仅以 Int32 表示，而不是具有内部字段的结构体。请在可能的情况下优先使用此类的静态方法，而不是已弃用的  com.aspose.psd.CmykColor  结构体。
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | 从 32 位青色、品红、黄色和黑色值创建 CMYK。 |
| [getC(int cmyk)](#getC-int-) | 获取青色分量值。 |
| [getClass()](#getClass--) |  |
| [getK(int cmyk)](#getK-int-) | 获取黑色分量值。 |
| [getM(int cmyk)](#getM-int-) | 获取品红分量值。 |
| [getY(int cmyk)](#getY-int-) | 获取黄色分量值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArgb(int cmykPixel)](#toArgb-int-) | CMYK 颜色到 ARGB 颜色的转换。 |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | CMYK 颜色到 ARGB 颜色的转换。 |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | CMYK 颜色到 ARGB 颜色的转换。 |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | 使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。 |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.psd.Color-) | ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.psd.Color---) | ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmyk(int argbPixel)](#toCmyk-int-) | ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | 将 RGB 转换为 CMYK。 |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.psd.Color-) | 使用默认配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.psd.Color---) | 使用默认配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-) | 使用自定义配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。 |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | 使用自定义 ICC 配置文件将 RGB 转换为 CMYK。 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


从 32 位青色、品红、黄色和黑色值创建 CMYK。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 青色 | int | 青色分量。有效值范围为 0 到 255。 |
| 品红 | int | 品红分量。有效值范围为 0 到 255。 |
| 黄色 | int | 黄色分量。有效值范围为 0 到 255。 |
| 黑色 | int | 黑色分量。有效值范围为 0 到 255。 |

**Returns:**
int - 以 32 位整数值表示的 CMYK 颜色。
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


获取青色分量值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns:**
int - 青色分量值。
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


获取黑色分量值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns:**
int - 黑色分量值。
### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


获取品红分量值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns:**
int - 品红分量值。
### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


获取黄色分量值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmyk | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns:**
int - 黄色分量值。
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


CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值表示的 CMYK 颜色数组。 |

**Returns:**
com.aspose.psd.Color[] - ARGB 颜色。
### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


CMYK 颜色到 ARGB 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值表示的 CMYK 颜色数组。 |

**Returns:**
int[] - 以 32 位整数值表示的 ARGB 颜色。
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | int | 以 32 位整数值表示的 CMYK 颜色。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixel | int | 以 32 位整数值表示的 CMYK 颜色。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The ARGB color.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


使用默认配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | CMYK 像素以 32 位整数值的形式呈现。 |

**Returns:**
com.aspose.psd.Color[] - ARGB 颜色。
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


使用自定义配置文件的 ICC 转换，将 CMYK 颜色转换为 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cmykPixels | int[] | 以 32 位整数值表示的 CMYK 颜色数组。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |

**Returns:**
com.aspose.psd.Color[] - ARGB 颜色。
### toCmyk(Color pixel) {#toCmyk-com.aspose.psd.Color-}
```
public static int toCmyk(Color pixel)
```


ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB 颜色。 |

**Returns:**
int - 以 32 位整数值表示的 CMYK 颜色。
### toCmyk(Color[] pixels) {#toCmyk-com.aspose.psd.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB 颜色。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数值的形式呈现。
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argbPixel | int | ARGB 颜色呈现为 32 位整数值。 |

**Returns:**
int - 以 32 位整数值表示的 CMYK 颜色。
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argbPixels | int[] | ARGB 颜色以 32 位整数值的形式呈现。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数值的形式呈现。
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


将 RGB 转换为 CMYK。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argbPixels | int[] | RGB 颜色以 32 位整数值的形式呈现。 |
| startIndex | int | RGB 颜色的起始索引。 |
| 长度 | int | 要转换的 RGB 像素数量。 |

**Returns:**
byte[] - CMYK 颜色以字节数组的形式呈现。
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.psd.Color-}
```
public static int toCmykIcc(Color pixel)
```


使用默认配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB 颜色。 |

**Returns:**
int - 以 32 位整数值表示的 CMYK 颜色。
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.psd/color) | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int - 以 32 位整数值表示的 CMYK 颜色。
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.psd.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


使用默认配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB 颜色。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数值的形式呈现。
### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.psd.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义配置文件进行 Icc 转换的 ARGB 颜色到 CMYK 颜色的转换。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.psd/color) | ARGB 颜色。 |
| rgbIccStream | java.io.InputStream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | java.io.InputStream | 包含 CMYK Icc 配置文件的流。 |

**Returns:**
int[] - CMYK 颜色以 32 位整数值的形式呈现。
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


使用自定义 ICC 配置文件将 RGB 转换为 CMYK。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 像素 | int[] | RGB 颜色以 32 位整数值的形式呈现。 |
| startIndex | int | RGB 颜色的起始索引。 |
| 长度 | int | 要转换的 RGB 像素数量。 |
| rgbIccStream | java.io.InputStream | RGB 配置文件流。 |
| cmykIccStream | java.io.InputStream | CMYK 配置文件流。 |

**Returns:**
byte[] - CMYK 颜色以字节数组的形式呈现。
### toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream) {#toCmykIccBytes-internalized-int---int-int-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
```
public static byte[] toCmykIccBytes_internalized(int[] pixels, int startIndex, int length, System.IO.Stream rgbIccStream, System.IO.Stream cmykIccStream)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 像素 | int[] |  |
| startIndex | int |  |
| 长度 | int |  |
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

