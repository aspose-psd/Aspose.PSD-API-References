---
title: "ColorComponent"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "कलर कंपोनेंट चैनल वैल्यू और चैनल वैल्यू का एक एब्स्ट्रैक्शन है।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Color component, Channel Value और Channel Value का एक सार है। कोई भी color, ColorComponent की एक array से बना होता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | नया instance of the [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) क्लास को प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Color Component/Channel की Bit Depth प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Color Component का विवरण प्राप्त करता है। |
| [getFullName()](#getFullName--) | नाम और स्पेस-सेपरेटेड विवरण के साथ color component का पूर्ण नाम प्राप्त करता है। |
| [getName()](#getName--) | color component का नाम प्राप्त करता है। |
| [getPermittedFullNames()](#getPermittedFullNames--) | अनुमत पूर्ण नाम प्राप्त करता है। |
| [getValue()](#getValue--) | मान को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | मान को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


नया instance of the [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) क्लास को प्रारंभ करता है। कृपया जांचें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitDepth | byte | बिट गहराई। |
| fullName | java.lang.String | पूर्ण नाम। |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Color Component/Channel की Bit Depth प्राप्त करता है।

Value: Bit Depth।

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Color Component का विवरण प्राप्त करता है।

मान: विवरण।

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


नाम और स्पेस-सेपरेटेड विवरण के साथ color component का पूर्ण नाम प्राप्त करता है।

मान: पूर्ण नाम।

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


color component का नाम प्राप्त करता है।

मान: नाम।

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


अनुमत पूर्ण नाम प्राप्त करता है।

मान: अनुमत पूर्ण नाम।

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


मान को प्राप्त करता है या सेट करता है। कृपया ध्यान दें, यदि आप मान को वर्तमान बिट गहराई में संग्रहीत अधिकतम से अधिक सेट करने का प्रयास करते हैं, तो आपको एक अपवाद मिलेगा।

मान: वह मान।

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


मान को प्राप्त करता है या सेट करता है। कृपया ध्यान दें, यदि आप मान को वर्तमान बिट गहराई में संग्रहीत अधिकतम से अधिक सेट करने का प्रयास करते हैं, तो आपको एक अपवाद मिलेगा।

मान: वह मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

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

