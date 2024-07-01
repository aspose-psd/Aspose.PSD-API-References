---
title: BaseGradientFillSettings
second_title: Aspose.PSD for Java API Reference
description: Base gradient definition class.
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Base gradient definition class. It contains common properties for both types of gradient (Solid and Noise).
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Initializes a new instance of the [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) class. |
| [BaseGradientFillSettings(GdFlResource resource)](#BaseGradientFillSettings-com.aspose.psd.fileformats.psd.layers.layerresources.GdFlResource-) | Initializes a new instance of the [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) class. |
## Fields

| Field | Description |
| --- | --- |
| [editBehaviour_internalized](#editBehaviour-internalized) | The edit behaviour. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Gets or sets a value indicating whether [align with layer]. |
| [getAngle()](#getAngle--) | Gets or sets the angle. |
| [getClass()](#getClass--) |  |
| [getDither()](#getDither--) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither. |
| [getFillType()](#getFillType--) | The fill type. |
| [getGradientMode()](#getGradientMode--) | Mode for this gradient. |
| [getGradientName()](#getGradientName--) | Gets or sets the name of the gradient. |
| [getGradientType()](#getGradientType--) | Gets or sets the type of the gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Gets or sets the horizontal offset in percentage. |
| [getReverse()](#getReverse--) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse. |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getVerticalOffset()](#getVerticalOffset--) | Gets or sets the vertical offset in percentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseChanged_internalized()](#raiseChanged-internalized--) | Raises the changed. |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Raises the value changed. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Gets or sets a value indicating whether [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets the angle. |
| [setDither(boolean value)](#setDither-boolean-) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither. |
| [setGradientMode(int value)](#setGradientMode-int-) | Mode for this gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gets or sets the name of the gradient. |
| [setGradientType(int value)](#setGradientType-int-) | Gets or sets the type of the gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Gets or sets the horizontal offset in percentage. |
| [setReverse(boolean value)](#setReverse-boolean-) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse. |
| [setScale(int value)](#setScale-int-) | Gets or sets the scale. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Gets or sets the vertical offset in percentage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Initializes a new instance of the [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) class.

### BaseGradientFillSettings(GdFlResource resource) {#BaseGradientFillSettings-com.aspose.psd.fileformats.psd.layers.layerresources.GdFlResource-}
```
public BaseGradientFillSettings(GdFlResource resource)
```


Initializes a new instance of the [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) | The resource. |

### editBehaviour_internalized {#editBehaviour-internalized}
```
public final GradientFillSettingsEditBehaviour editBehaviour_internalized
```


The edit behaviour.

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
### getDither() {#getDither--}
```
public final boolean getDither()
```


Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither.

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
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Mode for this gradient. Determines 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Gets or sets the name of the gradient.

Value: The name of the gradient.

**Returns:**
java.lang.String
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


Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse.

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




### raiseChanged_internalized() {#raiseChanged-internalized--}
```
public void raiseChanged_internalized()
```


Raises the changed.

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

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither.

Value:  true  if dither; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Mode for this gradient. Determines 'Gradient Type' = 'Solid/Noise' (0/1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Gets or sets the name of the gradient.

Value: The name of the gradient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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


Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse.

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

