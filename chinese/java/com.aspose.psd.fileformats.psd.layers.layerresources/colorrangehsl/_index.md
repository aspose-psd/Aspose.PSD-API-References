---
title: "ColorRangeHsl"
second_title: "Aspose.PSD 的 Java API 参考"
description: "具有 6 个颜色范围，您可以更改 HSV 参数。"
type: docs
weight: 22
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | 初始化 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 类的新实例。 |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | 初始化 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | 获取或设置色相。 |
| [getLeftBorder()](#getLeftBorder--) | 获取或设置左边界。 |
| [getLightness()](#getLightness--) | 获取或设置亮度。 |
| [getMostLeftBorder()](#getMostLeftBorder--) | 获取或设置最左边界。 |
| [getMostRightBorder()](#getMostRightBorder--) | 获取或设置最右边界。 |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | 获取范围系数。 |
| [getRightBorder()](#getRightBorder--) | 获取或设置右边界。 |
| [getSaturation()](#getSaturation--) | 获取或设置饱和度。 |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | 确定色相是否在大范围内。 |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | 确定色相是否在小范围内。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | 将数据保存到指定的流容器。 |
| [setHue(short value)](#setHue-short-) | 获取或设置色相。 |
| [setLeftBorder(short value)](#setLeftBorder-short-) | 获取或设置左边界。 |
| [setLightness(short value)](#setLightness-short-) | 获取或设置亮度。 |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | 获取或设置最左边界。 |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | 获取或设置最右边界。 |
| [setRightBorder(short value)](#setRightBorder-short-) | 获取或设置右边界。 |
| [setSaturation(short value)](#setSaturation-short-) | 获取或设置饱和度。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


初始化 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 类的新实例。

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


初始化 [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| data | byte[] | 颜色范围数据。 |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHue() {#getHue--}
```
public final short getHue()
```


获取或设置色相。

值：色相。

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


获取或设置左边界。

值：左边框。

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


获取或设置亮度。

值：亮度。

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


获取或设置最左边界。

值：最左边框。

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


获取或设置最右边界。

值：最右边框。

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


获取范围系数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 色相 | double | 色相值。 |

**Returns:**
double - 饱和度范围系数。
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


获取或设置右边界。

值：右边框。

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


获取或设置饱和度。

值：饱和度。

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


确定色相是否在大范围内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 色相 | double | 色相值。 |

**Returns:**
boolean -  true  如果色相在大范围内；否则，  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


确定色相是否在小范围内。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 色相 | double | 色相值。 |

**Returns:**
boolean -  true  如果色相在小范围内；否则，  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


将数据保存到指定的流容器。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


获取或设置色相。

值：色相。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


获取或设置左边界。

值：左边框。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


获取或设置亮度。

值：亮度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


获取或设置最左边界。

值：最左边框。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


获取或设置最右边界。

值：最右边框。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


获取或设置右边界。

值：右边框。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


获取或设置饱和度。

值：饱和度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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

