---
title: StrokeEffect
second_title: Aspose.PSD for Java API Reference
description: The Adobe Photoshop stroke effect for the PSD layer.
type: docs
weight: 17
url: /java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

The Adobe® Photoshop® stroke effect for the PSD layer.
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Gets or sets the blend mode. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calculate and gets the bounds of effect pixels based on input layer pixels bounds. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Gets the entity |
| [getEffectType()](#getEffectType--) | Gets a type of effect |
| [getFillSettings()](#getFillSettings--) | Gets or sets the fill settings. |
| [getOpacity()](#getOpacity--) | Gets or sets the opacity. |
| [getOverprint()](#getOverprint--) | Gets or sets a value indicating whether this [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) will blend stroke against current layer contents. |
| [getPosition()](#getPosition--) | Gets or sets the position of the stroke effect to control the alignment of your stroke to the PSD layer content. |
| [getSize()](#getSize--) | Gets or sets the width of stroke effect. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Gets or sets a value indicating whether this instance is visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Gets or sets the blend mode. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Gets or sets the fill settings. |
| [setOpacity(byte value)](#setOpacity-byte-) | Gets or sets the opacity. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Gets or sets a value indicating whether this [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) will blend stroke against current layer contents. |
| [setPosition(short value)](#setPosition-short-) | Gets or sets the position of the stroke effect to control the alignment of your stroke to the PSD layer content. |
| [setSize(int value)](#setSize-int-) | Gets or sets the width of stroke effect. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets a value indicating whether this instance is visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Gets or sets the fill settings.

Value: The fill settings.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Gets or sets the opacity.

Value: The opacity.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Gets or sets a value indicating whether this [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) will blend stroke against current layer contents.

Value:  true  if it must blend stroke against current layer contents; otherwise,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Gets or sets the position of the stroke effect to control the alignment of your stroke to the PSD layer content. The value can be [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) to draw stroke inside of the PSD layer content, or [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) to draw stroke around of PSD layer content, and [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) to draw stroke both inside and outside.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Gets or sets the width of stroke effect.

Value: The width of the stroke effect.

**Returns:**
int
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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Gets or sets the fill settings.

Value: The fill settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Gets or sets a value indicating whether this [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) will blend stroke against current layer contents.

Value:  true  if it must blend stroke against current layer contents; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Gets or sets the position of the stroke effect to control the alignment of your stroke to the PSD layer content. The value can be [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) to draw stroke inside of the PSD layer content, or [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) to draw stroke around of PSD layer content, and [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) to draw stroke both inside and outside.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Gets or sets the width of stroke effect.

Value: The width of the stroke effect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

