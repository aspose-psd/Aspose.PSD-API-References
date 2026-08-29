---
title: "XmpRdfRoot"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "rdfRDF तत्व का प्रतिनिधित्व करता है।"
type: docs
weight: 21
url: /hi/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

rdf:RDF तत्व का प्रतिनिधित्व करता है। एकल XMP पैकेट को एकल rdf:RDF XML तत्व का उपयोग करके क्रमबद्ध किया जाएगा। rdf:RDF तत्व की सामग्री केवल शून्य या अधिक rdf:Description तत्वों से बनी होगी।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | XmpRdfRoot वर्ग का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | गुण जोड़ता है। |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | निर्दिष्ट XMP तत्व को वर्तमान वाले को असाइन करता है। |
| [clearAttributes()](#clearAttributes--) | सभी गुण हटाता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट Object इस उदाहरण के बराबर है या नहीं। |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | गुण प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | विशिष्ट उपसर्ग द्वारा नेमस्पेस URI प्राप्त करता है। |
| [getXmlValue()](#getXmlValue--) | xmp मान को xml प्रतिनिधित्व में परिवर्तित करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | संकेत देता है कि वर्तमान वस्तु समान प्रकार की दूसरी वस्तु के बराबर है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | उपसर्ग द्वारा नेमस्पेस URI जोड़ता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


XmpRdfRoot वर्ग का नया उदाहरण प्रारंभ करता है।

### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


गुण जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attribute | java.lang.String | गुण। |
| मान | java.lang.String | मान। |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


निर्दिष्ट XMP तत्व को वर्तमान वाले को असाइन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | XMP तत्व। |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


सभी गुण हटाता है।

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


इस उदाहरण को क्लोन करता है।

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट Object इस उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | Object इस इंस्टेंस से तुलना करने के लिए। |

**Returns:**
boolean - true यदि निर्दिष्ट Object इस इंस्टेंस के बराबर है; अन्यथा, false।
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


गुण प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| attribute | java.lang.String | गुण। |

**Returns:**
java.lang.String - निर्दिष्ट विशेषता नाम के लिए विशेषता लौटाता है।
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


विशिष्ट उपसर्ग द्वारा नेमस्पेस URI प्राप्त करता है। उपसर्ग बिना xmlns के शुरू हो सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| उपसर्ग | java.lang.String | उपसर्ग। |

**Returns:**
java.lang.String - पैकेज स्कीमा URI लौटाता है।
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp मान को xml प्रतिनिधित्व में परिवर्तित करता है।

**Returns:**
java.lang.String - XMP मान को XML स्ट्रिंग में परिवर्तित करके लौटाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


संकेत देता है कि वर्तमान वस्तु समान प्रकार की दूसरी वस्तु के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | इस वस्तु की तुलना करने के लिए एक वस्तु। |

**Returns:**
boolean - true यदि वर्तमान वस्तु अन्य पैरामीटर के बराबर है; अन्यथा false।
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


उपसर्ग द्वारा नेमस्पेस URI जोड़ता है। उपसर्ग बिना xmlns के शुरू हो सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| उपसर्ग | java.lang.String | उपसर्ग। |
| namespaceUri | java.lang.String | पैकेज स्कीमा URI। |

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

