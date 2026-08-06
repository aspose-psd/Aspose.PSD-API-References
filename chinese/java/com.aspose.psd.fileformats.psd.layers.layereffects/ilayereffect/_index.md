---
title: "ILayerEffect"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图层效果的接口"
type: docs
weight: 20
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

图层效果的接口
## Methods

| Method | 描述 |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | 获取或设置混合模式。 |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | 计算并获取基于输入图层像素边界的效果像素边界。 |
| [getEffectType()](#getEffectType--) | 获取效果的类型 |
| [getOpacity()](#getOpacity--) | 获取或设置不透明度，其中 255 = 100%。 |
| [isVisible()](#isVisible--) | 获取或设置指示此实例是否可见的值。 |
| [setBlendMode(long value)](#setBlendMode-long-) | 获取或设置混合模式。 |
| [setOpacity(byte value)](#setOpacity-byte-) | 获取或设置不透明度，其中 255 = 100%。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 获取或设置指示此实例是否可见的值。 |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


获取或设置混合模式。

值：混合模式。

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


计算并获取基于输入图层像素边界的效果像素边界。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | 图层像素边界。 |
| globalAngle | int | 用于计算全局光角度的全局角度。 |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


获取效果的类型

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


获取或设置不透明度，其中 255 = 100%。

值：不透明度。

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


获取或设置指示此实例是否可见的值。

值：  true  如果此实例可见；否则，  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


获取或设置混合模式。

值：混合模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


获取或设置不透明度，其中 255 = 100%。

值：不透明度。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


获取或设置指示此实例是否可见的值。

值：  true  如果此实例可见；否则，  false .

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

