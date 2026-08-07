---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "हेडर और ट्रेलर सहित सीरियलाइज़्ड xmp पैकेज को शामिल करता है।"
type: docs
weight: 20
url: /hi/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

हेडर और ट्रेलर सहित सीरियलाइज़्ड xmp पैकेज को शामिल करता है।

एक रैपर जो XML प्रोसेसिंग इंस्ट्रक्शन (PIs) की जोड़ी से बना है, rdf:RDF तत्व के चारों ओर रखा जा सकता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | नए उदाहरण को प्रारंभ करता है XmpPacketWrapper क्लास का। |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | नए उदाहरण को प्रारंभ करता है XmpPacketWrapper क्लास का। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | पैकेज जोड़ता है। |
| [clearPackages()](#clearPackages--) | XMP के भीतर सभी XmpPackage हटाता है। |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | निर्धारित करता है कि पैकेज xmp रैपर में मौजूद है या नहीं। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | हेडर प्रोसेसिंग इंस्ट्रक्शन प्राप्त करता है। |
| [getMeta()](#getMeta--) | XMP मेटा प्राप्त करता है। |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | नेमस्पेस URI द्वारा पैकेज प्राप्त करता है। |
| [getPackages()](#getPackages--) | XMP के भीतर XmpPackage की एरे प्राप्त करता है। |
| [getPackagesCount()](#getPackagesCount--) | XMP संरचना के भीतर पैकेजों की संख्या प्राप्त करता है। |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | रूट RDF तत्व प्राप्त करता है। |
| [getTrailerPi()](#getTrailerPi--) | ट्रेलर प्रोसेसिंग इंस्ट्रक्शन प्राप्त करता है। |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | XMP मान को XML प्रतिनिधित्व में बदलता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | XMP पैकेज हटाता है। |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | हेडर प्रोसेसिंग इंस्ट्रक्शन सेट करता है। |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | XMP मेटा सेट करता है। |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | रूट RDF तत्व सेट करता है। |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | ट्रेलर प्रोसेसिंग इंस्ट्रक्शन सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


नए उदाहरण को प्रारंभ करता है XmpPacketWrapper क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | प्रोसेसिंग निर्देश का XMP हेडर। |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | प्रोसेसिंग निर्देश का XMP ट्रेलर। |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP मेटाडेटा। |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


नए उदाहरण को प्रारंभ करता है XmpPacketWrapper क्लास का।

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


पैकेज जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | पैकेज। |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


XMP के भीतर सभी XmpPackage हटाता है।

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


निर्धारित करता है कि पैकेज xmp रैपर में मौजूद है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| namespaceUri | java.lang.String | पैकेज स्कीमा URI। |

**Returns:**
boolean - यदि निर्दिष्ट नेमस्पेस URI वाला पैकेज XMP रैपर में मौजूद है तो true लौटाता है।
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


इस उदाहरण को क्लोन करता है।

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


हेडर प्रोसेसिंग इंस्ट्रक्शन प्राप्त करता है।

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


XMP मेटा प्राप्त करता है। वैकल्पिक।

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


नेमस्पेस URI द्वारा पैकेज प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| namespaceUri | java.lang.String | पैकेज स्कीमा URI। |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


XMP के भीतर XmpPackage की एरे प्राप्त करता है।

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - XMP के अंदर XmpPackage की एरे।
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


XMP संरचना के भीतर पैकेजों की संख्या प्राप्त करता है।

**Returns:**
int - XMP संरचना के भीतर पैकेजों की संख्या।
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


रूट RDF तत्व प्राप्त करता है।

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


ट्रेलर प्रोसेसिंग इंस्ट्रक्शन प्राप्त करता है।

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


XMP मान को XML प्रतिनिधित्व में बदलता है।

**Returns:**
java.lang.String - परिवर्तित XMP मान को XML में लौटाता है।
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


XMP पैकेज हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | पैकेज। |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


हेडर प्रोसेसिंग इंस्ट्रक्शन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | हेडर प्रोसेसिंग निर्देश। |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


XMP मेटा सेट करता है। वैकल्पिक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | XMP मेटा। वैकल्पिक। |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


रूट RDF तत्व सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | RDF रूट एलिमेंट। |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


ट्रेलर प्रोसेसिंग इंस्ट्रक्शन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | ट्रेलर प्रोसेसिंग निर्देश। |

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

