---
title: GradientFillSettings
second_title: Aspose.PSD for Java API Reference
description: Gradient fill effect settings.
type: docs
weight: 14
url: /java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Gradient fill effect settings.
## Constructors

| Constructor | Description |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Initializes a new instance of the [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) class. |
## Fields

| Field | Description |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Gets or sets a value indicating whether [align with layer]. |
| [getAngle()](#getAngle--) | Gets or sets the angle. |
| [getClass()](#getClass--) |  |
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Gets or sets the bounds of the layer container to correctly calculate the position of the gradient. |
| [getDither()](#getDither--) | Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is dither. |
| [getFillType()](#getFillType--) | The fill type. |
| [getGradient()](#getGradient--) | Gets or sets specific gradient definition instance (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Gets or sets the type of the gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Gets or sets the horizontal offset in percentage. |
| [getReverse()](#getReverse--) | Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is reverse. |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getVerticalOffset()](#getVerticalOffset--) | Gets or sets the vertical offset in percentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Raises the value changed. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Gets or sets a value indicating whether [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets the angle. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Gets or sets the bounds of the layer container to correctly calculate the position of the gradient. |
| [setDither(boolean value)](#setDither-boolean-) | Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is dither. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Gets or sets specific gradient definition instance (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Gets or sets the type of the gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Gets or sets the horizontal offset in percentage. |
| [setReverse(boolean value)](#setReverse-boolean-) | Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is reverse. |
| [setScale(int value)](#setScale-int-) | Gets or sets the scale. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Gets or sets the vertical offset in percentage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Initializes a new instance of the [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) class.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Gets or sets a value indicating whether [align with layer].

Value:  true  if [align with layer]; otherwise,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Gets or sets the angle.

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


Gets or sets the bounds of the layer container to correctly calculate the position of the gradient.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDither() {#getDither--}
```
public final boolean getDither()
```


Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is dither.

Value:  true  if dither; otherwise,  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


The fill type.

**Returns:**
int
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Gets or sets specific gradient definition instance (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Gets or sets the type of the gradient.

Value: The type of the gradient.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Gets or sets the horizontal offset in percentage.

Value: The horizontal offset.

**Returns:**
double
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is reverse.

Value:  true  if reverse; otherwise,  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Gets or sets the scale.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Gets or sets the vertical offset in percentage.

Value: The vertical offset.

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


Raises the value changed.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Gets or sets a value indicating whether [align with layer].

Value:  true  if [align with layer]; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Gets or sets the angle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Gets or sets the bounds of the layer container to correctly calculate the position of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is dither.

Value:  true  if dither; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Gets or sets specific gradient definition instance (Solid/Noise).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Gets or sets the type of the gradient.

Value: The type of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Gets or sets the horizontal offset in percentage.

Value: The horizontal offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Gets or sets a value indicating whether this [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) is reverse.

Value:  true  if reverse; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Gets or sets the scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Gets or sets the vertical offset in percentage.

Value: The vertical offset.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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

