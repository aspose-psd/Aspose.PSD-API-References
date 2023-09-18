---
title: XmpHeaderPi
second_title: Aspose.PSD for Java API Reference
description: Represents XMP header processing instruction.
type: docs
weight: 16
url: /java/com.aspose.psd.xmp/xmpheaderpi/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpHeaderPi implements IXmlValue, System.IEquatable<XmpHeaderPi>
```

Represents XMP header processing instruction.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpHeaderPi()](#XmpHeaderPi--) | Initializes a new instance of the  XmpHeaderPi  class. |
| [XmpHeaderPi(String guid)](#XmpHeaderPi-java.lang.String-) | Initializes a new instance of the  XmpHeaderPi  class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified  System.Object , is equal to this instance. |
| [getClass()](#getClass--) |  |
| [getGuid()](#getGuid--) | Represents Header Guid. |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isEquals(XmpHeaderPi other)](#isEquals-com.aspose.psd.xmp.XmpHeaderPi-) | Indicates whether the current object is equal to another object of the same type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(String value)](#setGuid-java.lang.String-) | Represents Header Guid. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpHeaderPi() {#XmpHeaderPi--}
```
public XmpHeaderPi()
```


Initializes a new instance of the  XmpHeaderPi  class.

### XmpHeaderPi(String guid) {#XmpHeaderPi-java.lang.String-}
```
public XmpHeaderPi(String guid)
```


Initializes a new instance of the  XmpHeaderPi  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| guid | java.lang.String | The unique identifier. |

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpHeaderPi deepClone_internalized()
```


Clones this instance.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The cloned object
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
### getGuid() {#getGuid--}
```
public String getGuid()
```


Represents Header Guid.

The text of the header PI contains a GUID, making it unlikely to appear by accident in the data stream.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### isEquals(XmpHeaderPi other) {#isEquals-com.aspose.psd.xmp.XmpHeaderPi-}
```
public boolean isEquals(XmpHeaderPi other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the  other  parameter; otherwise, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setGuid(String value) {#setGuid-java.lang.String-}
```
public void setGuid(String value)
```


Represents Header Guid.

The text of the header PI contains a GUID, making it unlikely to appear by accident in the data stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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

