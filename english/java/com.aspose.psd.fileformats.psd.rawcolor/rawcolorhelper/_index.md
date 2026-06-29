---
title: RawColorHelper
second_title: Aspose.PSD for Java API Reference
description: Raw Color Helper Class helps to create RawColor faster using predefined channel metadata
type: docs
weight: 12
url: /java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class helps to create RawColor faster, using predefined channel metadata
## Constructors

| Constructor | Description |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | Creates a 16-bit per channel ARGB color. |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | Creates an 8-bit per channel ARGB color. |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | Creates an 8-bit per channel ARGB color from Drawing.Color |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | Creates a 16-bit per channel CMYK color. |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | Creates an 8-bit per channel CMYK color. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


Creates a 16-bit per channel ARGB color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | int | The alpha component value (0-65535). |
| r | int | The red component value (0-65535). |
| g | int | The green component value (0-65535). |
| b | int | The blue component value (0-65535).

--------------------

The color components are packed into a 64-bit integer in the order: alpha (bits 48-63), red (bits 32-47), green (bits 16-31), and blue (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


Creates an 8-bit per channel ARGB color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | byte | The alpha component value (0-255). |
| r | byte | The red component value (0-255). |
| g | byte | The green component value (0-255). |
| b | byte | The blue component value (0-255).

--------------------

The color components are packed into a 32-bit integer in the order: alpha (bits 24-31), red (bits 16-23), green (bits 8-15), and blue (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


Creates an 8-bit per channel ARGB color from Drawing.Color

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| drawingColor | [Color](../../com.aspose.psd/color) | The System.Drawing Color

--------------------

The color components are packed into a 32-bit integer in the order: alpha (bits 24-31), red (bits 16-23), green (bits 8-15), and blue (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


Creates a 16-bit per channel CMYK color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | int | The cyan component value (0-65535). |
| m | int | The magenta component value (0-65535). |
| y | int | The yellow component value (0-65535). |
| k | int | The key (black) component value (0-65535).

--------------------

The color components are packed into a 64-bit integer in the order: cyan (bits 48-63), magenta (bits 32-47), yellow (bits 16-31), and key/black (bits 0-15). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


Creates an 8-bit per channel CMYK color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | byte | The cyan component value (0-255). |
| m | byte | The magenta component value (0-255). |
| y | byte | The yellow component value (0-255). |
| k | byte | The key (black) component value (0-255).

--------------------

The color components are packed into a 32-bit integer in the order: cyan (bits 24-31), magenta (bits 16-23), yellow (bits 8-15), and key/black (bits 0-7). |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

