---
title: "PsdLoadOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "PSD लोड विकल्प"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

PSD लोड विकल्प
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | नए उदाहरण को प्रारंभ करता है [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | कस्टम फ़ॉन्ट स्रोत। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | प्राप्त करता या सेट करता है कि क्या रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित किया जाए यदि लेयर में कोई परिवर्तन नहीं हुआ है। |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | प्राप्त करता या सेट करता है कि क्या रेंडर की गई छवि के साथ सहेजा जाए, वॉर्प ट्रांसफ़ॉर्म के साथ या बिना। |
| [getBufferSizeHint()](#getBufferSizeHint--) | बफ़र आकार संकेत प्राप्त करता है जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार के रूप में परिभाषित है। |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | छवि पृष्ठभूमि रंग को प्राप्त करता है। |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | डेटा पुनर्प्राप्ति मोड को प्राप्त करता है। |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि [ignore after load] है या नहीं। |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [ignore alpha channel]। |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या PSD टेक्स्ट लेयर की निश्चित चौड़ाई को UpdateText ऑपरेशन निष्पादन पर अनदेखा किया जाएगा। |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [load effects resource] (डिफ़ॉल्ट रूप से संसाधन लोड नहीं किया गया है)। |
| [getProgressEventHandler()](#getProgressEventHandler--) | प्रोग्रेस इवेंट हैंडलर प्राप्त करता है। |
| [getReadOnlyMode()](#getReadOnlyMode--) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use read only mode]। |
| [getReadOnlyType()](#getReadOnlyType--) | प्राप्त करता या सेट करता है वह रीड-ओनली मोड जो PSD छवि लोड करने पर उपयोग किया जाता है। |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use disk for load effects resource] (डिफ़ॉल्ट रूप से प्रभाव संसाधन लोड करने के लिए डिस्क का उपयोग किया जाता है, लेकिन यदि यह पर्याप्त हो तो इस मान को false सेट करके मेमोरी का उपयोग किया जा सकता है)। |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | यह दर्शाने वाला मान प्राप्त करता है कि क्या ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए। |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | यह वेंचर लाइसेंसिंग पैटर्न का हिस्सा है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | प्राप्त करता या सेट करता है कि क्या रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित किया जाए यदि लेयर में कोई परिवर्तन नहीं हुआ है। |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | प्राप्त करता या सेट करता है कि क्या रेंडर की गई छवि के साथ सहेजा जाए, वॉर्प ट्रांसफ़ॉर्म के साथ या बिना। |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | बफ़र आकार संकेत सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार को परिभाषित करता है। |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | इमेज बैकग्राउंड रंग सेट करता है। |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | डेटा रिकवरी मोड सेट करता है। |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | सेट करता है कि क्या [ignore after load]। |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [ignore alpha channel]। |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या PSD टेक्स्ट लेयर की निश्चित चौड़ाई को UpdateText ऑपरेशन निष्पादन पर अनदेखा किया जाएगा। |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [load effects resource] (डिफ़ॉल्ट रूप से संसाधन लोड नहीं किया गया है)। |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | मेमोरी MGR प्राप्त करता है या सेट करता है। |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर सेट करता है। |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use read only mode]। |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | प्राप्त करता या सेट करता है वह रीड-ओनली मोड जो PSD छवि लोड करने पर उपयोग किया जाता है। |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use disk for load effects resource] (डिफ़ॉल्ट रूप से प्रभाव संसाधन लोड करने के लिए डिस्क का उपयोग किया जाता है, लेकिन यदि यह पर्याप्त हो तो इस मान को false सेट करके मेमोरी का उपयोग किया जा सकता है)। |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | यह दर्शाने वाला मान सेट करता है कि क्या ICC प्रोफ़ाइल रूपांतरण लागू किया जाना चाहिए। |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | यह वेंचर लाइसेंसिंग पैटर्न का हिस्सा है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


नए उदाहरण को प्रारंभ करता है [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) क्लास का।

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


प्राप्त करता या सेट करता है कि क्या रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित किया जाए यदि लेयर में कोई परिवर्तन नहीं हुआ है।

मान: सही ताकि अपरिवर्तित लेयर्स के मूल पिक्सेल रखे जाएँ; अन्यथा, गलत।

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


प्राप्त करता या सेट करता है कि क्या रेंडर की गई छवि के साथ सहेजा जाए, वॉर्प ट्रांसफ़ॉर्म के साथ या बिना।

मान: सही रेंडर छवि वॉर्प ट्रांसफ़ॉर्मेशन के साथ; अन्यथा, गलत।

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
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [ignore alpha channel]।

मान: सही यदि [ignore alpha channel]; अन्यथा, गलत।

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या PSD टेक्स्ट लेयर की निश्चित चौड़ाई को UpdateText ऑपरेशन निष्पादन पर अनदेखा किया जाएगा।

मान: सही यदि [ignore text layer width]; अन्यथा, गलत।

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [load effects resource] (डिफ़ॉल्ट रूप से संसाधन लोड नहीं किया गया है)। जब यह विकल्प सेट किया जाता है, तो केवल समर्थित प्रभावों को अंतिम मर्ज्ड छवि में रेंडर किया जाएगा।

मान: सही यदि [load effects resource]; अन्यथा, गलत।

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


प्रोग्रेस इवेंट हैंडलर प्राप्त करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use read only mode]। यह रीड-ओनली मोड है, जो Adobe Photoshop के साथ समान संगतता के लिए समर्थित है। जब यह विकल्प सेट किया जाता है, तो लेयर्स पर लागू सभी परिवर्तन अंतिम छवि में सहेजे नहीं जाएंगे। सभी डेटा ImageData सेक्शन से उपयोग किया जाता है, इसलिए यह Photoshop के समान है। डिफ़ॉल्ट रूप से सभी लोड की गई छवियां Adobe Photoshop संगत नहीं होती हैं।

मान: सही यदि [use photoshop compatibility mode]; अन्यथा, गलत।

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


प्राप्त करता या सेट करता है वह रीड-ओनली मोड जो PSD छवि लोड करने पर उपयोग किया जाता है।

मान: ReadOnlyMode में से एक ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) मान:

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use disk for load effects resource] (डिफ़ॉल्ट रूप से प्रभाव संसाधन लोड करने के लिए डिस्क का उपयोग किया जाता है, लेकिन यदि यह पर्याप्त हो तो इस मान को false सेट करके मेमोरी का उपयोग किया जा सकता है)।

मान: सही यदि [use disk for load effects resource]; अन्यथा, गलत।

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


प्राप्त करता या सेट करता है कि क्या रेंडरिंग के दौरान मूल लेयर पिक्सेल को संरक्षित किया जाए यदि लेयर में कोई परिवर्तन नहीं हुआ है।

मान: सही ताकि अपरिवर्तित लेयर्स के मूल पिक्सेल रखे जाएँ; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


प्राप्त करता या सेट करता है कि क्या रेंडर की गई छवि के साथ सहेजा जाए, वॉर्प ट्रांसफ़ॉर्म के साथ या बिना।

मान: सही रेंडर छवि वॉर्प ट्रांसफ़ॉर्मेशन के साथ; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [ignore alpha channel]।

मान: सही यदि [ignore alpha channel]; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या PSD टेक्स्ट लेयर की निश्चित चौड़ाई को UpdateText ऑपरेशन निष्पादन पर अनदेखा किया जाएगा।

मान: सही यदि [ignore text layer width]; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [load effects resource] (डिफ़ॉल्ट रूप से संसाधन लोड नहीं किया गया है)। जब यह विकल्प सेट किया जाता है, तो केवल समर्थित प्रभावों को अंतिम मर्ज्ड छवि में रेंडर किया जाएगा।

मान: सही यदि [load effects resource]; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use read only mode]। यह रीड-ओनली मोड है, जो Adobe Photoshop के साथ समान संगतता के लिए समर्थित है। जब यह विकल्प सेट किया जाता है, तो लेयर्स पर लागू सभी परिवर्तन अंतिम छवि में सहेजे नहीं जाएंगे। सभी डेटा ImageData सेक्शन से उपयोग किया जाता है, इसलिए यह Photoshop के समान है। डिफ़ॉल्ट रूप से सभी लोड की गई छवियां Adobe Photoshop संगत नहीं होती हैं।

मान: सही यदि [use photoshop compatibility mode]; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


प्राप्त करता या सेट करता है वह रीड-ओनली मोड जो PSD छवि लोड करने पर उपयोग किया जाता है।

मान: ReadOnlyMode में से एक ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) मान:

 *  
 *  
 *  

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


प्राप्त करता या सेट करता है वह मान जो दर्शाता है कि क्या [use disk for load effects resource] (डिफ़ॉल्ट रूप से प्रभाव संसाधन लोड करने के लिए डिस्क का उपयोग किया जाता है, लेकिन यदि यह पर्याप्त हो तो इस मान को false सेट करके मेमोरी का उपयोग किया जा सकता है)।

मान: सही यदि [use disk for load effects resource]; अन्यथा, गलत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

