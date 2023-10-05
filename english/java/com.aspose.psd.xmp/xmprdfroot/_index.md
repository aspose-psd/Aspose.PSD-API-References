---
title: XmpRdfRoot
second_title: Aspose.PSD for Java API Reference
description: Represents rdfRDF element.
type: docs
weight: 21
url: /java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

Represents rdf:RDF element. A single XMP packet shall be serialized using a single rdf:RDF XML element. The rdf:RDF element content shall consist of only zero or more rdf:Description elements.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | Initializes a new instance of the  XmpRdfRoot  class. |
## Methods

| Method | Description |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Adds the attribute. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Assigns the specified XMP element to current one. |
| [clearAttributes()](#clearAttributes--) | Removes all attributes. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified  Object , is equal to this instance. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Gets the attribute. |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Gets namespace URI by specific prefix. |
| [getXmlValue()](#getXmlValue--) | Converts xmp value to the xml representation. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Indicates whether the current object is equal to another object of the same type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Adds namespace uri by prefix. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


Initializes a new instance of the  XmpRdfRoot  class.

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
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified  Object , is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The  Object  to compare with this instance. |

**Returns:**
boolean -  true  if the specified  Object  is equal to this instance; otherwise,  false .
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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Gets namespace URI by specific prefix. Prefix may start without xmlns.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |

**Returns:**
java.lang.String - Returns a package schema URI.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Converts xmp value to the xml representation.

**Returns:**
java.lang.String - Returns XMP value converted to XML string.
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Adds namespace uri by prefix. Prefix may start without xmlns.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix. |
| namespaceUri | java.lang.String | Package schema uri. |

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

