---
title: "RawColor"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Raw Color क्लास किसी भी चैनल गिनती, किसी भी रंग मोड और किसी भी बिट डेप्थ के साथ रंगों को संग्रहीत करने में मदद करती है। कृपया ध्यान दें कि कुछ आंतरिक क्लासें RawColor को उसके मूल स्वरूप में परिवर्तित करने में समस्याएँ पैदा कर सकती हैं, इसलिए यदि API आपके लिए CMYK रंग प्रदान करती है तो प्रदान किए गए स्वरूप का उपयोग करना अधिक विश्वसनीय है।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color क्लास किसी भी चैनल गिनती, किसी भी रंग मोड और किसी भी बिट डेप्थ के साथ रंगों को संग्रहीत करने में मदद करती है। कृपया ध्यान दें, कुछ आंतरिक क्लासें RawColor को उसके मूल स्वरूप में परिवर्तित करने में समस्याएँ पैदा कर सकती हैं, इसलिए यदि API आपके लिए CMYK रंग प्रदान करती है तो प्रदान किए गए स्वरूप का उपयोग करना अधिक विश्वसनीय है। साथ ही, कुछ मामलों में Raw Color को परिवर्तित किया जा सकता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | नए [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) क्लास का एक नया उदाहरण प्रारंभ करता है। |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | पूर्वनिर्धारित रंग मोड का उपयोग करके पिक्सेल डेटा फ़ॉर्मेट से [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं। |
| [getAsInt()](#getAsInt--) | यदि संभव हो तो रंग को int के रूप में प्राप्त करता है। |
| [getAsLong()](#getAsLong--) | यदि संभव हो तो रंग को long के रूप में प्राप्त करता है। |
| [getBitDepth()](#getBitDepth--) | Raw Color की बिट डेप्थ प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | रंग के लिए अनुसरण करने वाला मोड। |
| [getColorModeName()](#getColorModeName--) | रंग मोड का नाम प्राप्त करता है। |
| [getComponents()](#getComponents--) | रंग के घटकों को प्राप्त करता है। |
| [hashCode()](#hashCode--) | वर्तमान ऑब्जेक्ट का हैश कोड प्राप्त करें। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | ऑपरेटर == को लागू करता है। |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | ऑपरेटर != को लागू करता है। |
| [setAsInt(int value)](#setAsInt-int-) | यदि संभव हो तो int तर्क से सभी चैनलों के डेटा को सेट करता है। |
| [setAsLong(long value)](#setAsLong-long-) | यदि संभव हो तो int तर्क से सभी चैनलों के डेटा को सेट करता है। |
| [setColorMode(short value)](#setColorMode-short-) | रंग के लिए अनुसरण करने वाला मोड। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


नए [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | कस्टम रंग घटक। |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


पूर्वनिर्धारित रंग मोड का उपयोग करके पिक्सेल डेटा फ़ॉर्मेट से [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | पिक्सेल डेटा फ़ॉर्मेट। |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट इस उदाहरण के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन -  true  यदि निर्दिष्ट ऑब्जेक्ट इस इंस्टेंस के बराबर है; अन्यथा,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


यदि संभव हो तो रंग को int के रूप में प्राप्त करता है।

**Returns:**
int - चैनल डेटा int में संग्रहीत
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


यदि संभव हो तो रंग को long के रूप में प्राप्त करता है।

**Returns:**
long - चैनलों का डेटा Int में संग्रहीत
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Raw Color की Bit Depth प्राप्त करता है। उदाहरण के लिए ARGB रंग के लिए, यदि प्रत्येक चैनल/घटक में 8 बिट हैं तो कुल Bit Depth 32 होती है; पूर्ण ARGB रंग के लिए यदि प्रत्येक चैनल/घटक में 16 बिट हैं तो 64 होती है। Bit Depth चैनलों की Bit Depth के योग से प्राप्त होती है। यह संभव है कि विभिन्न चैनलों की Bit Depth अलग-अलग हों।

**Returns:**
int - सभी चैनलों की Bit Depth का योग
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


रंग के लिए अनुसरण करने वाला मोड।

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


color mode का नाम प्राप्त करता है। color mode का नाम चैनलों/घटकों के नामों से संकलित होता है।

**Returns:**
java.lang.String - color mode नाम वाली स्ट्रिंग
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


color के घटकों को प्राप्त करता है। प्रत्येक घटक एक अलग चैनल है, और यदि आप कम लोकप्रिय color स्कीम का उपयोग करते हैं, तो प्रत्येक चैनल को अलग से संभालना बेहतर है।

Value: color के घटक

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


वर्तमान ऑब्जेक्ट का हैश कोड प्राप्त करें।

**Returns:**
int - हैश कोड।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


ऑपरेटर == को लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | पहला RawColor। |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | दूसरा RawColor। |

**Returns:**
boolean - ऑपरेटर का परिणाम।
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


ऑपरेटर != को लागू करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | पहला RawColor। |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | दूसरा RawColor। |

**Returns:**
boolean - ऑपरेटर का परिणाम।
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


यदि संभव हो तो int तर्क से सभी चैनलों के डेटा को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | component डेटा को समाहित करने वाला int मान |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


यदि संभव हो तो int तर्क से सभी चैनलों के डेटा को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long | component डेटा को समाहित करने वाला int मान |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


रंग के लिए अनुसरण करने वाला मोड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

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

