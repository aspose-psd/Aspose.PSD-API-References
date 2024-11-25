---
title: GradientFillSettings
second_title: Aspose.PSD for Java API Reference
description: Gradient fill effect settings.
type: docs
weight: 15
url: /java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class GradientFillSettings extends BaseGradientFillSettings
```

Gradient fill effect settings.
## Constructors

| Constructor | Description |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Initializes a new instance of the [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) class. |
## Fields

| Field | Description |
| --- | --- |
| [PointsCountChanged_internalized](#PointsCountChanged-internalized) |  |
| [editBehaviour_internalized](#editBehaviour-internalized) | The edit behaviour. |
## Methods

| Method | Description |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Adds the color point. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Adds the color point. |
| [create_internalized(GdFlResource resource)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GdFlResource-) |  |
| [create_internalized(GrdmResource resource)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GrdmResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Generates the LFX2 resource nodes. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Gets or sets a value indicating whether [align with layer]. |
| [getAngle()](#getAngle--) | Gets or sets the angle. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets or sets the color. |
| [getColorPoints()](#getColorPoints--) | Gets or sets the color points. |
| [getDither()](#getDither--) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither. |
| [getFillType()](#getFillType--) | The fill type. |
| [getGradientMode()](#getGradientMode--) | Mode for this gradient. |
| [getGradientName()](#getGradientName--) | Gets or sets the name of the gradient. |
| [getGradientType()](#getGradientType--) | Gets or sets the type of the gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Gets or sets the horizontal offset in percentage. |
| [getInterpolation()](#getInterpolation--) | Interpolation. |
| [getReverse()](#getReverse--) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse. |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Gets or sets the transparency points. |
| [getVerticalOffset()](#getVerticalOffset--) | Gets or sets the vertical offset in percentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseChanged_internalized()](#raiseChanged-internalized--) | Raises the changed. |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Raises the value changed. |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Removes the color point. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Removes the transparency point. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Gets or sets a value indicating whether [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets the angle. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Gets or sets the color. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Gets or sets the color points. |
| [setDither(boolean value)](#setDither-boolean-) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Mode for this gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gets or sets the name of the gradient. |
| [setGradientType(int value)](#setGradientType-int-) | Gets or sets the type of the gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Gets or sets the horizontal offset in percentage. |
| [setInterpolation(short value)](#setInterpolation-short-) | Interpolation. |
| [setReverse(boolean value)](#setReverse-boolean-) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse. |
| [setScale(int value)](#setScale-int-) | Gets or sets the scale. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Gets or sets the transparency points. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Gets or sets the vertical offset in percentage. |
| [toString()](#toString--) |  |
| [updateStructures_internalized(DescriptorStructure structure)](#updateStructures-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | Updates the structures. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Initializes a new instance of the [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) class.

### PointsCountChanged_internalized {#PointsCountChanged-internalized}
```
public final Event<System.EventHandler> PointsCountChanged_internalized
```


### editBehaviour_internalized {#editBehaviour-internalized}
```
public final GradientFillSettingsEditBehaviour editBehaviour_internalized
```


The edit behaviour.

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Adds the color point.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Adds the color point.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
### create_internalized(GdFlResource resource) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GdFlResource-}
```
public static GradientFillSettings create_internalized(GdFlResource resource)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) |  |

**Returns:**
[GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)
### create_internalized(GrdmResource resource) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GrdmResource-}
```
public static GradientFillSettings create_internalized(GrdmResource resource)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resource | [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) |  |

**Returns:**
[GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Generates the LFX2 resource nodes.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Generated List of [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
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
### getColor() {#getColor--}
```
public final Color getColor()
```


Gets or sets the color.

Value: The color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Gets or sets the color points.

Value: The color points.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
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
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Interpolation. Determines Smoothness, when 'Gradient Type' = 'Solid'. Value range: 0-4096.

**Returns:**
short
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
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Gets or sets the transparency points.

Value: The transparency points.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
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

### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


Removes the color point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | The point. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Removes the transparency point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | The point. |

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

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Gets or sets the color points.

Value: The color points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

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

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Interpolation. Determines Smoothness, when 'Gradient Type' = 'Solid'. Value range: 0-4096.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Gets or sets the transparency points.

Value: The transparency points.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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
### updateStructures_internalized(DescriptorStructure structure) {#updateStructures-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void updateStructures_internalized(DescriptorStructure structure)
```


Updates the structures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structure | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) | The structure. |

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

