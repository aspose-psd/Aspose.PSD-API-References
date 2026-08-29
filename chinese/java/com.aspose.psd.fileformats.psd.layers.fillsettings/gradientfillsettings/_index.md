---
title: "GradientFillSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "渐变填充效果设置。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

渐变填充效果设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | 初始化 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 类的新实例。 |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | 获取或设置图层容器的边界，以正确计算渐变的位置。 |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | 计算并返回对应当前 Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) 值的 **denormalized** 渐变比例（UI 比例）。 |
| [getDither()](#getDither--) | 获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否使用抖动。 |
| [getFillType()](#getFillType--) | 填充类型。 |
| [getGradient()](#getGradient--) | 获取或设置特定的渐变定义实例（实色/噪声）。 |
| [getGradientType()](#getGradientType--) | 获取或设置渐变的类型。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 获取或设置水平偏移（百分比）。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | 获取或设置渐变的插值方法。 |
| [getReverse()](#getReverse--) | 获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否反向。 |
| [getScale()](#getScale--) | 获取或设置 **normalized** 渐变比例（百分比） |
| [getVerticalOffset()](#getVerticalOffset--) | 获取或设置垂直偏移（百分比）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | 引发值更改。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示是否 [align with layer]。 |
| [setAngle(double value)](#setAngle-double-) | 获取或设置角度。 |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | 获取或设置图层容器的边界，以正确计算渐变的位置。 |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | 将指定的去标准化（UI）比例值转换为其 **normalized** 等价值，并将其分配给 Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-))。 |
| [setDither(boolean value)](#setDither-boolean-) | 获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否使用抖动。 |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | 获取或设置特定的渐变定义实例（实色/噪声）。 |
| [setGradientType(int value)](#setGradientType-int-) | 获取或设置渐变的类型。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 获取或设置水平偏移（百分比）。 |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 获取或设置渐变的插值方法。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否反向。 |
| [setScale(int value)](#setScale-int-) | 获取或设置 **normalized** 渐变比例（百分比） |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 获取或设置垂直偏移（百分比）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


初始化 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 类的新实例。

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


获取或设置图层容器的边界，以正确计算渐变的位置。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


计算并返回对应当前 Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)) 值的 **denormalized** 渐变比例（UI 比例）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | 渐变的边界。 |

**Returns:**
int - Photoshop 中显示的去标准化（UI）比例（百分比）。
### getDither() {#getDither--}
```
public final boolean getDither()
```


获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否使用抖动。

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
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


获取或设置特定的渐变定义实例（实色/噪声）。

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


获取或设置渐变的插值方法。

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否反向。

值： true 表示反向；否则为 false。

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


获取或设置 **normalized** 渐变比例（百分比）

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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


获取或设置图层容器的边界，以正确计算渐变的位置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


将指定的去标准化（UI）比例值转换为其 **normalized** 等价值，并将其分配给 Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-))。该转换使用渐变的当前 Angle ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) 和提供的 fillArea 来计算归一化因子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 去标准化比例，即 Photoshop 显示的 UI 比例（百分比）； |
| fillArea | [Size](../../com.aspose.psd/size) | 渐变的边界。 |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否使用抖动。

值： true 表示抖动；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


获取或设置特定的渐变定义实例（实色/噪声）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


获取或设置渐变的插值方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


获取或设置一个值，指示此 [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) 是否反向。

值： true 表示反向；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


获取或设置 **normalized** 渐变比例（百分比）

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

