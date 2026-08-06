---
title: "IShadowEffect"
second_title: "Aspose.PSD 的 Java API 参考"
description: "阴影图层效果的接口"
type: docs
weight: 21
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect)
```
public interface IShadowEffect extends ILayerEffect
```

阴影图层效果的接口
## Methods

| Method | 描述 |
| --- | --- |
| [getAngle()](#getAngle--) | 获取或设置角度（单位：度）。 |
| [getColor()](#getColor--) | 获取或设置颜色。 |
| [getDistance()](#getDistance--) | 获取或设置以像素为单位的距离。 |
| [getNoise()](#getNoise--) | 获取或设置噪声。 |
| [getSize()](#getSize--) | 获取或设置以像素为单位的模糊值。 |
| [getSpread()](#getSpread--) | 获取或设置以百分比表示的强度。 |
| [getUseGlobalLight()](#getUseGlobalLight--) | 获取或设置一个值，指示是否[在所有图层效果中使用此角度]。 |
| [setAngle(int value)](#setAngle-int-) | 获取或设置角度（单位：度）。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | 获取或设置颜色。 |
| [setDistance(int value)](#setDistance-int-) | 获取或设置以像素为单位的距离。 |
| [setNoise(int value)](#setNoise-int-) | 获取或设置噪声。 |
| [setSize(int value)](#setSize-int-) | 获取或设置以像素为单位的模糊值。 |
| [setSpread(int value)](#setSpread-int-) | 获取或设置以百分比表示的强度。 |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | 获取或设置一个值，指示是否[在所有图层效果中使用此角度]。 |
### getAngle() {#getAngle--}
```
public abstract int getAngle()
```


获取或设置角度（单位：度）。

值：角度。

**Returns:**
int
### getColor() {#getColor--}
```
public abstract Color getColor()
```


获取或设置颜色。

值：颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public abstract int getDistance()
```


获取或设置以像素为单位的距离。

值：距离。

**Returns:**
int
### getNoise() {#getNoise--}
```
public abstract int getNoise()
```


获取或设置噪声。

**Returns:**
int
### getSize() {#getSize--}
```
public abstract int getSize()
```


获取或设置以像素为单位的模糊值。

值：大小。

**Returns:**
int
### getSpread() {#getSpread--}
```
public abstract int getSpread()
```


获取或设置以百分比表示的强度。

值：扩散。

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public abstract boolean getUseGlobalLight()
```


获取或设置一个值，指示是否[在所有图层效果中使用此角度]。

值：如果[使用全局光]则为 true；否则为 false。

**Returns:**
boolean
### setAngle(int value) {#setAngle-int-}
```
public abstract void setAngle(int value)
```


获取或设置角度（单位：度）。

值：角度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public abstract void setColor(Color value)
```


获取或设置颜色。

值：颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public abstract void setDistance(int value)
```


获取或设置以像素为单位的距离。

值：距离。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setNoise(int value) {#setNoise-int-}
```
public abstract void setNoise(int value)
```


获取或设置噪声。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```


获取或设置以像素为单位的模糊值。

值：大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setSpread(int value) {#setSpread-int-}
```
public abstract void setSpread(int value)
```


获取或设置以百分比表示的强度。

值：扩散。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public abstract void setUseGlobalLight(boolean value)
```


获取或设置一个值，指示是否[在所有图层效果中使用此角度]。

值：如果[使用全局光]则为 true；否则为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

