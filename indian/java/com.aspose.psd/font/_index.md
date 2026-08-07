---
title: "फ़ॉन्ट"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "फ़ॉन्ट फ़ेस आकार और शैली गुणों सहित पाठ के लिए एक विशिष्ट स्वरूप परिभाषित करता है।"
type: docs
weight: 46
url: /hi/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

फ़ॉन्ट फ़ेस, आकार और शैली गुणों सहित पाठ के लिए एक विशिष्ट स्वरूप परिभाषित करता है। इस क्लास को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | एक नया  com.aspose.psd.Font  प्रारंभ करता है जो निर्दिष्ट मौजूदा  com.aspose.psd.Font  और  com.aspose.psd.FontStyle  एनीमरेशन का उपयोग करता है। |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | निर्दिष्ट आकार का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | निर्दिष्ट आकार और शैली का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | निर्दिष्ट आकार, शैली, इकाई और कैरेक्टर सेट का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | निर्दिष्ट आकार, शैली और इकाई का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | इस  Font  की एक सटीक गहरी प्रति बनाता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट ऑब्जेक्ट एक  com.aspose.psd.Font  है और क्या यह इस  com.aspose.psd.Font  के समान प्रॉपर्टी मान रखता है, यह दर्शाता है। |
| [getBold()](#getBold--) | यह दर्शाता है कि यह  Font  बोल्ड है या नहीं, इसका मान प्राप्त करता है। |
| [getCharacterSet()](#getCharacterSet--) | यह प्राप्त करता है वह बाइट मान जो इस  Font  द्वारा उपयोग किए जाने वाले कैरेक्टर सेट को निर्दिष्ट करता है। |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | यह दर्शाता है कि यह  Font  इटैलिक है या नहीं, इसका मान प्राप्त करता है। |
| [getName()](#getName--) | इस  Font  का फ़ेस नाम प्राप्त करता है। |
| [getSize()](#getSize--) | इस  Font  का इम-आकार प्राप्त करता है, जिसे  P:Aspose.Imaging.Font.Unit  प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में मापा जाता है। |
| [getStrikeout()](#getStrikeout--) | यह दर्शाता है कि यह  Font  फ़ॉन्ट के माध्यम से एक क्षैतिज रेखा निर्दिष्ट करता है या नहीं, इसका मान प्राप्त करता है। |
| [getStyle()](#getStyle--) | इस  Font  के लिए शैली जानकारी प्राप्त करता है। |
| [getUnderline()](#getUnderline--) | यह दर्शाता है कि यह  Font  अंडरलाइन है या नहीं, इसका मान प्राप्त करता है। |
| [getUnit()](#getUnit--) | इस  Font  के लिए माप इकाई प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस  com.aspose.psd.Font  का हैश कोड प्राप्त करता है। |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | निर्दिष्ट आकार और इकाई का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | इस  com.aspose.psd.Font  का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


एक नया  com.aspose.psd.Font  प्रारंभ करता है जो निर्दिष्ट मौजूदा  com.aspose.psd.Font  और  com.aspose.psd.FontStyle  एनीमरेशन का उपयोग करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | वह मौजूदा  com.aspose.psd.Font  जिससे नया  com.aspose.psd.Font  बनाया जाता है। |
| newStyle | int | नए  com.aspose.psd.Font  पर लागू करने के लिए  com.aspose.psd.FontStyle  ।  com.aspose.psd.FontStyle  एनीमरेशन के कई मान OR ऑपरेटर से संयोजित किए जा सकते हैं। |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


निर्दिष्ट आकार का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। कैरेक्टर सेट को  F:Aspose.Imaging.CharacterSet.Default , ग्राफ़िक्स यूनिट को  F:Aspose.Imaging.GraphicsUnit.Point , और फ़ॉन्ट शैली को  F:Aspose.Imaging.FontStyle.Regular  पर सेट किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | float | नए फ़ॉन्ट का em-size, पॉइंट्स में। |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


निर्दिष्ट आकार और शैली का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। कैरेक्टर सेट को  F:Aspose.Imaging.CharacterSet.Default , ग्राफ़िक्स यूनिट को  F:Aspose.Imaging.GraphicsUnit.Point  पर सेट किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | float | नए फ़ॉन्ट का em-size, पॉइंट्स में। |
| style | int | नए फ़ॉन्ट का  com.aspose.psd.FontStyle . |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


निर्दिष्ट आकार, शैली, इकाई और कैरेक्टर सेट का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | float | नए फ़ॉन्ट का em-size, वह इकाइयों में जो  unit  पैरामीटर द्वारा निर्दिष्ट हैं। |
| style | int | नए फ़ॉन्ट का  com.aspose.psd.FontStyle . |
| unit | int | नए फ़ॉन्ट का  com.aspose.psd.GraphicsUnit . |
| characterSet | int | इस फ़ॉन्ट के लिए उपयोग करने वाला एक कैरेक्टर सेट। |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


निर्दिष्ट आकार, शैली और इकाई का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | float | नए फ़ॉन्ट का em-size, वह इकाइयों में जो  unit  पैरामीटर द्वारा निर्दिष्ट हैं। |
| style | int | नए फ़ॉन्ट का  com.aspose.psd.FontStyle . |
| unit | int | नए फ़ॉन्ट का  com.aspose.psd.GraphicsUnit . |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


इस  Font  की एक सटीक गहरी प्रति बनाता है।

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट ऑब्जेक्ट एक  com.aspose.psd.Font  है और क्या यह इस  com.aspose.psd.Font  के समान प्रॉपर्टी मान रखता है, यह दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | परीक्षण करने के लिए वस्तु। |

**Returns:**
boolean - true यदि  obj  पैरामीटर एक  com.aspose.psd.Font  है और इस  com.aspose.psd.Font  के समान प्रॉपर्टी मान रखता है; अन्यथा, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


यह दर्शाता है कि यह  Font  बोल्ड है या नहीं, इसका मान प्राप्त करता है।

**Returns:**
boolean - true यदि यह  Font  बोल्ड है; अन्यथा, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


यह प्राप्त करता है वह बाइट मान जो इस  Font  द्वारा उपयोग किए जाने वाले कैरेक्टर सेट को निर्दिष्ट करता है।

**Returns:**
int - वह कैरेक्टर सेट जो यह  Font  उपयोग करता है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


यह दर्शाता है कि यह  Font  इटैलिक है या नहीं, इसका मान प्राप्त करता है।

**Returns:**
boolean - true यदि यह  Font  इटैलिक है; अन्यथा, false.
### getName() {#getName--}
```
public String getName()
```


इस  Font  का फ़ेस नाम प्राप्त करता है।

**Returns:**
java.lang.String - इस  Font  के फेस नाम का स्ट्रिंग प्रतिनिधित्व।
### getSize() {#getSize--}
```
public float getSize()
```


इस  Font  का इम-आकार प्राप्त करता है, जिसे  P:Aspose.Imaging.Font.Unit  प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में मापा जाता है।

**Returns:**
float - इस  Font  का em-size।
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


यह दर्शाता है कि यह  Font  फ़ॉन्ट के माध्यम से एक क्षैतिज रेखा निर्दिष्ट करता है या नहीं, इसका मान प्राप्त करता है।

**Returns:**
boolean - true यदि इस  Font  पर एक क्षैतिज रेखा है; अन्यथा, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


इस  Font  के लिए शैली जानकारी प्राप्त करता है।

**Returns:**
int - एक  FontStyle  एन्यूमरेशन जिसमें इस  Font  के लिए शैली जानकारी होती है।
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


यह दर्शाता है कि यह  Font  अंडरलाइन है या नहीं, इसका मान प्राप्त करता है।

**Returns:**
boolean - true यदि यह  Font  अंडरलाइन किया गया है; अन्यथा, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


इस  Font  के लिए माप इकाई प्राप्त करता है।

**Returns:**
int - एक  GraphicsUnit  जो इस  Font  के माप इकाई को दर्शाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस  com.aspose.psd.Font  का हैश कोड प्राप्त करता है।

**Returns:**
int - इस  com.aspose.psd.Font  का हैश कोड।
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


निर्दिष्ट आकार और इकाई का उपयोग करके एक नया  com.aspose.psd.Font  प्रारंभ करता है। कैरेक्टर सेट को  F:Aspose.Imaging.CharacterSet.Default , शैली को  F:Aspose.Imaging.FontStyle.Regular  पर सेट किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  नाम का स्ट्रिंग प्रतिनिधित्व। |
| emSize | float | नए फ़ॉन्ट का em-size, वह इकाइयों में जो  unit  पैरामीटर द्वारा निर्दिष्ट हैं। |
| unit | int | नए फ़ॉन्ट का  com.aspose.psd.GraphicsUnit . |

**Returns:**
[Font](../../com.aspose.psd/font)
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


इस  com.aspose.psd.Font  का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस  com.aspose.psd.Font  को दर्शाती है।
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

