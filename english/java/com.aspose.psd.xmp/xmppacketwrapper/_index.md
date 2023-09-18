---
title: XmpPacketWrapper
second_title: Aspose.PSD for Java API Reference
description: Contains serialized xmp package including header and trailer.
type: docs
weight: 20
url: /java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Contains serialized xmp package including header and trailer.

A wrapper consisting of a pair of XML processing instructions (PIs) may be placed around the rdf:RDF element.
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Initializes a new instance of the  XmpPacketWrapper  class. |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Initializes a new instance of the  XmpPacketWrapper  class. |
## Methods

| Method | Description |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Adds the package. |
| [clearPackages()](#clearPackages--) | Removes all  XmpPackage  inside XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Determines whethere package is exist in xmp wrapper. |
| [deepClone_internalized()](#deepClone-internalized--) | Clones this instance. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Gets the header processing instruction. |
| [getMeta()](#getMeta--) | Gets the XMP meta. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Gets package by namespace URI. |
| [getPackages()](#getPackages--) | Gets array of  XmpPackage  inside XMP. |
| [getPackagesCount()](#getPackagesCount--) | Gets amount of packages inside XMP structure. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Gets the root RDF element. |
| [getTrailerPi()](#getTrailerPi--) | Gets the trailer processing instruction. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Converts XMP value to the XML representation. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Removes the XMP package. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Sets the header processing instruction. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Sets the XMP meta. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Sets the root RDF element. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Sets the trailer processing instruction. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Initializes a new instance of the  XmpPacketWrapper  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | The XMP header of processing instruction. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | The XMP trailer of processing instruction. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | The XMP metadata. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Initializes a new instance of the  XmpPacketWrapper  class.

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Adds the package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | The package. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Removes all  XmpPackage  inside XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Determines whethere package is exist in xmp wrapper.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | Package schema uri. |

**Returns:**
boolean - Returns true if package with specified namespace Uri exist in XMP wrapper.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Clones this instance.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Gets the header processing instruction.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Gets the XMP meta. Optional.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Gets package by namespace URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | The package schema URI. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Gets array of  XmpPackage  inside XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - The array of  XmpPackage  inside XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Gets amount of packages inside XMP structure.

**Returns:**
int - The amount of packages inside XMP structure.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Gets the root RDF element.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Gets the trailer processing instruction.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Converts XMP value to the XML representation.

**Returns:**
java.lang.String - Returns converted XMP value to XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Removes the XMP package.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | The package. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Sets the header processing instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | The Header processing instruction. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Sets the XMP meta. Optional.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | The XMP meta. Optional. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Sets the root RDF element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | The RDF root element. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Sets the trailer processing instruction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Trailer processing instruction. |

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

