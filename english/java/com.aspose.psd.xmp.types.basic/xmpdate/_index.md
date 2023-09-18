---
title: XmpDate
second_title: Aspose.PSD for Java API Reference
description: Represents Date in XMP packet.
type: docs
weight: 11
url: /java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

Represents Date in XMP packet.

A date-time value is represented using a subset of the formats as defined in Date and Time Formats: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | Initializes a new instance of the  XmpDate  class. |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | Initializes a new instance of the  XmpDate  class. |
## Fields

| Field | Description |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | The ISO 8601 (roundtrip) format string. |
## Methods

| Method | Description |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | Gets the format string for current value. |
| [getValue()](#getValue--) | Gets or sets the date value. |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returns string contained value in XMP format. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | Gets or sets the date value. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


Initializes a new instance of the  XmpDate  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | java.util.Date | A date-time value which is represented using a subset of ISO RFC 8601 formatting. |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


Initializes a new instance of the  XmpDate  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateString | java.lang.String | The string representation of date. |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


The ISO 8601 (roundtrip) format string.

See more: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


Gets the format string for current value.

Value: The format string for current value.

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


Gets or sets the date value.

Value: The date value.

**Returns:**
java.util.Date
### getValue_internalized() {#getValue-internalized--}
```
public System.DateTime getValue_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returns string contained value in XMP format.

**Returns:**
java.lang.String - Returns string contained value in XMP format.
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




### setValue(Date value) {#setValue-java.util.Date-}
```
public void setValue(Date value)
```


Gets or sets the date value.

Value: The date value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

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

