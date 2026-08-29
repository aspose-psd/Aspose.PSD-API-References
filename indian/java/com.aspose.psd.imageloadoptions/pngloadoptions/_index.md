---
title: "PngLoadOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "png लोड विकल्प।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.imageloadoptions/pngloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

png लोड विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | PngLoadOptions वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | कस्टम फ़ॉन्ट स्रोत। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है। |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | छवि पृष्ठभूमि रंग को प्राप्त करता है। |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | डेटा पुनर्प्राप्ति मोड को प्राप्त करता है। |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि [ignore after load] है या नहीं। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर प्राप्त करता है। |
| [getStrictMode()](#getStrictMode--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [strict mode] है। |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | यह दर्शाने वाला मान प्राप्त करता है कि क्या ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए। |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | यह वेंचर लाइसेंसिंग पैटर्न का हिस्सा है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | इमेज बैकग्राउंड रंग सेट करता है। |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | डेटा रिकवरी मोड सेट करता है। |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | सेट करता है कि क्या [ignore after load]। |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | मेमोरी MGR प्राप्त करता है या सेट करता है। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर सेट करता है। |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [strict mode] है। |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | यह दर्शाने वाला मान सेट करता है कि क्या ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए। |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | यह वेंचर लाइसेंसिंग पैटर्न का हिस्सा है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


PngLoadOptions वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


कस्टम फ़ॉन्ट स्रोत।

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


बफ़र आकार संकेत प्राप्त करता है जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Returns:**
int - बफ़र आकार संकेत जो सभी आंतरिक बफ़र्स के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


छवि पृष्ठभूमि रंग को प्राप्त करता है।

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

आमतौर पर बैकग्राउंड रंग तब सेट किया जाता है जब डेटा भ्रष्टाचार के कारण पिक्सेल मान पुनः प्राप्त नहीं किया जा सकता।
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


डेटा पुनर्प्राप्ति मोड को प्राप्त करता है।

**Returns:**
int - डेटा रिकवरी मोड।
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


एक मान प्राप्त करता है जो दर्शाता है कि [ignore after load] है या नहीं।

**Returns:**
boolean - यदि [ignore after load] है तो true; अन्यथा false।
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


प्रोग्रेस इवेंट हैंडलर प्राप्त करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [strict mode] है।

**Returns:**
boolean - एक मान जो दर्शाता है कि क्या [strict mode] है।
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


यह दर्शाने वाला मान प्राप्त करता है कि क्या ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए।

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


यह वेंचर लाइसेंसिंग पैटर्न का हिस्सा है। यदि वेंचर हमें एक LoadOptions ऑब्जेक्ट पास करता है तो यह मान VentureLicenser द्वारा सेट किया जाएगा।

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


बफ़र आकार संकेत सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है।

मान: बफ़र आकार संकेत, मेगाबाइट में। गैर-धनात्मक मान का अर्थ है आंतरिक बफ़र्स के लिए कोई मेमोरी सीमा नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | बफ़र आकार संकेत जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


इमेज बैकग्राउंड रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | बैकग्राउंड रंग। |

आमतौर पर बैकग्राउंड रंग तब सेट किया जाता है जब डेटा भ्रष्टाचार के कारण पिक्सेल मान पुनः प्राप्त नहीं किया जा सकता। |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


डेटा रिकवरी मोड सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | डेटा रिकवरी मोड। |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


सेट करता है कि क्या [ignore after load]।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | सही यदि [ignore after load]; अन्यथा, गलत। |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


मेमोरी MGR प्राप्त करता है या सेट करता है।

मान: मेमोरी MGR।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


प्रोग्रेस इवेंट हैंडलर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | प्रोग्रेस इवेंट हैंडलर। |

### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या [strict mode] है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो दर्शाता है कि क्या [strict mode] है। |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


यह दर्शाने वाला मान सेट करता है कि क्या ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


यह वेंचर लाइसेंसिंग पैटर्न का हिस्सा है। यदि वेंचर हमें एक LoadOptions ऑब्जेक्ट पास करता है तो यह मान VentureLicenser द्वारा सेट किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

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

