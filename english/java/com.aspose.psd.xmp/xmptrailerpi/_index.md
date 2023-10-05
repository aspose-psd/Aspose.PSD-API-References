---
title: XmpTrailerPi
second_title: Aspose.PSD for Java API Reference
description: Represents XMP trailer processing instruction.
type: docs
weight: 22
url: /java/com.aspose.psd.xmp/xmptrailerpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpTrailerPi implements IXmlValue, System.IEquatable<XmpTrailerPi>
```

Represents XMP trailer processing instruction.

The end="w" or end="r" portion shall be used by packet scanning processors to determine whether the XMP may be modified in-place.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpTrailerPi(boolean isWritable)](#XmpTrailerPi-boolean-) | Initializes a new instance of the  XmpTrailerPi  class. |
| [XmpTrailerPi()](#XmpTrailerPi--) | Initializes a new instance of the  XmpTrailerPi  class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified  System.Object , is equal to this instance. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Converts xmp value to the xml representation. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isEquals(XmpTrailerPi other)](#isEquals-com.aspose.psd.xmp.XmpTrailerPi-) | Indicates whether the current object is equal to another object of the same type. |
| [isWritable()](#isWritable--) | Gets or sets a value indicating whether this instance is writable. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setWritable(boolean value)](#setWritable-boolean-) | Gets or sets a value indicating whether this instance is writable. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpTrailerPi(boolean isWritable) {#XmpTrailerPi-boolean-}
```
public XmpTrailerPi(boolean isWritable)
```


Initializes a new instance of the  XmpTrailerPi  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isWritable | boolean | Inditacates whether trailer is writable. |

### XmpTrailerPi() {#XmpTrailerPi--}
```
public XmpTrailerPi()
```


Initializes a new instance of the  XmpTrailerPi  class.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpTrailerPi deepClone_internalized()
```


Clones this instance.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified  System.Object , is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  System.Object  to compare with this instance. |

**Returns:**
boolean -  true  if the specified  System.Object  is equal to this instance; otherwise,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts xmp value to the xml representation.

**Returns:**
java.lang.String - Returns XML representation of XMP.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### isEquals(XmpTrailerPi other) {#isEquals-com.aspose.psd.xmp.XmpTrailerPi-}
```
public boolean isEquals(XmpTrailerPi other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the  other  parameter; otherwise, false.
### isWritable() {#isWritable--}
```
public boolean isWritable()
```


Gets or sets a value indicating whether this instance is writable.

Value:  true  if this instance is writable; otherwise,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setWritable(boolean value) {#setWritable-boolean-}
```
public void setWritable(boolean value)
```


Gets or sets a value indicating whether this instance is writable.

Value:  true  if this instance is writable; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

