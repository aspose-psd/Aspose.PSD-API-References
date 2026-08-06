---
title: "NoiseGradient"
second_title: "Aspose.PSD 的 Java API 参考"
description: "噪声渐变定义类。"
type: docs
weight: 19
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class NoiseGradient extends BaseGradient
```

噪声渐变定义类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NoiseGradient()](#NoiseGradient--) | 初始化一个新的 [NoiseGradient](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient) 类实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | 获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。 |
| [getExpansionCount()](#getExpansionCount--) | 获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。 |
| [getGradientMode()](#getGradientMode--) | 获取此渐变的模式。 |
| [getGradientName()](#getGradientName--) | 获取或设置渐变的名称。 |
| [getMaximumColor()](#getMaximumColor--) | 获取或设置 PixelDataFormat 的最大颜色。 |
| [getMinimumColor()](#getMinimumColor--) | 获取或设置 PixelDataFormat 的最小颜色。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | 获取或设置用于生成噪声渐变颜色的随机数种子 |
| [getRoughness()](#getRoughness--) | 获取或设置粗糙度因子。 |
| [getShowTransparency()](#getShowTransparency--) | 获取或设置显示透明度的标志。 |
| [getUseVectorColor()](#getUseVectorColor--) | 获取或设置使用矢量颜色的标志。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColorModel(short value)](#setColorModel-short-) | 获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。 |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 获取或设置渐变的名称。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置 PixelDataFormat 的最大颜色。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置 PixelDataFormat 的最小颜色。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 获取或设置用于生成噪声渐变颜色的随机数种子 |
| [setRoughness(int value)](#setRoughness-int-) | 获取或设置粗糙度因子。 |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 获取或设置显示透明度的标志。 |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | 获取或设置使用矢量颜色的标志。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradient() {#NoiseGradient--}
```
public NoiseGradient()
```


初始化一个新的 [NoiseGradient](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradient) 类实例。

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。

**Returns:**
short
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


获取此渐变的模式。确定“Gradient Type” = “Solid/Noise”（0/1）。

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


获取或设置渐变的名称。

值：渐变的名称。

**Returns:**
java.lang.String
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


获取或设置 PixelDataFormat 的最大颜色。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


获取或设置 PixelDataFormat 的最小颜色。

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


获取或设置用于生成噪声渐变颜色的随机数种子

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


获取或设置粗糙度因子。

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


获取或设置显示透明度的标志。

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


获取或设置使用矢量颜色的标志。

**Returns:**
boolean
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




### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


获取或设置渐变的名称。

值：渐变的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


获取或设置 PixelDataFormat 的最大颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


获取或设置 PixelDataFormat 的最小颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


获取或设置用于生成噪声渐变颜色的随机数种子

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


获取或设置粗糙度因子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


获取或设置显示透明度的标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


获取或设置使用矢量颜色的标志。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

