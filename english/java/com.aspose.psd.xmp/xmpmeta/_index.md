---
title: XmpMeta
second_title: Aspose.PSD for Java API Reference
description: Represents xmpmeta.
type: docs
weight: 17
url: /java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

Represents xmpmeta. Optional. The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | Initializes a new instance of the  XmpMeta  class. |
| [XmpMeta()](#XmpMeta--) | Initializes a new instance of the  XmpMeta  class. |
## Methods

| Method | Description |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Adds the attribute. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Assigns the specified XMP element to current one. |
| [clearAttributes()](#clearAttributes--) | Removes all attributes. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified  System.Object , is equal to this instance. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Gets or set Adobe Xmp toolkit version. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Gets the attribute. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | Converts XMP value to the XML representation. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indicates whether the current object is equal to another object of the same type. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Indicates whether the current object is equal to another object of the same type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Gets or set Adobe Xmp toolkit version. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


Initializes a new instance of the  XmpMeta  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP toolkit version. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


Initializes a new instance of the  XmpMeta  class.

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Adds the attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | The attribute. |
| value | java.lang.String | The value. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Assigns the specified XMP element to current one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | The XMP element. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Removes all attributes.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Clones this instance.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determines whether the specified  System.Object , is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | The  System.Object  to compare with this instance. |

**Returns:**
boolean -  true  if the specified  System.Object  is equal to this instance; otherwise,  false .
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Gets or set Adobe Xmp toolkit version.

**Returns:**
java.lang.String
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Gets the attribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attribute | java.lang.String | The attribute. |

**Returns:**
java.lang.String - Returns the attribute for specified attribute name.
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
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the  other  parameter; otherwise, false.
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | An object to compare with this object. |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Gets or set Adobe Xmp toolkit version.

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

