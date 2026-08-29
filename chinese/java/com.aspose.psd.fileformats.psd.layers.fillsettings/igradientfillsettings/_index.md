---
title: "IGradientFillSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于渐变填充设置的基础接口。"
type: docs
weight: 23
url: /zh/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

用于渐变填充设置的基础接口。
## Methods

| Method | 描述 |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | 获取或设置一个值，指示是否 [align with layer]。 |
| [getAngle()](#getAngle--) | 获取或设置角度。 |
| [getDither()](#getDither--) | 获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否抖动。 |
| [getGradient()](#getGradient--) | 获取或设置特定的渐变定义实例（实色/噪声）。 |
| [getGradientType()](#getGradientType--) | 获取或设置渐变的类型。 |
| [getHorizontalOffset()](#getHorizontalOffset--) | 获取或设置水平偏移。 |
| [getInterpolationMethod()](#getInterpolationMethod--) | 获取或设置渐变的插值方法。 |
| [getReverse()](#getReverse--) | 获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否反向。 |
| [getScale()](#getScale--) | 获取或设置 **normalized** 渐变比例（百分比）。 |
| [getVerticalOffset()](#getVerticalOffset--) | 获取或设置垂直偏移量。 |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | 获取或设置一个值，指示是否 [align with layer]。 |
| [setAngle(double value)](#setAngle-double-) | 获取或设置角度。 |
| [setDither(boolean value)](#setDither-boolean-) | 获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否抖动。 |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | 获取或设置特定的渐变定义实例（实色/噪声）。 |
| [setGradientType(int value)](#setGradientType-int-) | 获取或设置渐变的类型。 |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | 获取或设置水平偏移。 |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | 获取或设置渐变的插值方法。 |
| [setReverse(boolean value)](#setReverse-boolean-) | 获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否反向。 |
| [setScale(int value)](#setScale-int-) | 获取或设置 **normalized** 渐变比例（百分比）。 |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | 获取或设置垂直偏移量。 |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


获取或设置角度。

值：角度。

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否抖动。

值： true 表示抖动；否则为 false。

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


获取或设置特定的渐变定义实例（实色/噪声）。

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


获取或设置渐变的类型。

值：渐变的类型。

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


获取或设置水平偏移。

值：水平偏移量。

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


获取或设置渐变的插值方法。

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否反向。

值： true 表示反向；否则为 false。

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


获取或设置 **normalized** 渐变比例（百分比）。

值：比例。

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


获取或设置垂直偏移量。

值：垂直偏移量。

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


获取或设置一个值，指示是否 [align with layer]。

值：如果 [align with layer] 为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


获取或设置角度。

值：角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否抖动。

值： true 表示抖动；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


获取或设置特定的渐变定义实例（实色/噪声）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


获取或设置渐变的类型。

值：渐变的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


获取或设置水平偏移。

值：水平偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


获取或设置渐变的插值方法。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


获取或设置一个值，指示此 [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) 是否反向。

值： true 表示反向；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


获取或设置 **normalized** 渐变比例（百分比）。

值：比例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


获取或设置垂直偏移量。

值：垂直偏移量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double |  |

