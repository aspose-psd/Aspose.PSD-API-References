---
title: "समय"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "सेकंड में समय मान का प्रतिनिधित्व।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.xmp.schemas.xmpdm/time/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase)
```
public final class Time extends XmpTypeBase
```

सेकंड में समय मान का प्रतिनिधित्व।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Time(Rational scale, int value)](#Time-com.aspose.psd.xmp.types.derived.Rational-int-) | एक नया उदाहरण Time वर्ग को प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getScale()](#getScale--) | समय मान के लिए स्केल प्राप्त करता है या सेट करता है। |
| [getValue()](#getValue--) | निर्दिष्ट स्केल में समय मान प्राप्त करता है या सेट करता है। |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP प्रारूप में सम्मिलित स्ट्रिंग मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setScale(Rational value)](#setScale-com.aspose.psd.xmp.types.derived.Rational-) | समय मान के लिए स्केल प्राप्त करता है या सेट करता है। |
| [setValue(int value)](#setValue-int-) | निर्दिष्ट स्केल में समय मान प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Time(Rational scale, int value) {#Time-com.aspose.psd.xmp.types.derived.Rational-int-}
```
public Time(Rational scale, int value)
```


एक नया उदाहरण Time वर्ग को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scale | [Rational](../../com.aspose.psd.xmp.types.derived/rational) | स्केल। |
| मान | int | मान। |

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
### getScale() {#getScale--}
```
public Rational getScale()
```


समय मान के लिए स्केल प्राप्त करता है या सेट करता है।

NTSC के लिए, 1001/30000 उपयोग करें, या कम सटीक 100/2997। PAL के लिए, 1/25 उपयोग करें। मान: समय मान के लिए स्केल।

**Returns:**
[Rational](../../com.aspose.psd.xmp.types.derived/rational)
### getValue() {#getValue--}
```
public int getValue()
```


निर्दिष्ट स्केल में समय मान प्राप्त करता है या सेट करता है।

मान: निर्दिष्ट स्केल में समय मान।

**Returns:**
int
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




### setScale(Rational value) {#setScale-com.aspose.psd.xmp.types.derived.Rational-}
```
public void setScale(Rational value)
```


समय मान के लिए स्केल प्राप्त करता है या सेट करता है।

NTSC के लिए, 1001/30000 उपयोग करें, या कम सटीक 100/2997। PAL के लिए, 1/25 उपयोग करें। मान: समय मान के लिए स्केल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rational](../../com.aspose.psd.xmp.types.derived/rational) |  |

### setValue(int value) {#setValue-int-}
```
public void setValue(int value)
```


निर्दिष्ट स्केल में समय मान प्राप्त करता है या सेट करता है।

मान: निर्दिष्ट स्केल में समय मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

