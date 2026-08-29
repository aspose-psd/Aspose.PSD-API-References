---
title: "Blend"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक मिश्रण पैटर्न को परिभाषित करता है।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

एक ब्लेंड पैटर्न को परिभाषित करता है। इस क्लास को विरासत में नहीं लिया जा सकता।

सामान्य ब्लेंड क्लास का उपयोग ब्रश के लिए ब्लेंड पैटर्न को परिभाषित करना है। इसलिए ब्लेंड प्रॉपर्टीज़ को सावधानीपूर्वक प्रारंभ किया जाना चाहिए। शून्य (null) एरे की अनुमति नहीं है। यदि ब्लेंड फैक्टर्स या पोजीशन एरे खाली हैं या उनकी लंबाई समान नहीं है, तो ब्रश उपयुक्त अपवाद फेंकेगा। यदि पोजीशन एरे में दो या अधिक तत्व हैं तो पहला तत्व 0 और अंतिम तत्व 1 होना चाहिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Blend()](#Blend--) | Blend क्लास का नया उदाहरण प्रारंभ करता है। |
| [Blend(int count)](#Blend-int-) | निर्दिष्ट संख्या के फैक्टर्स और पोजीशन्स के साथ Blend क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | जाँचता है कि निर्दिष्ट ऑब्जेक्ट com.aspose.psd.Blend क्लास है और यह com.aspose.psd.Blend क्लास के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | ग्रेडिएंट के लिए ब्लेंड फैक्टर्स की एरे प्राप्त करता है। |
| [getPositions()](#getPositions--) | ग्रेडिएंट के लिए ब्लेंड पोजीशन्स की एरे प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | ग्रेडिएंट के लिए ब्लेंड फैक्टर्स की एरे सेट करता है। |
| [setPositions(float[] value)](#setPositions-float---) | ग्रेडिएंट के लिए ब्लेंड पोजीशन्स की एरे सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Blend क्लास का नया उदाहरण प्रारंभ करता है। फैक्टर और ब्लेंड एरे में तत्वों की संख्या 1 के बराबर होगी।

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


निर्दिष्ट संख्या के फैक्टर्स और पोजीशन्स के साथ Blend क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| count | int | फैक्टर और पोजीशन एरे में तत्वों की संख्या। |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


जाँचता है कि निर्दिष्ट ऑब्जेक्ट com.aspose.psd.Blend क्लास है और यह com.aspose.psd.Blend क्लास के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए वस्तु। |

**Returns:**
boolean - true यदि obj com.aspose.psd.Blend क्लास इस com.aspose.psd.Blend क्लास के बराबर है; अन्यथा false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


ग्रेडिएंट के लिए ब्लेंड फैक्टर्स की एरे प्राप्त करता है।

**Returns:**
float[] - ब्लेंड फैक्टर्स की एरे जो संबंधित पोजीशन पर उपयोग किए जाने वाले प्रारंभिक रंग और समाप्ति रंग के प्रतिशत निर्दिष्ट करती है।
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


ग्रेडिएंट के लिए ब्लेंड पोजीशन्स की एरे प्राप्त करता है।

**Returns:**
float[] - ब्लेंड पोजीशन्स की एरे जो ग्रेडिएंट लाइन के साथ दूरी के प्रतिशत को निर्दिष्ट करती है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


ग्रेडिएंट के लिए ब्लेंड फैक्टर्स की एरे सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float[] | ब्लेंड फैक्टर्स की एरे जो संबंधित पोजीशन पर उपयोग किए जाने वाले प्रारंभिक रंग और समाप्ति रंग के प्रतिशत को निर्दिष्ट करती है। |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


ग्रेडिएंट के लिए ब्लेंड पोजीशन्स की एरे सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float[] | ब्लेंड पोजीशन्स की एरे जो ग्रेडिएंट लाइन के साथ दूरी के प्रतिशत को निर्दिष्ट करती है। |

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

