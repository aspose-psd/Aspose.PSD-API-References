---
title: ColorOverlayEffect
second_title: Aspose.PSD for Java API Reference
description: Color Overlay Layer effect
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class ColorOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Color Overlay Layer effect
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Gets or sets the blend mode. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets or sets the color. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calculate and gets the bounds of effect pixels based on input layer pixels bounds. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Gets the entity |
| [getEffectType()](#getEffectType--) | Gets a type of effect |
| [getOpacity()](#getOpacity--) | Gets or sets the opacity. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Gets or sets a value indicating whether this instance is visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Gets or sets the blend mode. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Gets or sets the color. |
| [setOpacity(byte value)](#setOpacity-byte-) | Gets or sets the opacity. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets a value indicating whether this instance is visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static ColorOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Gets or sets the blend mode.

Value: The blend mode.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Gets or sets the color.

Value: The color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Calculate and gets the bounds of effect pixels based on input layer pixels bounds.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | The layer pixels bounds. |
| globalAngle | int | The global angle to calculate global light angle. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Gets the entity

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Gets a type of effect

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Gets or sets the opacity.

Value: The opacity.

**Returns:**
byte
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Gets or sets a value indicating whether this instance is visible.

Value:  true  if this instance is visible; otherwise,  false .

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Gets or sets the blend mode.

Value: The blend mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Gets or sets the color.

Value: The color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Gets or sets the opacity.

Value: The opacity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Gets or sets a value indicating whether this instance is visible.

Value:  true  if this instance is visible; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

