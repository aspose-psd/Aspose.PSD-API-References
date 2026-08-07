---
title: "Hue2Resource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "क्लास Hue2Resource."
type: docs
weight: 36
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class Hue2Resource extends AdjustmentLayerResource
```

क्लास Hue2Resource. एक्सपोज़र एडजस्टमेंट लेयर का रिसोर्स।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Hue2Resource()](#Hue2Resource--) | नए [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है। |
| [Hue2Resource(byte[] data)](#Hue2Resource-byte---) | नए [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है। |
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
| [getClass()](#getClass--) |  |
| [getColorize()](#getColorize--) | इस [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) को कलराइज़ है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getData()](#getData--) | डेटा को प्राप्त करता है या सेट करता है। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getHue()](#getHue--) | मास्टर ह्यू प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getLightness()](#getLightness--) | मास्टर लाइटनेस प्राप्त करता है या सेट करता है। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getRanges()](#getRanges--) | Hue/Saturation एडजस्टमेंट लेयर की रेंज प्राप्त करता है। |
| [getSaturation()](#getSaturation--) | मास्टर सैचुरेशन प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [getVersion()](#getVersion--) | संस्करण प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setColorize(boolean value)](#setColorize-boolean-) | इस [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) को कलराइज़ है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setHue(short value)](#setHue-short-) | मास्टर ह्यू प्राप्त करता है या सेट करता है। |
| [setLightness(short value)](#setLightness-short-) | मास्टर लाइटनेस प्राप्त करता है या सेट करता है। |
| [setRanges(ColorRangeHsl[] value)](#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---) | Hue/Saturation एडजस्टमेंट लेयर की रेंज प्राप्त करता है। |
| [setSaturation(short value)](#setSaturation-short-) | मास्टर सैचुरेशन प्राप्त करता है या सेट करता है। |
| [setVersion(short value)](#setVersion-short-) | संस्करण प्राप्त करता है। |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Hue2Resource() {#Hue2Resource--}
```
public Hue2Resource()
```


नए [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।

### Hue2Resource(byte[] data) {#Hue2Resource-byte---}
```
public Hue2Resource(byte[] data)
```


नए [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा | byte[] | संसाधन का डेटा। |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorize() {#getColorize--}
```
public final boolean getColorize()
```


इस [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) को कलराइज़ है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि colorize; अन्यथा,  false .

**Returns:**
boolean
### getData() {#getData--}
```
public final byte[] getData()
```


डेटा को प्राप्त करता है या सेट करता है।

मान: डेटा।

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHue() {#getHue--}
```
public final short getHue()
```


मास्टर ह्यू प्राप्त करता है या सेट करता है।

मान: मास्टर ह्यू।

**Returns:**
short
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
### getLightness() {#getLightness--}
```
public final short getLightness()
```


मास्टर लाइटनेस प्राप्त करता है या सेट करता है।

मान: मास्टर लाइटनेस।

**Returns:**
short
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
### getRanges() {#getRanges--}
```
public final ColorRangeHsl[] getRanges()
```


Hue/Saturation एडजस्टमेंट लेयर की रेंज प्राप्त करता है। PS में रेंज के नाम बदल सकते हैं यदि रेंज बदला जाता है, इसलिए हमें इंडेक्स द्वारा काम करना चाहिए।

मान: रेंजेज।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl[]
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


मास्टर सैचुरेशन प्राप्त करता है या सेट करता है।

मान: मास्टर सैचुरेशन।

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


लेयर रिसोर्स सिग्नेचर प्राप्त करता है।

**Returns:**
int
### getVersion() {#getVersion--}
```
public final short getVersion()
```


संस्करण प्राप्त करता है। डिफ़ॉल्ट 2 है।

मान: संस्करण।

**Returns:**
short
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

### setColorize(boolean value) {#setColorize-boolean-}
```
public final void setColorize(boolean value)
```


इस [Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) को कलराइज़ है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

मान:  true  यदि colorize; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


मास्टर ह्यू प्राप्त करता है या सेट करता है।

मान: मास्टर ह्यू।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


मास्टर लाइटनेस प्राप्त करता है या सेट करता है।

मान: मास्टर लाइटनेस।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setRanges(ColorRangeHsl[] value) {#setRanges-com.aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl---}
```
public void setRanges(ColorRangeHsl[] value)
```


Hue/Saturation एडजस्टमेंट लेयर की रेंज प्राप्त करता है। PS में रेंज के नाम बदल सकते हैं यदि रेंज बदला जाता है, इसलिए हमें इंडेक्स द्वारा काम करना चाहिए।

मान: रेंजेज।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ColorRangeHsl\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


मास्टर सैचुरेशन प्राप्त करता है या सेट करता है।

मान: मास्टर सैचुरेशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setVersion(short value) {#setVersion-short-}
```
public void setVersion(short value)
```


संस्करण प्राप्त करता है। डिफ़ॉल्ट 2 है।

मान: संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

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

