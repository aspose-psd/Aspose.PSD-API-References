---
title: "XmpMeta"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "xmpmeta का प्रतिनिधित्व करता है।"
type: docs
weight: 17
url: /hi/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

xmpmeta का प्रतिनिधित्व करता है। वैकल्पिक। इस तत्व का उद्देश्य सामान्य XML पाठ में XMP मेटाडेटा की पहचान करना है, जिसमें RDF के अन्य गैर‑XMP उपयोग भी हो सकते हैं।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | XmpMeta क्लास का एक नया उदाहरण आरंभ करता है। |
| [XmpMeta()](#XmpMeta--) | XmpMeta क्लास का एक नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | गुण जोड़ता है। |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | निर्दिष्ट XMP तत्व को वर्तमान वाले को असाइन करता है। |
| [clearAttributes()](#clearAttributes--) | सभी गुण हटाता है। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [equals(Object other)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट  **System.Object**  इस उदाहरण के बराबर है या नहीं। |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Adobe Xmp टूलकिट संस्करण प्राप्त करता है या सेट करता है। |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | गुण प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | XMP मान को XML प्रतिनिधित्व में बदलता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | संकेत देता है कि वर्तमान वस्तु समान प्रकार की दूसरी वस्तु के बराबर है या नहीं। |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | संकेत देता है कि वर्तमान वस्तु समान प्रकार की दूसरी वस्तु के बराबर है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Adobe Xmp टूलकिट संस्करण प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


XmpMeta क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP टूलकिट संस्करण। |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


XmpMeta क्लास का एक नया उदाहरण आरंभ करता है।

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
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


निर्धारित करता है कि निर्दिष्ट  **System.Object**  इस उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अन्य | java.lang.Object | इस उदाहरण से तुलना करने के लिए  **System.Object**  । |

**Returns:**
boolean - true यदि निर्दिष्ट System.Object इस उदाहरण के बराबर है; अन्यथा false।
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Adobe Xmp टूलकिट संस्करण प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
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
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP मान को XML प्रतिनिधित्व में बदलता है।

**Returns:**
java.lang.String - XMP मान को XML प्रतिनिधित्व में परिवर्तित करके लौटाता है।
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
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


संकेत देता है कि वर्तमान वस्तु समान प्रकार की दूसरी वस्तु के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | इस वस्तु की तुलना करने के लिए एक वस्तु। |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Adobe Xmp टूलकिट संस्करण प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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

