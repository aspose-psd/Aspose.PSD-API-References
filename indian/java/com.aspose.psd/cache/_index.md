---
title: "कैश"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "कैश सेटिंग्स शामिल है।"
type: docs
weight: 14
url: /hi/java/com.aspose.psd/cache/
---

**Inheritance:**
java.lang.Object
```
public final class Cache
```

कैश सेटिंग्स शामिल है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllocatedDiskBytesCount()](#getAllocatedDiskBytesCount--) | आवंटित डिस्क बाइट्स की गिनती प्राप्त करता है। |
| [getAllocatedMemoryBytesCount()](#getAllocatedMemoryBytesCount--) | आवंटित इन-मेमोरी बाइट्स की गिनती प्राप्त करता है। |
| [getCacheFolder()](#getCacheFolder--) | कैश फ़ोल्डर प्राप्त करता है। |
| [getCacheType()](#getCacheType--) | उपयोग किए गए कैश स्कीम को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getExactReallocateOnly()](#getExactReallocateOnly--) | एक मान प्राप्त करता है जो दर्शाता है कि पुनः आवंटन सटीक होना चाहिए या नहीं। |
| [getMaxDiskSpaceForCache()](#getMaxDiskSpaceForCache--) | कैश के लिए उपलब्ध अधिकतम डिस्क स्पेस प्राप्त करता है। |
| [getMaxMemoryForCache()](#getMaxMemoryForCache--) | कैश के लिए उपलब्ध अधिकतम मेमोरी इन‑मेमोरी प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCacheFolder(String value)](#setCacheFolder-java.lang.String-) | कैश फ़ोल्डर सेट करता है। |
| [setCacheType(int value)](#setCacheType-int-) | उपयोग किए गए कैश स्कीम को सेट करता है। |
| [setDefaults()](#setDefaults--) | कैश सेटिंग्स को डिफ़ॉल्ट पर सेट करता है। |
| [setExactReallocateOnly(boolean value)](#setExactReallocateOnly-boolean-) | एक मान सेट करता है जो दर्शाता है कि पुनः आवंटन सटीक होना चाहिए या नहीं। |
| [setMaxDiskSpaceForCache(int value)](#setMaxDiskSpaceForCache-int-) | कैश के लिए उपलब्ध अधिकतम डिस्क स्पेस सेट करता है। |
| [setMaxMemoryForCache(int value)](#setMaxMemoryForCache-int-) | कैश के लिए उपलब्ध अधिकतम मेमोरी इन‑मेमोरी सेट करता है। |
| [toString()](#toString--) |  |
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
### getAllocatedDiskBytesCount() {#getAllocatedDiskBytesCount--}
```
public static long getAllocatedDiskBytesCount()
```


आवंटित डिस्क बाइट्स की गिनती प्राप्त करता है।

**Returns:**
long - आवंटित डिस्क बाइट्स की गिनती।
### getAllocatedMemoryBytesCount() {#getAllocatedMemoryBytesCount--}
```
public static long getAllocatedMemoryBytesCount()
```


आवंटित इन-मेमोरी बाइट्स की गिनती प्राप्त करता है।

**Returns:**
long - आवंटित इन‑मेमोरी बाइट्स की गिनती।
### getCacheFolder() {#getCacheFolder--}
```
public static String getCacheFolder()
```


कैश फ़ोल्डर प्राप्त करता है।

**Returns:**
java.lang.String - कैश फ़ोल्डर।
### getCacheType() {#getCacheType--}
```
public static int getCacheType()
```


उपयोग किए गए कैश स्कीम को प्राप्त करता है या सेट करता है।

**Returns:**
int - उपयोग किया गया कैश स्कीम।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExactReallocateOnly() {#getExactReallocateOnly--}
```
public static boolean getExactReallocateOnly()
```


एक मान प्राप्त करता है जो दर्शाता है कि पुनः आवंटन सटीक होना चाहिए या नहीं। यदि पुनः आवंटन सटीक नहीं है तो प्रदर्शन अधिक होना चाहिए।

**Returns:**
boolean -  true  यदि पुनः आवंटन सटीक है; अन्यथा,  false .

सटीक पुनः आवंटन केवल निर्दिष्ट ऊपरी सीमा तक अतिरिक्त मेमोरी का पुनः आवंटन करेगा। पुनः आवंटन के दौरान इन‑मेमोरी के लिए ऊपरी सीमा पास करने पर, यदि संभव हो तो कैश्ड डेटा को डिस्क पर कॉपी किया जाएगा। डिस्क मेमोरी के लिए ऊपरी सीमा पास करने पर उपयुक्त अपवाद फेंका जाएगा। यदि यह विकल्प बंद किया जाता है तो प्रदर्शन अधिक होना चाहिए क्योंकि कोई अतिरिक्त कॉपी नहीं की जाएगी, हालांकि इससे मेमोरी या डिस्क के लिए निर्दिष्ट ऊपरी सीमाओं को पार करने का जोखिम भी हो सकता है।
### getMaxDiskSpaceForCache() {#getMaxDiskSpaceForCache--}
```
public static int getMaxDiskSpaceForCache()
```


कैश के लिए उपलब्ध अधिकतम डिस्क स्पेस प्राप्त करता है। निर्दिष्ट मान मेगाबाइट्स की गिनती है।

**Returns:**
int - कैश के लिए उपलब्ध अधिकतम डिस्क स्पेस।

0 का मान सभी उपलब्ध मेमोरी का उपभोग करेगा और कोई ऊपरी सीमा नहीं माना जाएगा।
### getMaxMemoryForCache() {#getMaxMemoryForCache--}
```
public static int getMaxMemoryForCache()
```


कैश के लिए उपलब्ध अधिकतम मेमोरी को मेमोरी में प्राप्त करता है। निर्दिष्ट मान मेगाबाइट की संख्या है।

**Returns:**
int - कैश के लिए अधिकतम मेमोरी।

0 का मान सभी उपलब्ध मेमोरी का उपभोग करेगा और कोई ऊपरी सीमा नहीं माना जाएगा।
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




### setCacheFolder(String value) {#setCacheFolder-java.lang.String-}
```
public static void setCacheFolder(String value)
```


कैश फ़ोल्डर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String | कैश फ़ोल्डर। |

### setCacheType(int value) {#setCacheType-int-}
```
public static void setCacheType(int value)
```


उपयोग किए गए कैश स्कीम को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | उपयोग किया गया कैश योजना। |

### setDefaults() {#setDefaults--}
```
public static void setDefaults()
```


कैश सेटिंग्स को डिफ़ॉल्ट पर सेट करता है।

### setExactReallocateOnly(boolean value) {#setExactReallocateOnly-boolean-}
```
public static void setExactReallocateOnly(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि पुनः आवंटन सटीक होना चाहिए या नहीं। यदि पुनः आवंटन सटीक नहीं है तो प्रदर्शन अधिक होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | सही यदि पुनः आवंटन सटीक है; अन्यथा, गलत। |

सटीक पुनः आवंटन केवल निर्दिष्ट ऊपरी सीमा तक अतिरिक्त मेमोरी का पुनः आवंटन करेगा। पुनः आवंटन के दौरान इन-मेमोरी के लिए ऊपरी सीमा पास करने पर यदि संभव हो तो कैश्ड डेटा डिस्क पर कॉपी किया जाएगा। डिस्क मेमोरी के लिए ऊपरी सीमा पास करने पर उपयुक्त अपवाद फेंका जाएगा। यदि यह विकल्प बंद किया जाता है तो प्रदर्शन अधिक होना चाहिए क्योंकि संभव होने पर कोई अतिरिक्त कॉपी नहीं की जाएगी, हालांकि इससे मेमोरी या डिस्क के लिए निर्दिष्ट ऊपरी सीमाओं को पार करने की संभावना भी हो सकती है। |

### setMaxDiskSpaceForCache(int value) {#setMaxDiskSpaceForCache-int-}
```
public static void setMaxDiskSpaceForCache(int value)
```


कैश के लिए उपलब्ध अधिकतम डिस्क स्पेस सेट करता है। निर्दिष्ट मान मेगाबाइट की संख्या है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | कैश के लिए उपलब्ध अधिकतम डिस्क स्पेस। |

0 का मान सभी उपलब्ध मेमोरी का उपभोग करेगा और कोई ऊपरी सीमा नहीं माना जाएगा। |

### setMaxMemoryForCache(int value) {#setMaxMemoryForCache-int-}
```
public static void setMaxMemoryForCache(int value)
```


मेमोरी में कैश के लिए उपलब्ध अधिकतम मेमोरी सेट करता है। निर्दिष्ट मान मेगाबाइट की संख्या है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | कैश के लिए अधिकतम मेमोरी। |

0 का मान सभी उपलब्ध मेमोरी का उपभोग करेगा और कोई ऊपरी सीमा नहीं माना जाएगा। |

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

