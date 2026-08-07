---
title: "ResourceEvent"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "खींचे गए ऑब्जेक्ट के आयाम शामिल हैं।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

खींचे गए ऑब्जेक्ट के आयाम शामिल हैं।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | ResourceEvent वर्ग का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | निर्दिष्ट कुंजी जोड़ता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | क्रिया प्राप्त करता है। |
| [getActionDate()](#getActionDate--) | क्रिया तिथि को प्राप्त करता है या सेट करता है। |
| [getChanged()](#getChanged--) | पिछले इवेंट इतिहास से अब तक बदले गए संसाधन के भागों की सेमीकोलन-सेपरेटेड सूची प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | xmpMM:InstanceId का मान प्राप्त करता है। |
| [getNamespaceUri()](#getNamespaceUri--) | डिफ़ॉल्ट नेमस्पेस URI को प्राप्त करता है। |
| [getParameters()](#getParameters--) | क्रिया का अतिरिक्त विवरण प्राप्त करता है या सेट करता है। |
| [getPrefix()](#getPrefix--) | प्रिफिक्स को प्राप्त करता है। |
| [getSofwareAgentName()](#getSofwareAgentName--) | सॉफ़्टवेयर एजेंट का नाम प्राप्त करता है या सेट करता है। |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP प्रारूप में सम्मिलित स्ट्रिंग मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | क्रिया सेट करता है। |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | क्रिया तिथि को प्राप्त करता है या सेट करता है। |
| [setChanged(String value)](#setChanged-java.lang.String-) | पिछले इवेंट इतिहास से अब तक बदले गए संसाधन के भागों की सेमीकोलन-सेपरेटेड सूची सेट करता है। |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | xmpMM:InstanceId का मान प्राप्त करता है या सेट करता है। |
| [setParameters(String value)](#setParameters-java.lang.String-) | क्रिया का अतिरिक्त विवरण प्राप्त करता है या सेट करता है। |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | सॉफ़्टवेयर एजेंट का नाम प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


ResourceEvent वर्ग का नया उदाहरण प्रारंभ करता है।

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


निर्दिष्ट कुंजी जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | कुंजी का स्ट्रिंग प्रतिनिधित्व जो जोड़े गए मान के साथ पहचाना जाता है। |
| मान | java.lang.Object | जोड़ने के लिए मान। |

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
### getAction() {#getAction--}
```
public String getAction()
```


क्रिया प्राप्त करता है।

परिभाषित मान हैं: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved। नए मान भूतकाल में क्रिया रूप होने चाहिए।

**Returns:**
java.lang.String - क्रिया।
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


क्रिया तिथि को प्राप्त करता है या सेट करता है।

**Returns:**
java.util.Date - क्रिया तिथि।
### getChanged() {#getChanged--}
```
public String getChanged()
```


पिछले इवेंट इतिहास से अब तक बदले गए संसाधन के भागों की सेमीकोलन-सेपरेटेड सूची प्राप्त करता है।

**Returns:**
java.lang.String - पिछले इवेंट इतिहास से अब तक बदले गए संसाधन के भागों की सेमीकोलन-सेपरेटेड सूची।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


xmpMM:InstanceId का मान प्राप्त करता है।

**Returns:**
java.util.UUID - xmpMM:InstanceId का मान.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


डिफ़ॉल्ट नेमस्पेस URI को प्राप्त करता है।

**Returns:**
java.lang.String - डिफ़ॉल्ट नेमस्पेस URI।
### getParameters() {#getParameters--}
```
public String getParameters()
```


क्रिया का अतिरिक्त विवरण प्राप्त करता है या सेट करता है।

Value: कार्रवाई का अतिरिक्त विवरण।

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


प्रिफिक्स को प्राप्त करता है।

**Returns:**
java.lang.String - उपसर्ग।
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


सॉफ़्टवेयर एजेंट का नाम प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String - सॉफ़्टवेयर एजेंट का नाम।
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP प्रारूप में सम्मिलित स्ट्रिंग मान प्राप्त करता है।

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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


क्रिया सेट करता है।

परिभाषित मान हैं: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved। नए मान भूतकाल में क्रिया रूप होने चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | कार्रवाई। |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


क्रिया तिथि को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date | कार्रवाई की तिथि। |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


पिछले इवेंट इतिहास से अब तक बदले गए संसाधन के भागों की सेमीकोलन-सेपरेटेड सूची सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | सेमीकोलन-डिलिमिटेड सूची उन संसाधन भागों की जो पिछले इवेंट इतिहास से बदल गई हैं। |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


xmpMM:InstanceId का मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.UUID | xmpMM:InstanceId का मान। |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


क्रिया का अतिरिक्त विवरण प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | कार्रवाई का अतिरिक्त विवरण। |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


सॉफ़्टवेयर एजेंट का नाम प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | सॉफ़्टवेयर एजेंट का नाम। |

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

