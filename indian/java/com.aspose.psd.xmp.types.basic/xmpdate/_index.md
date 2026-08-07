---
title: "XmpDate"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "XMP पैकेट में तिथि का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.xmp.types.basic/xmpdate/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class XmpDate extends XmpTypeBase
```

XMP पैकेट में तिथि का प्रतिनिधित्व करता है।

एक तिथि-समय मान को Date and Time Formats में परिभाषित स्वरूपों के एक उपसमुच्चय का उपयोग करके दर्शाया जाता है: YYYY YYYY-MM YYYY-MM-DD YYYY-MM-DDThh:mmTZD YYYY-MM-DDThh:mm:ssTZD YYYY-MM-DDThh:mm:ss.sTZD
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XmpDate(Date dateTime)](#XmpDate-java.util.Date-) | XmpDate क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [XmpDate(String dateString)](#XmpDate-java.lang.String-) | XmpDate क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Iso8601Format](#Iso8601Format) | ISO 8601 (राउंडट्रिप) फ़ॉर्मेट स्ट्रिंग। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create_internalized(System.DateTime dateTime)](#create-internalized-com.aspose.ms.System.DateTime-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormat()](#getFormat--) | वर्तमान मान के लिए फ़ॉर्मेट स्ट्रिंग प्राप्त करता है। |
| [getValue()](#getValue--) | तारीख मान को प्राप्त करता है या सेट करता है। |
| [getValue_internalized()](#getValue-internalized--) |  |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP प्रारूप में सम्मिलित स्ट्रिंग मान लौटाता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(Date value)](#setValue-java.util.Date-) | तारीख मान को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpDate(Date dateTime) {#XmpDate-java.util.Date-}
```
public XmpDate(Date dateTime)
```


XmpDate क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dateTime | java.util.Date | एक तिथि-समय मान जो ISO RFC 8601 फ़ॉर्मेटिंग के उपसमुच्चय का उपयोग करके दर्शाया गया है। |

### XmpDate(String dateString) {#XmpDate-java.lang.String-}
```
public XmpDate(String dateString)
```


XmpDate क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dateString | java.lang.String | तारीख का स्ट्रिंग प्रतिनिधित्व। |

### Iso8601Format {#Iso8601Format}
```
public static final String Iso8601Format
```


ISO 8601 (राउंडट्रिप) फ़ॉर्मेट स्ट्रिंग।

और देखें: https://en.wikipedia.org/wiki/ISO\_8601.

### create_internalized(System.DateTime dateTime) {#create-internalized-com.aspose.ms.System.DateTime-}
```
public static XmpDate create_internalized(System.DateTime dateTime)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dateTime | com.aspose.ms.System.DateTime |  |

**Returns:**
[XmpDate](../../com.aspose.psd.xmp.types.basic/xmpdate)
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
### getFormat() {#getFormat--}
```
public String getFormat()
```


वर्तमान मान के लिए फ़ॉर्मेट स्ट्रिंग प्राप्त करता है।

मान: वर्तमान मान के लिए फ़ॉर्मेट स्ट्रिंग।

**Returns:**
java.lang.String
### getValue() {#getValue--}
```
public Date getValue()
```


तारीख मान को प्राप्त करता है या सेट करता है।

मान: तारीख मान।

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


XMP प्रारूप में सम्मिलित स्ट्रिंग मान लौटाता है।

**Returns:**
java.lang.String - XMP प्रारूप में सम्मिलित स्ट्रिंग मान लौटाता है।
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


तारीख मान को प्राप्त करता है या सेट करता है।

मान: तारीख मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

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

