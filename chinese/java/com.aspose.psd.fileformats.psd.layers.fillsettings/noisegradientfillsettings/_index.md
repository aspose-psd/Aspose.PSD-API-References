---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "噪声渐变定义类。"
type: docs
weight: 18
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

噪声渐变定义类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | 初始化 [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | 获取或设置一个值，指示是否 [align with layer]。 |
| [getAngle()](#getAngle--) | 获取或设置角度。 |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | 获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。 |
| [getDither()](#getDither--) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。 |
| [getExpansionCount()](#getExpansionCount--) | 获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。 |
| [getFillType()](#getFillType--) | 填充类型。 |
| [getGradientMode()](#getGradientMode--) | 获取此渐变的模式。 |
| [getGradientName()](#getGradientName--) | 获取或设置渐变的名称。 |
| [getGradientType()](#getGradientType--) | 获取或设置渐变的类型。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 获取或设置水平偏移（百分比）。 |
| [getMaximumColor()](#getMaximumColor--) | 获取或设置 PixelDataFormat 的最大颜色。 |
| [getMinimumColor()](#getMinimumColor--) | 获取或设置 PixelDataFormat 的最小颜色。 |
| [getReverse()](#getReverse--) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。 |
| [getRndNumberSeed()](#getRndNumberSeed--) | 获取或设置用于生成噪声渐变颜色的随机数种子 |
| [getRoughness()](#getRoughness--) | 获取或设置粗糙度因子。 |
| [getScale()](#getScale--) | 获取或设置比例。 |
| [getShowTransparency()](#getShowTransparency--) | 获取或设置显示透明度的标志。 |
| [getUseVectorColor()](#getUseVectorColor--) | 获取或设置使用矢量颜色的标志。 |
| [getVerticalOffset()](#getVerticalOffset--) | 获取或设置垂直偏移（百分比）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 引发值更改。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示是否 [align with layer]。 |
| [setAngle(double value)](#setAngle-double-) | 获取或设置角度。 |
| [setColorModel(short value)](#setColorModel-short-) | 获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。 |
| [setDither(boolean value)](#setDither-boolean-) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。 |
| [setExpansionCount(short value)](#setExpansionCount-short-) | 获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。 |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | 获取此渐变的模式。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 获取或设置渐变的名称。 |
| [setGradientType(int value)](#setGradientType-int-) | 获取或设置渐变的类型。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 获取或设置水平偏移（百分比）。 |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置 PixelDataFormat 的最大颜色。 |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 获取或设置 PixelDataFormat 的最小颜色。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。 |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | 获取或设置用于生成噪声渐变颜色的随机数种子 |
| [setRoughness(int value)](#setRoughness-int-) | 获取或设置粗糙度因子。 |
| [setScale(int value)](#setScale-int-) | 获取或设置比例。 |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | 获取或设置显示透明度的标志。 |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | 获取或设置使用矢量颜色的标志。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 获取或设置垂直偏移（百分比）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


初始化 [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) 类的新实例。

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


获取或设置角度。

**Returns:**
double
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
### getDither() {#getDither--}
```
public final boolean getDither()
```


获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。

值： true 表示抖动；否则为 false。

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。

**Returns:**
short
### getFillType() {#getFillType--}
```
public int getFillType()
```


填充类型。

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
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
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


获取或设置渐变的类型。

值：渐变的类型。

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


获取或设置水平偏移（百分比）。

值：水平偏移量。

**Returns:**
double
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。

值： true 表示反向；否则为 false。

**Returns:**
boolean
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
### getScale() {#getScale--}
```
public final int getScale()
```


获取或设置比例。

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
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


获取或设置垂直偏移（百分比）。

值：垂直偏移量。

**Returns:**
double
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


引发值更改。

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


获取或设置角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


获取或设置颜色模型 - RGB/HSB/LAB (3/4/6)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。

值： true 表示抖动；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


获取或设置扩展计数 ( = 2 对于 Photoshop 6.0)。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


获取此渐变的模式。确定“Gradient Type” = “Solid/Noise”（0/1）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


获取或设置渐变的类型。

值：渐变的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


获取或设置水平偏移（百分比）。

值：水平偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

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

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。

值： true 表示反向；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

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

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


获取或设置比例。

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

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


获取或设置垂直偏移（百分比）。

值：垂直偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

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

