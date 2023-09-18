---
title: HatchBrush
second_title: Aspose.PSD for Java API Reference
description: Defines a rectangular brush with a hatch style a foreground color and a background color.
type: docs
weight: 10
url: /java/com.aspose.psd.brushes/hatchbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class HatchBrush extends Brush
```

Defines a rectangular brush with a hatch style, a foreground color, and a background color. This class cannot be inherited.
## Constructors

| Constructor | Description |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. |
| [deepClone()](#deepClone--) | Creates a new deep clone of the current  Brush . |
| [dispose()](#dispose--) | Disposes the current instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Gets the color of spaces between the hatch lines. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Gets a value indicating whether this instance is disposed. |
| [getForegroundColor()](#getForegroundColor--) | Gets the color of hatch lines. |
| [getHatchStyle()](#getHatchStyle--) | Gets the hatch style of this brush. |
| [getOpacity()](#getOpacity--) | Gets the brush opacity. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Sets the color of spaces between the hatch lines. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.psd.Color-) | Sets the color of hatch lines. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Sets the hatch style of this brush. |
| [setOpacity(float value)](#setOpacity-float-) | Sets the brush opacity. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### close() {#close--}
```
public void close()
```


Implements the Closable interface and can be used in the try-with-resources statement since JDK 1.7. This method simply call dispose method.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Creates a new deep clone of the current  Brush .

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
### dispose() {#dispose--}
```
public final void dispose()
```


Disposes the current instance.

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gets the color of spaces between the hatch lines.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of spaces between the hatch lines.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gets a value indicating whether this instance is disposed.

**Returns:**
boolean -  true  if disposed; otherwise,  false .
### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Gets the color of hatch lines.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of hatch lines.
### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Gets the hatch style of this brush.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Gets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Returns:**
float - The brush opacity value.
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Sets the color of spaces between the hatch lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | The color of spaces between the hatch lines. |

### setForegroundColor(Color value) {#setForegroundColor-com.aspose.psd.Color-}
```
public void setForegroundColor(Color value)
```


Sets the color of hatch lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | The color of hatch lines. |

### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Sets the hatch style of this brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | The brush opacity value. |

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

