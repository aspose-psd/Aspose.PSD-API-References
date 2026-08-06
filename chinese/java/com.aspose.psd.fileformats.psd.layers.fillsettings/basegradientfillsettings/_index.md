---
title: "BaseGradientFillSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "基础渐变定义类。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Base gradient 定义类。它包含实心和噪声两种渐变的通用属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | 初始化 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 类的新实例。 |
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
| [getDither()](#getDither--) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。 |
| [getFillType()](#getFillType--) | 填充类型。 |
| [getGradientMode()](#getGradientMode--) | 获取此渐变的模式。 |
| [getGradientName()](#getGradientName--) | 获取或设置渐变的名称。 |
| [getGradientType()](#getGradientType--) | 获取或设置渐变的类型。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 获取或设置水平偏移（百分比）。 |
| [getReverse()](#getReverse--) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。 |
| [getScale()](#getScale--) | 获取或设置比例。 |
| [getVerticalOffset()](#getVerticalOffset--) | 获取或设置垂直偏移（百分比）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 引发值更改。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示是否 [align with layer]。 |
| [setAngle(double value)](#setAngle-double-) | 获取或设置角度。 |
| [setDither(boolean value)](#setDither-boolean-) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。 |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | 获取此渐变的模式。 |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | 获取或设置渐变的名称。 |
| [setGradientType(int value)](#setGradientType-int-) | 获取或设置渐变的类型。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 获取或设置水平偏移（百分比）。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。 |
| [setScale(int value)](#setScale-int-) | 获取或设置比例。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 获取或设置垂直偏移（百分比）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


初始化 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 类的新实例。

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
### getDither() {#getDither--}
```
public final boolean getDither()
```


获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否进行抖动。

值： true 表示抖动；否则为 false。

**Returns:**
boolean
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


获取或设置一个值，指示此 [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) 是否为反向。

值： true 表示反向；否则为 false。

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


获取或设置比例。

**Returns:**
int
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

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


获取或设置比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

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

