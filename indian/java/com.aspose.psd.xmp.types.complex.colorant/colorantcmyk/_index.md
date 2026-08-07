---
title: "ColorantCmyk"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "CMYK कलरेंट का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

CMYK कलरेंट का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | एक नया उदाहरण  ColorantCmyk  क्लास का आरंभ करता है। |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | एक नया उदाहरण  ColorantCmyk  क्लास का आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | CMYK कलरेंट में अधिकतम रंग मान। |
| [ColorValueMin](#ColorValueMin) | CMYK कलरेंट में न्यूनतम रंग मान। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | निर्दिष्ट कुंजी जोड़ता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | ब्लैक घटक मान को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | रंग के प्रकार को प्राप्त करता है या सेट करता है। |
| [getCyan()](#getCyan--) | सियान घटक मान को प्राप्त करता है या सेट करता है। |
| [getMagenta()](#getMagenta--) | मैजेंटा घटक मान को प्राप्त करता है या सेट करता है। |
| [getMode()](#getMode--) | प्राप्त करता है  ColorMode । |
| [getNamespaceUri()](#getNamespaceUri--) | डिफ़ॉल्ट नेमस्पेस URI को प्राप्त करता है। |
| [getPrefix()](#getPrefix--) | प्रिफिक्स को प्राप्त करता है। |
| [getSwatchName()](#getSwatchName--) | स्वैच का नाम प्राप्त करता है या सेट करता है। |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP प्रारूप में सम्मिलित स्ट्रिंग मान प्राप्त करता है। |
| [getYellow()](#getYellow--) | येलो घटक मान को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | ब्लैक घटक मान को प्राप्त करता है या सेट करता है। |
| [setColorType(int value)](#setColorType-int-) | रंग के प्रकार को प्राप्त करता है या सेट करता है। |
| [setCyan(float value)](#setCyan-float-) | सियान घटक मान को प्राप्त करता है या सेट करता है। |
| [setMagenta(float value)](#setMagenta-float-) | मैजेंटा घटक मान को प्राप्त करता है या सेट करता है। |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | स्वैच का नाम प्राप्त करता है या सेट करता है। |
| [setYellow(float value)](#setYellow-float-) | येलो घटक मान को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


एक नया उदाहरण  ColorantCmyk  क्लास का आरंभ करता है।

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


एक नया उदाहरण  ColorantCmyk  क्लास का आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ब्लैक | float | काले घटक का मान। |
| सियान | float | सियान रंग घटक का मान। |
| मैजेंटा | float | मैजेंटा घटक का मान। |
| पीला | float | पीले घटक का मान। |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


CMYK कलरेंट में अधिकतम रंग मान।

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


CMYK कलरेंट में न्यूनतम रंग मान।

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


ब्लैक घटक मान को प्राप्त करता है या सेट करता है।

मान: काले घटक का मान।

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


रंग के प्रकार को प्राप्त करता है या सेट करता है।

मान: रंग का प्रकार।

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


सियान घटक मान को प्राप्त करता है या सेट करता है।

मान: सियान घटक का मान।

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


मैजेंटा घटक मान को प्राप्त करता है या सेट करता है।

मान: मैजेंटा घटक का मान।

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


प्राप्त करता है  ColorMode ।

मान: रंग मोड।

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


डिफ़ॉल्ट नेमस्पेस URI को प्राप्त करता है।

**Returns:**
java.lang.String - डिफ़ॉल्ट नेमस्पेस URI।
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


प्रिफिक्स को प्राप्त करता है।

**Returns:**
java.lang.String - उपसर्ग।
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


स्वैच का नाम प्राप्त करता है या सेट करता है।

मान: स्वैच का नाम।

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP प्रारूप में सम्मिलित स्ट्रिंग मान प्राप्त करता है।

**Returns:**
java.lang.String - XMP प्रारूप में सम्मिलित स्ट्रिंग मान लौटाता है।
### getYellow() {#getYellow--}
```
public float getYellow()
```


येलो घटक मान को प्राप्त करता है या सेट करता है।

मान: पीले घटक का मान।

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


ब्लैक घटक मान को प्राप्त करता है या सेट करता है।

मान: काले घटक का मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


रंग के प्रकार को प्राप्त करता है या सेट करता है।

मान: रंग का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


सियान घटक मान को प्राप्त करता है या सेट करता है।

मान: सियान घटक का मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


मैजेंटा घटक मान को प्राप्त करता है या सेट करता है।

मान: मैजेंटा घटक का मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


स्वैच का नाम प्राप्त करता है या सेट करता है।

मान: स्वैच का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


येलो घटक मान को प्राप्त करता है या सेट करता है।

मान: पीले घटक का मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

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

