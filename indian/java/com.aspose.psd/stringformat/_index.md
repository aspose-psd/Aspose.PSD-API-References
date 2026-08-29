---
title: "StringFormat"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "पाठ लेआउट जानकारी को समेटता है जैसे संरेखण, अभिविन्यास और टैब स्टॉप्स, तथा डिस्प्ले हेरफेर जैसे बिंदु-तीन (ellipsis) सम्मिलन, राष्ट्रीय अंक प्रतिस्थापन और OpenType सुविधाएँ।"
type: docs
weight: 106
url: /hi/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

पाठ लेआउट जानकारी (जैसे संरेखण, अभिविन्यास और टैब स्टॉप्स) को समेटता है, डिस्प्ले हेरफेर (जैसे बिंदु-तीन (ellipsis) सम्मिलन और राष्ट्रीय अंक प्रतिस्थापन) और OpenType सुविधाएँ। इस क्लास को विरासत में नहीं लिया जा सकता।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [StringFormat()](#StringFormat--) | एक नया  com.aspose.psd.StringFormat  ऑब्जेक्ट प्रारंभ करता है। |
| [StringFormat(int options)](#StringFormat-int-) | निर्दिष्ट  com.aspose.psd.StringFormatFlags  एन्यूमरेशन और भाषा के साथ एक नया  com.aspose.psd.StringFormat  ऑब्जेक्ट प्रारंभ करता है। |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | निर्दिष्ट मौजूदा  com.aspose.psd.StringFormat  ऑब्जेक्ट से एक नया  com.aspose.psd.StringFormat  ऑब्जेक्ट प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [close()](#close--) | Closable इंटरफ़ेस को लागू करता है और JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। |
| [deepClone()](#deepClone--) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट की गहरी क्लोन बनाता है। |
| [dispose()](#dispose--) | वर्तमान उदाहरण को नष्ट करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | उस भाषा को प्राप्त करता है जो स्थानीय अंकों को पश्चिमी अंकों के स्थान पर प्रतिस्थापित करने पर उपयोग होती है। |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि प्राप्त करता है। |
| [getDisposed()](#getDisposed--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं। |
| [getFirstTabOffset()](#getFirstTabOffset--) | पाठ की पंक्ति की शुरुआत और पहले टैब स्टॉप के बीच स्पेस की संख्या प्राप्त करता है। |
| [getFormatFlags()](#getFormatFlags--) | एक  com.aspose.psd.StringFormatFlags  एन्यूमरेशन प्राप्त करता है जिसमें स्वरूपण जानकारी होती है। |
| [getGenericDefault()](#getGenericDefault--) | एक सामान्य डिफ़ॉल्ट  com.aspose.psd.StringFormat  ऑब्जेक्ट प्राप्त करता है। |
| [getGenericTypographic()](#getGenericTypographic--) | एक सामान्य टाइपोग्राफिक  com.aspose.psd.StringFormat  ऑब्जेक्ट प्राप्त करता है। |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.HotkeyPrefix  ऑब्जेक्ट प्राप्त करता है। |
| [getLineAlignment()](#getLineAlignment--) | क्षैतिज तल पर पंक्ति संरेखण प्राप्त करता है। |
| [getTabStops()](#getTabStops--) |   P:Aspose.Imaging.getGraphics().PageUnit  प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में टैब स्टॉप्स के बीच दूरी की एक सरणी प्राप्त करता है। |
| [getTrimming()](#getTrimming--) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.StringTrimming  एन्यूमरेशन प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी सेट करता है। |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | स्थानीय अंकों को पश्चिमी अंकों के साथ बदलने पर उपयोग की जाने वाली भाषा सेट करता है। |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि सेट करता है। |
| [setFormatFlags(int value)](#setFormatFlags-int-) | फ़ॉर्मेटिंग जानकारी वाला  com.aspose.psd.StringFormatFlags  एन्यूमरेशन सेट करता है। |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.HotkeyPrefix  ऑब्जेक्ट सेट करता है। |
| [setLineAlignment(int value)](#setLineAlignment-int-) | क्षैतिज तल पर पंक्ति संरेखण सेट करता है। |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए टैब स्टॉप सेट करता है। |
| [setTrimming(int value)](#setTrimming-int-) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.StringTrimming  एन्यूमरेशन सेट करता है। |
| [toString()](#toString--) | इस  com.aspose.psd.StringFormat  ऑब्जेक्ट को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


एक नया  com.aspose.psd.StringFormat  ऑब्जेक्ट प्रारंभ करता है।

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


निर्दिष्ट  com.aspose.psd.StringFormatFlags  एन्यूमरेशन और भाषा के साथ एक नया  com.aspose.psd.StringFormat  ऑब्जेक्ट प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विकल्प | int | नए  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.StringFormatFlags  एन्यूमरेशन। |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


निर्दिष्ट मौजूदा  com.aspose.psd.StringFormat  ऑब्जेक्ट से एक नया  com.aspose.psd.StringFormat  ऑब्जेक्ट प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | नए  com.aspose.psd.StringFormat  ऑब्जेक्ट को प्रारंभ करने के लिए  com.aspose.psd.StringFormat  ऑब्जेक्ट। |

### close() {#close--}
```
public void close()
```


Closable इंटरफ़ेस को लागू करता है और इसे JDK 1.7 से try-with-resources स्टेटमेंट में उपयोग किया जा सकता है। यह मेथड केवल dispose method को कॉल करता है।

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट की गहरी क्लोन बनाता है।

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


वर्तमान उदाहरण को नष्ट करता है।

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी प्राप्त करता है।

**Returns:**
int - एक  com.aspose.psd.StringAlignment  एन्यूमरेशन जो पाठ संरेखण जानकारी निर्दिष्ट करता है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


उस भाषा को प्राप्त करता है जो स्थानीय अंकों को पश्चिमी अंकों के स्थान पर प्रतिस्थापित करने पर उपयोग होती है।

**Returns:**
int - एक राष्ट्रीय भाषा समर्थन (NLS) भाषा पहचानकर्ता जो उस भाषा को पहचानता है जिसका उपयोग स्थानीय अंकों को पश्चिमी अंकों के साथ बदलने पर किया जाएगा। आप  P:System.Globalization.CultureInfo.LCID  प्रॉपर्टी को एक  System.Globalization.CultureInfo  ऑब्जेक्ट की NLS भाषा पहचानकर्ता के रूप में पास कर सकते हैं। उदाहरण के लिए, मान लीजिए आप एक  System.Globalization.CultureInfo  ऑब्जेक्ट बनाते हैं जिसमें स्ट्रिंग "ar-EG" को  System.Globalization.CultureInfo  कंस्ट्रक्टर में पास किया जाता है। यदि आप उस  System.Globalization.CultureInfo  ऑब्जेक्ट की  P:System.Globalization.CultureInfo.LCID  प्रॉपर्टी को  com.aspose.psd.StringDigitSubstitute.Traditional  के साथ  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  मेथड को पास करते हैं, तो डिस्प्ले समय पर अरबी-इंडिक अंक पश्चिमी अंकों के साथ बदल दिए जाएंगे।

पुराने मेथड setDigitSubstitution के लिए सेट्टर पेश किया गया है।
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि प्राप्त करता है।

**Returns:**
int - एक  com.aspose.psd.StringDigitSubstitute  एन्यूमरेशन मान जो यह निर्दिष्ट करता है कि उन अक्षरों को कैसे बदलें जो वर्तमान फ़ॉन्ट द्वारा समर्थित न होने के कारण प्रदर्शित नहीं हो सकते।

पुराने मेथड SetDigitSubstitution के लिए सेट्टर पेश किया गया है।
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़्ड है या नहीं।

**Returns:**
boolean - यदि डिस्पोज़ किया गया हो तो true; अन्यथा false।
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


पाठ की पंक्ति की शुरुआत और पहले टैब स्टॉप के बीच स्पेस की संख्या प्राप्त करता है।

**Returns:**
float - पहला टैब ऑफ़सेट।

हटाए गए मेथड GetTabStops के लिए प्रॉपर्टी पेश की गई है।
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


एक  com.aspose.psd.StringFormatFlags  एन्यूमरेशन प्राप्त करता है जिसमें स्वरूपण जानकारी होती है।

**Returns:**
int - एक  com.aspose.psd.StringFormatFlags  एन्यूमरेशन जिसमें फ़ॉर्मेटिंग जानकारी होती है।
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


एक सामान्य डिफ़ॉल्ट  com.aspose.psd.StringFormat  ऑब्जेक्ट प्राप्त करता है।

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


एक सामान्य टाइपोग्राफिक  com.aspose.psd.StringFormat  ऑब्जेक्ट प्राप्त करता है।

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.HotkeyPrefix  ऑब्जेक्ट प्राप्त करता है।

**Returns:**
int - इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.HotkeyPrefix  ऑब्जेक्ट, डिफ़ॉल्ट है  F:Aspose.Imaging.HotkeyPrefix.None ।
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


क्षैतिज तल पर पंक्ति संरेखण प्राप्त करता है।

**Returns:**
int - एक  com.aspose.psd.StringAlignment  एन्यूमरेशन जो पंक्ति संरेखण का प्रतिनिधित्व करता है।
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


  P:Aspose.Imaging.getGraphics().PageUnit  प्रॉपर्टी द्वारा निर्दिष्ट इकाइयों में टैब स्टॉप्स के बीच दूरी की एक सरणी प्राप्त करता है।

**Returns:**
float[] - टैब स्टॉप्स।

हटाए गए मेथड GetTabStops के लिए प्रॉपर्टी पेश की गई है।
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.StringTrimming  एन्यूमरेशन प्राप्त करता है।

**Returns:**
int - एक  com.aspose.psd.StringTrimming  एन्यूमरेशन जो यह दर्शाता है कि इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के साथ खींचा गया पाठ लेआउट आयत के किनारों से अधिक होने पर कैसे ट्रिम किया जाता है।
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


ऊर्ध्वाधर तल पर पाठ संरेखण जानकारी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक  com.aspose.psd.StringAlignment  एन्यूमरेशन जो पाठ संरेखण जानकारी निर्दिष्ट करता है। |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


स्थानीय अंकों को पश्चिमी अंकों के साथ बदलने पर उपयोग की जाने वाली भाषा सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | एक राष्ट्रीय भाषा समर्थन (NLS) भाषा पहचानकर्ता जो उस भाषा को पहचानता है जिसका उपयोग स्थानीय अंकों को पश्चिमी अंकों के साथ बदलने पर किया जाएगा। आप  P:System.Globalization.CultureInfo.LCID  प्रॉपर्टी को एक  System.Globalization.CultureInfo  ऑब्जेक्ट की NLS भाषा पहचानकर्ता के रूप में पास कर सकते हैं। उदाहरण के लिए, मान लीजिए आप एक  System.Globalization.CultureInfo  ऑब्जेक्ट बनाते हैं जिसमें स्ट्रिंग "ar-EG" को  System.Globalization.CultureInfo  कंस्ट्रक्टर में पास किया जाता है। यदि आप उस  System.Globalization.CultureInfo  ऑब्जेक्ट की  P:System.Globalization.CultureInfo.LCID  प्रॉपर्टी को  com.aspose.psd.StringDigitSubstitute.Traditional  के साथ  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  मेथड को पास करते हैं, तो डिस्प्ले समय पर अरबी-इंडिक अंक पश्चिमी अंकों के साथ बदल दिए जाएंगे। |

सेटर को पुरानी विधि SetDigitSubstitution के लिए पेश किया गया है। |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


अंक प्रतिस्थापन के लिए उपयोग की जाने वाली विधि सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | एक  com.aspose.psd.StringDigitSubstitute  एन्यूमरेशन मान जो यह निर्दिष्ट करता है कि उन अक्षरों को कैसे बदलना है जो वर्तमान फ़ॉन्ट द्वारा समर्थित न होने के कारण प्रदर्शित नहीं किए जा सकते। |

सेटर को पुरानी विधि SetDigitSubstitution के लिए पेश किया गया है। |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


फ़ॉर्मेटिंग जानकारी वाला  com.aspose.psd.StringFormatFlags  एन्यूमरेशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक  com.aspose.psd.StringFormatFlags  एन्यूमरेशन जिसमें स्वरूपण जानकारी शामिल है। |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.HotkeyPrefix  ऑब्जेक्ट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | इस  com.aspose.psd.StringFormat  वस्तु के लिए  com.aspose.psd.HotkeyPrefix  ऑब्जेक्ट, डिफ़ॉल्ट है  F:Aspose.Imaging.HotkeyPrefix.None । |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


क्षैतिज तल पर पंक्ति संरेखण सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक  com.aspose.psd.StringAlignment  एन्यूमरेशन जो पंक्ति संरेखण को दर्शाता है। |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए टैब स्टॉप सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| firstTabOffset | float | पाठ की एक पंक्ति की शुरुआत और पहले टैब स्टॉप के बीच स्पेस की संख्या। |
| tabStops | float[] | एक एरे जिसमें टैब स्टॉप्स के बीच की दूरी उन इकाइयों में है जो  com.aspose.psd.Graphics.PageUnit  प्रॉपर्टी द्वारा निर्दिष्ट की गई हैं। |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के लिए  com.aspose.psd.StringTrimming  एन्यूमरेशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | एक  com.aspose.psd.StringTrimming  एन्यूमरेशन जो यह दर्शाता है कि इस  com.aspose.psd.StringFormat  ऑब्जेक्ट के साथ खींचा गया पाठ लेआउट आयत के किनारों से अधिक होने पर कैसे ट्रिम किया जाता है। |

### toString() {#toString--}
```
public String toString()
```


इस  com.aspose.psd.StringFormat  ऑब्जेक्ट को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है।

**Returns:**
java.lang.String - इस  com.aspose.psd.StringFormat  ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व।
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

