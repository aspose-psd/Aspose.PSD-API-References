---
title: "BlwhResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "BlwhResource क्लास ब्लैक एंड व्हाइट एडजस्टमेंट लेयर का एक रिसोर्स है।"
type: docs
weight: 15
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

BlwhResource क्लास ब्लैक एंड व्हाइट एडजस्टमेंट लेयर का एक रिसोर्स है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | नए [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) क्लास की एक नई इंस्टेंस को इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB हेडर संस्करण। |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-विशिष्ट रिसोर्स सिग्नेचर। |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD हेडर संस्करण। |
| [ResourceSignature](#ResourceSignature) | सामान्य रिसोर्स सिग्नेचर। |
| [TypeToolKey](#TypeToolKey) | टाइप टूल जानकारी कुंजी। |
| [ventureLicense_internalized](#ventureLicense-internalized) | वेंचर लाइसेंस। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | जांचता है और सेट करता है यदि रिसोर्स PSB-विशिष्ट है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | काली और सफ़ेद प्रीसेट फ़ाइल नाम को प्राप्त करता है या सेट करता है। |
| [getBlues()](#getBlues--) | नीले मान को प्राप्त करता है या सेट करता है। |
| [getBwPresetKind()](#getBwPresetKind--) | काली और सफ़ेद प्रीसेट प्रकार मान को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | सियान मान को प्राप्त करता है या सेट करता है। |
| [getData()](#getData--) | डेटा को प्राप्त करता है या सेट करता है। |
| [getGreens()](#getGreens--) | हरा मान को प्राप्त करता है या सेट करता है। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getMagentas()](#getMagentas--) | मैजेंटा मान को प्राप्त करता है या सेट करता है। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getReds()](#getReds--) | लाल मान को प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [getTintColor()](#getTintColor--) | ARGB टिंट रंग को प्राप्त करता है। |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | नीला टिंट रंग डबल मान को प्राप्त करता है या सेट करता है। |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | हरा टिंट रंग डबल मान को प्राप्त करता है या सेट करता है। |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | लाल टिंट रंग डबल मान को प्राप्त करता है या सेट करता है। |
| [getUseTint()](#getUseTint--) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] उपयोग किया गया है या नहीं। |
| [getYellows()](#getYellows--) | पीले मान को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | काली और सफ़ेद प्रीसेट फ़ाइल नाम को प्राप्त करता है या सेट करता है। |
| [setBlues(int value)](#setBlues-int-) | नीले मान को प्राप्त करता है या सेट करता है। |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | काली और सफ़ेद प्रीसेट प्रकार मान को प्राप्त करता है या सेट करता है। |
| [setCyans(int value)](#setCyans-int-) | सियान मान को प्राप्त करता है या सेट करता है। |
| [setGreens(int value)](#setGreens-int-) | हरा मान को प्राप्त करता है या सेट करता है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setMagentas(int value)](#setMagentas-int-) | मैजेंटा मान को प्राप्त करता है या सेट करता है। |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | प्रकार संरचना द्वारा प्रॉपर्टी मान सेट करता है। |
| [setReds(int value)](#setReds-int-) | लाल मान को प्राप्त करता है या सेट करता है। |
| [setTintColor(int value)](#setTintColor-int-) | टिंट रंग को सेट करता है। |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | नीला टिंट रंग डबल मान को प्राप्त करता है या सेट करता है। |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | हरा टिंट रंग डबल मान को प्राप्त करता है या सेट करता है। |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | लाल टिंट रंग डबल मान को प्राप्त करता है या सेट करता है। |
| [setUseTint(boolean value)](#setUseTint-boolean-) | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] उपयोग किया गया है या नहीं। |
| [setYellows(int value)](#setYellows-int-) | पीले मान को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


नए [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) क्लास की एक नई इंस्टेंस को इनिशियलाइज़ करता है।

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB हेडर संस्करण।

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB-विशिष्ट रिसोर्स सिग्नेचर।

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD हेडर संस्करण।

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


सामान्य रिसोर्स सिग्नेचर।

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


टाइप टूल जानकारी कुंजी।

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


वेंचर लाइसेंस।

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


जाँचता है और सेट करता है कि रिसोर्स PSB‑विशिष्ट है या नहीं। कुछ रिसोर्स अभी पहचाने नहीं गए हैं, लेकिन हमारे पास PSB‑विशिष्ट रिसोर्स की पूरी सूची है जो सहेजने पर उनके व्यवहार को बदलती है। इसलिए हमें कम से कम UnknownResource में इसे जाँचने की आवश्यकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | int | कुंजी। |

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


काली और सफ़ेद प्रीसेट फ़ाइल नाम को प्राप्त करता है या सेट करता है।

मान: काली और सफ़ेद प्रीसेट फ़ाइल नाम।

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


नीले मान को प्राप्त करता है या सेट करता है।

मान: नीले मान।

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


काली और सफ़ेद प्रीसेट प्रकार मान को प्राप्त करता है या सेट करता है।

मान: काली और सफ़ेद प्रीसेट प्रकार मान।

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


सियान मान को प्राप्त करता है या सेट करता है।

मान: सियान मान।

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


डेटा को प्राप्त करता है या सेट करता है।

मान: डेटा।

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


हरा मान को प्राप्त करता है या सेट करता है।

मान: हरा मान।

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


लेयर रिसोर्स कुंजी प्राप्त करता है।

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है।

**Returns:**
int
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


मैजेंटा मान को प्राप्त करता है या सेट करता है।

मान: मैजेंटा मान।

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


प्रिफिक्स लंबाई प्राप्त करता है। डिफ़ॉल्ट मान 8BIM रिसोर्स के लिए 12 है और 8B64 के लिए 16 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| psdVersion | int | PSD संस्करण। |

**Returns:**
int - प्रिफिक्स लंबाई।
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है।

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


लाल मान को प्राप्त करता है या सेट करता है।

मान: लाल मान।

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


लेयर रिसोर्स सिग्नेचर प्राप्त करता है।

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


ARGB टिंट रंग को प्राप्त करता है।

**Returns:**
int - ARGB टिंट रंग।
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


नीला टिंट रंग डबल मान को प्राप्त करता है या सेट करता है।

मान: नीला टिंट रंग डबल मान।

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


हरा टिंट रंग डबल मान को प्राप्त करता है या सेट करता है।

मान: ग्रीन टिंट कलर डबल वैल्यू।

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


लाल टिंट रंग डबल मान को प्राप्त करता है या सेट करता है।

मान: रेड टिंट कलर डबल वैल्यू।

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] उपयोग किया गया है या नहीं।

मान:  true  यदि उपयोग किया गया है [tint color]; अन्यथा,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


पीले मान को प्राप्त करता है या सेट करता है।

मान: येलोज़ वैल्यू।

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | int | रिसोर्स कुंजी। |

**Returns:**
boolean - यदि रिसोर्स PSB‑विशिष्ट है तो true, अन्यथा false।
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं।

मान: यदि यह इंस्टेंस रिसोर्स PSB‑विशिष्ट है तो true, अन्यथा false।

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | सहेजने के लिए स्ट्रीम कंटेनर। |
| psdVersion | int | PSD संस्करण। |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


कस्टम रिसोर्स हेडर को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| हस्ताक्षर | int | हस्ताक्षर। |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| हस्ताक्षर | int | हस्ताक्षर। |
| isLengthLong | boolean | यदि true सेट किया गया है तो लंबाई लंबी होती है। |

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


काली और सफ़ेद प्रीसेट फ़ाइल नाम को प्राप्त करता है या सेट करता है।

मान: काली और सफ़ेद प्रीसेट फ़ाइल नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


नीले मान को प्राप्त करता है या सेट करता है।

मान: नीले मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


काली और सफ़ेद प्रीसेट प्रकार मान को प्राप्त करता है या सेट करता है।

मान: काली और सफ़ेद प्रीसेट प्रकार मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


सियान मान को प्राप्त करता है या सेट करता है।

मान: सियान मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


हरा मान को प्राप्त करता है या सेट करता है।

मान: हरा मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


मैजेंटा मान को प्राप्त करता है या सेट करता है।

मान: मैजेंटा मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


प्रकार संरचना द्वारा प्रॉपर्टी मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | संरचना। |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


लाल मान को प्राप्त करता है या सेट करता है।

मान: लाल मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


टिंट रंग को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | मान। |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


नीला टिंट रंग डबल मान को प्राप्त करता है या सेट करता है।

मान: नीला टिंट रंग डबल मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


हरा टिंट रंग डबल मान को प्राप्त करता है या सेट करता है।

मान: ग्रीन टिंट कलर डबल वैल्यू।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


लाल टिंट रंग डबल मान को प्राप्त करता है या सेट करता है।

मान: रेड टिंट कलर डबल वैल्यू।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [tint color] उपयोग किया गया है या नहीं।

मान:  true  यदि उपयोग किया गया है [tint color]; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


पीले मान को प्राप्त करता है या सेट करता है।

मान: येलोज़ वैल्यू।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग।
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

