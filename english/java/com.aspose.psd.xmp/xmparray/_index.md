---
title: XmpArray
second_title: Aspose.PSD for Java API Reference
description: Represents Xmp Array in XmpPackage.
type: docs
weight: 12
url: /java/com.aspose.psd.xmp/xmparray/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public class XmpArray implements IXmlValue
```

Represents Xmp Array in  XmpPackage . todo: Array may contain complex data.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpArray(int type, String[] items)](#XmpArray-int-java.lang.String---) | Initializes a new instance of the  XmpArray  class. |
| [XmpArray(int type)](#XmpArray-int-) | Initializes a new instance of the  XmpArray  class. |
## Methods

| Method | Description |
| --- | --- |
| [addItem(String item)](#addItem-java.lang.String-) | Adds new item. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getValues()](#getValues--) | Gets array of values inside  XmpArray . |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a  System.String  that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpArray(int type, String[] items) {#XmpArray-int-java.lang.String---}
```
public XmpArray(int type, String[] items)
```


Initializes a new instance of the  XmpArray  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of array. |
| items | java.lang.String[] | The items list. |

### XmpArray(int type) {#XmpArray-int-}
```
public XmpArray(int type)
```


Initializes a new instance of the  XmpArray  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | The type of array. |

### addItem(String item) {#addItem-java.lang.String-}
```
public void addItem(String item)
```


Adds new item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | java.lang.String | The item to be added to list of items. |

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
### getValues() {#getValues--}
```
public String[] getValues()
```


Gets array of values inside  XmpArray .

**Returns:**
java.lang.String[]
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns the XMP value converted to the XML representation.
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


Returns a  System.String  that represents this instance.

**Returns:**
java.lang.String - A  System.String  that represents this instance.
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

