---
title: ColorantCmyk
second_title: Aspose.PSD for Java API Reference
description: Represents CMYK Colorant.
type: docs
weight: 13
url: /java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Represents CMYK Colorant.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Initializes a new instance of the  ColorantCmyk  class. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Initializes a new instance of the  ColorantCmyk  class. |
## Fields

| Field | Description |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Color max value in CMYK colorant. |
| [ColorValueMin](#ColorValueMin) | Color min value in CMYK colorant. |
## Methods

| Method | Description |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Adds the specified key. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Gets or sets the black component value. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Gets or sets the type of the color. |
| [getCyan()](#getCyan--) | Gets or sets the cyan component value. |
| [getMagenta()](#getMagenta--) | Gets or sets the magenta component value. |
| [getMode()](#getMode--) | Gets  ColorMode . |
| [getNamespaceUri()](#getNamespaceUri--) | Gets the default namespace URI. |
| [getPrefix()](#getPrefix--) | Gets the prefix. |
| [getSwatchName()](#getSwatchName--) | Gets or sets the name of the swatch. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
| [getYellow()](#getYellow--) | Gets or sets the yellow component value. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Gets or sets the black component value. |
| [setColorType(int value)](#setColorType-int-) | Gets or sets the type of the color. |
| [setCyan(float value)](#setCyan-float-) | Gets or sets the cyan component value. |
| [setMagenta(float value)](#setMagenta-float-) | Gets or sets the magenta component value. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Gets or sets the name of the swatch. |
| [setYellow(float value)](#setYellow-float-) | Gets or sets the yellow component value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Initializes a new instance of the  ColorantCmyk  class.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Initializes a new instance of the  ColorantCmyk  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| black | float | The black component value. |
| cyan | float | The cyan color component value. |
| magenta | float | The magenta component value. |
| yellow | float | The yellow component value. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Color max value in CMYK colorant.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Color min value in CMYK colorant.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Adds the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The string representation of key that is identified with added value. |
| value | java.lang.Object | The value to add to. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Gets or sets the black component value.

Value: The black component value.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Gets or sets the type of the color.

Value: The type of the color.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Gets or sets the cyan component value.

Value: The cyan component value.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Gets or sets the magenta component value.

Value: The magenta component value.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Gets  ColorMode .

Value: The color mode.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Gets the default namespace URI.

**Returns:**
java.lang.String - The default namespace URI.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Gets the prefix.

**Returns:**
java.lang.String - The prefix.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Gets or sets the name of the swatch.

Value: The name of the swatch.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Gets or sets the yellow component value.

Value: The yellow component value.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Gets or sets the black component value.

Value: The black component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Gets or sets the type of the color.

Value: The type of the color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Gets or sets the cyan component value.

Value: The cyan component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Gets or sets the magenta component value.

Value: The magenta component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Gets or sets the name of the swatch.

Value: The name of the swatch.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Gets or sets the yellow component value.

Value: The yellow component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

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

