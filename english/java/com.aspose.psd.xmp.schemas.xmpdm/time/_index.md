---
title: Time
second_title: Aspose.PSD for Java API Reference
description: Representation of a time value in seconds.
type: docs
weight: 13
url: /java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

Representation of a time value in seconds.
## Constructors

| Constructor | Description |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | Initializes a new instance of the  Time  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | Gets or sets scale for the time value. |
| [getValue()](#getValue--) | Gets or sets time value in the specified scale. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | Gets or sets scale for the time value. |
| [setValue(int value)](#setValue-int-) | Gets or sets time value in the specified scale. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


Initializes a new instance of the  Time  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | The scale. |
| value | int | The value. |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


Gets or sets scale for the time value.

For NTSC, use 1001/30000, or the less accurate 100/2997. For PAL, use 1/25. Value: The scale for the time value.

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


Gets or sets time value in the specified scale.

Value: The time value in the specified scale.

**Returns:**
int
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


Gets or sets scale for the time value.

For NTSC, use 1001/30000, or the less accurate 100/2997. For PAL, use 1/25. Value: The scale for the time value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


Gets or sets time value in the specified scale.

Value: The time value in the specified scale.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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

