---
title: ColorRangeHsl
second_title: Aspose.PSD for Java API Reference
description: has 6 color ranges where you can change HSV parameters.
type: docs
weight: 21
url: /java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Initializes a new instance of the [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) class. |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Initializes a new instance of the [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) class. |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Gets or sets the hue. |
| [getLeftBorder()](#getLeftBorder--) | Gets or sets the left border. |
| [getLightness()](#getLightness--) | Gets or sets the lightness. |
| [getMostLeftBorder()](#getMostLeftBorder--) | Gets or sets the most left border. |
| [getMostRightBorder()](#getMostRightBorder--) | Gets or sets the most right border. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Gets the range Coefficient. |
| [getRightBorder()](#getRightBorder--) | Gets or sets the right border. |
| [getSaturation()](#getSaturation--) | Gets or sets the saturation. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Determines whether is hue in big range. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Determines whether hue in small range. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Saves data to the specified stream container. |
| [setHue(short value)](#setHue-short-) | Gets or sets the hue. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Gets or sets the left border. |
| [setLightness(short value)](#setLightness-short-) | Gets or sets the lightness. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | Gets or sets the most left border. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | Gets or sets the most right border. |
| [setRightBorder(short value)](#setRightBorder-short-) | Gets or sets the right border. |
| [setSaturation(short value)](#setSaturation-short-) | Gets or sets the saturation. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Initializes a new instance of the [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) class.

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Initializes a new instance of the [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | The color range data. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHue() {#getHue--}
```
public final short getHue()
```


Gets or sets the hue.

Value: The hue.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Gets or sets the left border.

Value: The left border.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Gets or sets the lightness.

Value: The lightness.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


Gets or sets the most left border.

Value: The most left border.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


Gets or sets the most right border.

Value: The most right border.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Gets the range Coefficient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | double | The hue value. |

**Returns:**
double - Saturation range coefficient.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Gets or sets the right border.

Value: The right border.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Gets or sets the saturation.

Value: The saturation.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


Determines whether is hue in big range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | double | The hue value. |

**Returns:**
boolean -  true  if hue in big range; otherwise,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Determines whether hue in small range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| hue | double | The hue value. |

**Returns:**
boolean -  true  if hue in small range; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Saves data to the specified stream container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Gets or sets the hue.

Value: The hue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Gets or sets the left border.

Value: The left border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Gets or sets the lightness.

Value: The lightness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


Gets or sets the most left border.

Value: The most left border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


Gets or sets the most right border.

Value: The most right border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Gets or sets the right border.

Value: The right border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Gets or sets the saturation.

Value: The saturation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

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

