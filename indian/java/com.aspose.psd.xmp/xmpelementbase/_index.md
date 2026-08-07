---
title: "XmpElementBase"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "बेस xmp एलिमेंट जो एट्रिब्यूट्स रखता है, उसका प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/java/com.aspose.psd.xmp/xmpelementbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

बेस xmp एलिमेंट जो एट्रिब्यूट्स रखता है, उसका प्रतिनिधित्व करता है।
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
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | संकेत देता है कि वर्तमान वस्तु समान प्रकार की दूसरी वस्तु के बराबर है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

