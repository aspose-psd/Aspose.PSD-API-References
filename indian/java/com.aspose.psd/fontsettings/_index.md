---
title: "FontSettings"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "सामान्य इमेजिंग वेक्टर फ़ॉर्मेट्स रेंडरर फ़ॉन्ट सेटिंग्स।"
type: docs
weight: 47
url: /hi/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

सामान्य इमेजिंग वेक्टर फ़ॉर्मेट्स रेंडरर फ़ॉन्ट सेटिंग्स।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | डिफ़ॉल्ट फ़ॉन्ट नाम प्राप्त करता है। |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | डिफ़ॉल्ट फ़ॉन्ट फ़ोल्डरों को प्राप्त करता है। |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है। |
| [getFontsFolders()](#getFontsFolders--) | एक एरे की कॉपी प्राप्त करता है जिसमें उन फ़ोल्डरों की सूची होती है जहाँ Aspose.Imaging TrueType फ़ॉन्ट्स खोजता है। |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [get alternative font]। |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | निर्धारित करता है कि [is font allowed] [the specified font name]। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | फ़ॉन्ट कैश फ़ाइल को हटाता है। |
| [reset()](#reset--) | फ़ॉन्ट फ़ोल्डर और डिफ़ॉल्ट फ़ॉन्ट नाम को सिस्टम डिफ़ॉल्ट पर रीसेट करता है। |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | फ़ॉन्ट उपयोग को फ़ॉन्टों की सूची द्वारा प्रतिबंधित करता है। |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | डिफ़ॉल्ट फ़ॉन्ट नाम सेट करता है। |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | फ़ॉन्ट फ़ोल्डर सूची को ओवरराइड करता है  फ़ोल्डर के लिए |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | फ़ॉन्ट फ़ोल्डर सूची को ओवरराइड करता है  फ़ोल्डरों के लिए |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | फ़ोल्डर सेट करता है जहाँ से TrueType फ़ॉन्ट लोड होते हैं और सभी लोड किए गए फ़ॉन्ट साफ़ करता है। |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [get alternative font]। |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | टेक्स्ट लेयर्स वाले PSD फ़ाइलों के लिए फ़ॉन्ट कैश अपडेट करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontFamilyName | java.lang.String | फ़ॉन्ट परिवार नाम। |

**Returns:**
java.lang.String - फ़ॉन्ट परिवार नाम द्वारा एडोब फ़ॉन्ट नाम।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


डिफ़ॉल्ट फ़ॉन्ट नाम प्राप्त करता है।

**Returns:**
java.lang.String - डिफ़ॉल्ट फ़ॉन्ट का नाम
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


डिफ़ॉल्ट फ़ॉन्ट फ़ोल्डरों को प्राप्त करता है।

**Returns:**
java.lang.String[] - सिस्टम फ़ोल्डर लौटाता है
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


फ़ॉन्ट नाम द्वारा फ़ॉन्ट प्रतिस्थापन एरे प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | फ़ॉन्ट का नाम। |

**Returns:**
java.lang.String[] - प्रदान किए गए फ़ॉन्ट्स के प्रतिस्थापन नामों की सरणी
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


एक एरे की कॉपी प्राप्त करता है जिसमें उन फ़ोल्डरों की सूची होती है जहाँ Aspose.Imaging TrueType फ़ॉन्ट्स खोजता है।

वापसी मान Aspose.Imaging द्वारा उपयोग किए गए डेटा की एक प्रति है। यदि आप लौटाए गए सरणी में प्रविष्टियों को बदलते हैं, तो इसका दस्तावेज़ रेंडरिंग पर कोई प्रभाव नहीं पड़ेगा। नई फ़ॉन्ट स्थान निर्दिष्ट करने के लिए  setFontsFolders  मेथड का उपयोग करें।

**Returns:**
java.lang.String[] - वर्तमान फ़ॉन्ट स्थानों की एक प्रति।
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [get alternative font]।

मान:  true  यदि [get alternative font]; अन्यथा,  false ।

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


सबसे उपयुक्त प्रतिस्थापन फ़ॉन्ट प्राप्त करता है। यदि सभी प्रतिस्थापन अनुमत नहीं हैं तो पहला अनुमत और उपलब्ध फ़ॉन्ट लौटाया जाएगा। यदि कोई उपलब्ध फ़ॉन्ट नहीं है तो तर्क से फ़ॉन्ट लौटाया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | फ़ॉन्ट का नाम। |

**Returns:**
java.lang.String - प्रतिस्थापित फ़ॉन्ट का नाम
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


निर्धारित करता है कि [is font allowed] [the specified font name]।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | फ़ॉन्ट का नाम। |

**Returns:**
boolean -  true  यदि [is font allowed] [निर्दिष्ट फ़ॉन्ट नाम]; अन्यथा,  false ।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


फ़ॉन्ट कैश फ़ाइल को हटाता है।

### reset() {#reset--}
```
public static void reset()
```


फ़ॉन्ट फ़ोल्डर और डिफ़ॉल्ट फ़ॉन्ट नाम को सिस्टम डिफ़ॉल्ट पर रीसेट करता है।

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


फ़ॉन्ट को फ़ॉन्ट सूची द्वारा प्रतिबंधित करता है। प्रतिबंध से पहले वास्तविक फ़ॉन्ट नाम जांचें। प्रतिबंध हटाने के लिए अनुमत फ़ॉन्ट सूची को Null सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontList | java.lang.String[] | फ़ॉन्ट सूची। |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


डिफ़ॉल्ट फ़ॉन्ट नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontName | java.lang.String | फ़ॉन्ट का डिफ़ॉल्ट नाम। |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


फ़ॉन्ट प्रतिस्थापन सूची सेट करता है। यदि फ़ॉन्ट अनुमत नहीं है तो प्रतिस्थापन खोजा जाएगा। सूची में पहला फ़ॉन्ट पहले उपयोग किया जाएगा। यदि वह भी प्रतिबंधित है, तो सूची से अगला फ़ॉन्ट चुना जाएगा। यदि फ़ॉन्ट के पास कोई प्रतिस्थापन नहीं है या सभी प्रतिस्थापन अनुमत नहीं हैं तो अनुमत फ़ॉन्ट सूची से पहला अनुमत फ़ॉन्ट उपयोग किया जाएगा। यदि कोई अनुमत और उपलब्ध फ़ॉन्ट नहीं है तो लाइब्रेरी सिस्टम डिफ़ॉल्ट फ़ॉन्ट का उपयोग करने का प्रयास करेगी, भले ही वह अनुमत न हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fontToReplace | java.lang.String | प्रतिस्थापित करने के लिए फ़ॉन्ट। |
| fontNames | java.lang.String[] | समानता के क्रम में प्रतिस्थापन फ़ॉन्ट नाम। |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


फ़ॉन्ट फ़ोल्डर सूची को ओवरराइड करता है  फ़ोल्डर के लिए

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| folder | java.lang.String | TrueType फ़ॉन्ट्स वाला फ़ोल्डर। |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


फ़ॉन्ट फ़ोल्डर सूची को ओवरराइड करता है  फ़ोल्डरों के लिए

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| folders | java.lang.String[] | फ़ोल्डर की सरणी |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


फ़ोल्डर सेट करता है जहाँ से TrueType फ़ॉन्ट लोड होते हैं और सभी लोड किए गए फ़ॉन्ट साफ़ करता है। फ़ॉन्ट फ़ोल्डरों पर कोई जांच नहीं की जाती।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| folders | java.lang.String[] | फ़ॉन्ट फ़ोल्डर। |
| recursive | boolean | यदि true पर सेट किया गया हो [recursive]। |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि [get alternative font]।

मान:  true  यदि [get alternative font]; अन्यथा,  false ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


PSD फ़ाइलों में टेक्स्ट लेयर्स वाले फ़ॉन्ट कैश को अपडेट करता है। यह मेथड यह गारंटी देता है कि फ़ॉन्ट फ़ोल्डर fontsFolder से फ़ॉन्ट, FontSettings.setFontsFolder(fontsFolder) मेथड का उपयोग करके या FontSettings.reset() द्वारा फ़ॉन्ट रीसेट करने के बाद, PSD फ़ाइलों को प्रोसेस करते समय ध्यान में रखे जाएंगे। कृपया इस मेथड का उपयोग हर बार करें जब FontSettings.setFontsFolder(fontsFolder) या FontSettings.reset() को PSD इमेज के लिए कॉल किया जाए। इस मेथड को कॉल किए बिना फ़ॉन्ट अपडेट होने की कोई गारंटी नहीं है।

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

