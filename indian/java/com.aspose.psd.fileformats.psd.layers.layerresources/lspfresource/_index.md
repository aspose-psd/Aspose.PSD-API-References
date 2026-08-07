---
title: "LspfResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लेयर प्रोटेक्टेड सेटिंग्स"
type: docs
weight: 57
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class LspfResource extends LayerResource
```

लेयर प्रोटेक्टेड सेटिंग्स
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LspfResource(byte[] data)](#LspfResource-byte---) | नए उदाहरण को प्रारंभ करता है [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) क्लास का। |
| [LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)](#LspfResource-boolean-boolean-boolean-) | नए उदाहरण को प्रारंभ करता है [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) क्लास का। |
| [LspfResource()](#LspfResource--) | नए उदाहरण को प्रारंभ करता है [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB हेडर संस्करण। |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-विशिष्ट रिसोर्स सिग्नेचर। |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD हेडर संस्करण। |
| [ResourceSignature](#ResourceSignature) | सामान्य रिसोर्स सिग्नेचर। |
| [TypeToolKey](#TypeToolKey) | प्रकार टूल जानकारी कुंजी 1819504742 |
| [ventureLicense_internalized](#ventureLicense-internalized) | वेंचर लाइसेंस। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | जांचता है और सेट करता है यदि रिसोर्स PSB-विशिष्ट है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getLockType()](#getLockType--) | लॉक के प्रकार को प्राप्त करता है या सेट करता है। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isCompositeProtected()](#isCompositeProtected--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण संयोगित रूप से संरक्षित है। |
| [isPositionProtected()](#isPositionProtected--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण स्थिति रूप से संरक्षित है। |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isTransparencyProtected()](#isTransparencyProtected--) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण पारदर्शिता रूप से संरक्षित है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setCompositeProtected(boolean value)](#setCompositeProtected-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण संयोगित रूप से संरक्षित है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setLockType(int value)](#setLockType-int-) | लॉक के प्रकार को प्राप्त करता है या सेट करता है। |
| [setPositionProtected(boolean value)](#setPositionProtected-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण स्थिति रूप से संरक्षित है। |
| [setTransparencyProtected(boolean value)](#setTransparencyProtected-boolean-) | यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण पारदर्शिता रूप से संरक्षित है। |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LspfResource(byte[] data) {#LspfResource-byte---}
```
public LspfResource(byte[] data)
```


नए उदाहरण को प्रारंभ करता है [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) क्लास का। कस्टम या अज्ञात मान के साथ

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा | byte[] | संसाधन डेटा। |

### LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected) {#LspfResource-boolean-boolean-boolean-}
```
public LspfResource(boolean isTransparencyProtected, boolean isCompositeProtected, boolean isPositionProtected)
```


नए उदाहरण को प्रारंभ करता है [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isTransparencyProtected | boolean | यदि true पर सेट किया गया है [is transparency protected]. |
| isCompositeProtected | boolean | यदि true पर सेट किया गया है [is composite protected]. |
| isPositionProtected | boolean | यदि इसे  true  पर सेट किया गया है तो [is position protected]। |

### LspfResource() {#LspfResource--}
```
public LspfResource()
```


नए उदाहरण को प्रारंभ करता है [LspfResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/lspfresource) क्लास का।

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


प्रकार टूल जानकारी कुंजी 1819504742

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
### getLockType() {#getLockType--}
```
public final int getLockType()
```


लॉक के प्रकार को प्राप्त करता है या सेट करता है।

मान: लॉक का प्रकार।

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
### getSignature() {#getSignature--}
```
public int getSignature()
```


लेयर रिसोर्स सिग्नेचर प्राप्त करता है।

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompositeProtected() {#isCompositeProtected--}
```
public final boolean isCompositeProtected()
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण संयोगित रूप से संरक्षित है।

मान:  true  यदि यह इंस्टेंस कॉम्पोजिट संरक्षित है; अन्यथा,  false .

**Returns:**
boolean
### isPositionProtected() {#isPositionProtected--}
```
public final boolean isPositionProtected()
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण स्थिति रूप से संरक्षित है।

मान:  true  यदि यह इंस्टेंस पोजीशन संरक्षित है; अन्यथा,  false .

**Returns:**
boolean
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
### isTransparencyProtected() {#isTransparencyProtected--}
```
public final boolean isTransparencyProtected()
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण पारदर्शिता रूप से संरक्षित है।

मान:  true  यदि यह इंस्टेंस ट्रांसपैरेंसी संरक्षित है; अन्यथा,  false .

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

### setCompositeProtected(boolean value) {#setCompositeProtected-boolean-}
```
public final void setCompositeProtected(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण संयोगित रूप से संरक्षित है।

मान:  true  यदि यह इंस्टेंस कॉम्पोजिट संरक्षित है; अन्यथा,  false .

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

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


लॉक के प्रकार को प्राप्त करता है या सेट करता है।

मान: लॉक का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setPositionProtected(boolean value) {#setPositionProtected-boolean-}
```
public final void setPositionProtected(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण स्थिति रूप से संरक्षित है।

मान:  true  यदि यह इंस्टेंस पोजीशन संरक्षित है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setTransparencyProtected(boolean value) {#setTransparencyProtected-boolean-}
```
public final void setTransparencyProtected(boolean value)
```


यह दर्शाने वाला मान प्राप्त करता है या सेट करता है कि यह उदाहरण पारदर्शिता रूप से संरक्षित है।

मान:  true  यदि यह इंस्टेंस ट्रांसपैरेंसी संरक्षित है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

