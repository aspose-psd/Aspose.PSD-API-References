---
title: RawColor
second_title: Aspose.PSD for Java API Reference
description: Raw Color Class helps to store colors with any channels count any color mode and any bit depth Please note some internal classes can have issues with converting RawColor to its native format so if API provides for you CMYK color its more reliable to use the provided format.
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color Class helps to store colors with any channels count, any color mode and any bit depth Please note, some internal classes can have issues with converting RawColor to its' native format, so if API provides for you CMYK color, it's more reliable to use the provided format. Also, there are can be some cases when Raw Color can be converted
## Constructors

| Constructor | Description |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Initializes a new instance of the [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) class. |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Initializes a new instance of the [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) class from pixel data format using predefined color modes |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsInt()](#getAsInt--) | Gets the color as int in case it's possible to get it. |
| [getAsLong()](#getAsLong--) | Gets the color as long in case it's possible to get it. |
| [getBitDepth()](#getBitDepth--) | Gets the bit depth of Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Mode for the color to follow. |
| [getColorModeName()](#getColorModeName--) | Gets the name of the color mode. |
| [getComponents()](#getComponents--) | Gets the components of color. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAsInt(int value)](#setAsInt-int-) | Sets data to all channels from int argument if it's possible |
| [setAsLong(long value)](#setAsLong-long-) | Sets data to all channels from int argument if it's possible |
| [setColorMode(short value)](#setColorMode-short-) | Mode for the color to follow. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Initializes a new instance of the [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | The custom color components. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Initializes a new instance of the [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) class from pixel data format using predefined color modes

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | The pixel data format. |
| colorMode | short |  |

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
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Gets the color as int in case it's possible to get it.

**Returns:**
int - Channels data stored in Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Gets the color as long in case it's possible to get it.

**Returns:**
long - Channels data stored in Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Gets the bit depth of Raw Color. For example for ARGB color with 8 bits per channel/component is 32 Bit Depth of full ARGB color with 16 bits per channel/component is 64. Bit depth is accumulated from the sum of channels' bit depths. It's possible if different channels will have different bit depths.

**Returns:**
int - The sum of all channels bit depths
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Mode for the color to follow.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Gets the name of the color mode. Color mode name accumulated from channels/components names

**Returns:**
java.lang.String - String with the color mode name
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Gets the components of color. Each component is separate channel, and if you use not popular color scheme, it's better to work with each channel separately

Value: The components of color

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
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




### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Sets data to all channels from int argument if it's possible

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The int value that contains component data |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Sets data to all channels from int argument if it's possible

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The int value that contains component data |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Mode for the color to follow.

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

