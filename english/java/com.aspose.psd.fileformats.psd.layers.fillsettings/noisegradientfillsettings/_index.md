---
title: NoiseGradientFillSettings
second_title: Aspose.PSD for Java API Reference
description: Noise gradient definition class.
type: docs
weight: 18
url: /java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Noise gradient definition class.
## Constructors

| Constructor | Description |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Initializes a new instance of the [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) class. |
## Fields

| Field | Description |
| --- | --- |
| [editBehaviour_internalized](#editBehaviour-internalized) | The edit behaviour. |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(GdFlResource gdFlResource)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GdFlResource-) |  |
| [create_internalized(GrdmResource grdmResource)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GrdmResource-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Gets or sets a value indicating whether [align with layer]. |
| [getAngle()](#getAngle--) | Gets or sets the angle. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Gets or sets the color. |
| [getColorModel()](#getColorModel--) | Color Model - RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither. |
| [getExpansionCount()](#getExpansionCount--) | Expansion count ( = 2 for Photoshop 6.0). |
| [getFillType()](#getFillType--) | The fill type. |
| [getGradientMode()](#getGradientMode--) | Mode for this gradient. |
| [getGradientName()](#getGradientName--) | Gets or sets the name of the gradient. |
| [getGradientType()](#getGradientType--) | Gets or sets the type of the gradient. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Gets or sets the horizontal offset in percentage. |
| [getMaximumColor()](#getMaximumColor--) | Maximum color of PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Minimum color of PixelDataFormat. |
| [getReverse()](#getReverse--) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse. |
| [getRndNumberSeed()](#getRndNumberSeed--) | The random number seed used to generate colors for Noise gradient |
| [getRoughness()](#getRoughness--) | Roughness factor. |
| [getScale()](#getScale--) | Gets or sets the scale. |
| [getShowTransparency()](#getShowTransparency--) | Flag for showing transparency. |
| [getUseVectorColor()](#getUseVectorColor--) | Flag for using vector color. |
| [getVerticalOffset()](#getVerticalOffset--) | Gets or sets the vertical offset in percentage. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseChanged_internalized()](#raiseChanged-internalized--) | Raises the changed. |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Raises the value changed. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Gets or sets a value indicating whether [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Gets or sets the angle. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Gets or sets the color. |
| [setColorModel(short value)](#setColorModel-short-) | Color Model - RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Expansion count ( = 2 for Photoshop 6.0). |
| [setGradientMode(int value)](#setGradientMode-int-) | Mode for this gradient. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gets or sets the name of the gradient. |
| [setGradientType(int value)](#setGradientType-int-) | Gets or sets the type of the gradient. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Gets or sets the horizontal offset in percentage. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Maximum color of PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Minimum color of PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | The random number seed used to generate colors for Noise gradient |
| [setRoughness(int value)](#setRoughness-int-) | Roughness factor. |
| [setScale(int value)](#setScale-int-) | Gets or sets the scale. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Flag for showing transparency. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Flag for using vector color. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Gets or sets the vertical offset in percentage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Initializes a new instance of the [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) class.

### editBehaviour_internalized {#editBehaviour-internalized}
```
public final GradientFillSettingsEditBehaviour editBehaviour_internalized
```


The edit behaviour.

### create_internalized(GdFlResource gdFlResource) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GdFlResource-}
```
public static NoiseGradientFillSettings create_internalized(GdFlResource gdFlResource)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gdFlResource | [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) |  |

**Returns:**
[NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings)
### create_internalized(GrdmResource grdmResource) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.GrdmResource-}
```
public static NoiseGradientFillSettings create_internalized(GrdmResource grdmResource)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| grdmResource | [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) |  |

**Returns:**
[NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings)
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
### getColor() {#getColor--}
```
public final Color getColor()
```


Gets or sets the color.

Value: The color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Color Model - RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is dither.

Value:  true  if dither; otherwise,  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Expansion count ( = 2 for Photoshop 6.0).

**Returns:**
short
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Maximum color of PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Minimum color of PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Gets or sets a value indicating whether this [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) is reverse.

Value:  true  if reverse; otherwise,  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


The random number seed used to generate colors for Noise gradient

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Roughness factor.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Gets or sets the scale.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Flag for showing transparency.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Flag for using vector color.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Color Model - RGB/HSB/LAB (3/4/6).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Expansion count ( = 2 for Photoshop 6.0).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Maximum color of PixelDataFormat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Minimum color of PixelDataFormat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


The random number seed used to generate colors for Noise gradient

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Roughness factor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Gets or sets the scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Flag for showing transparency.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Flag for using vector color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

