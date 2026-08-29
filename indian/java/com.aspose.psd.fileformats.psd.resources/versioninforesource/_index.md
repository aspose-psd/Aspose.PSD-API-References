---
title: "VersionInfoResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "संस्करण जानकारी संसाधन"
type: docs
weight: 41
url: /hi/java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

संस्करण जानकारी संसाधन
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | नए [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) वर्ग का एक नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady की रिसोर्स सिग्नेचर। |
| [ResouceBlockSignature](#ResouceBlockSignature) | सामान्य Photoshop रिसोर्स सिग्नेचर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | रिसोर्स डेटा आकार को बाइट्स में प्राप्त करता है। |
| [getFileVersion()](#getFileVersion--) | फ़ाइल संस्करण को प्राप्त करता है या सेट करता है। |
| [getID()](#getID--) | रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है। |
| [getMinimalVersion()](#getMinimalVersion--) | आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है। |
| [getName()](#getName--) | रिसोर्स नाम को प्राप्त करता है या सेट करता है। |
| [getReaderName()](#getReaderName--) | रीडर का नाम प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | रिसोर्स सिग्नेचर को प्राप्त करता है। |
| [getSize()](#getSize--) | डेटा सहित रिसोर्स ब्लॉक आकार को बाइट्स में प्राप्त करता है। |
| [getVersion()](#getVersion--) | संस्करण को प्राप्त करता है या सेट करता है। |
| [getWriterName()](#getWriterName--) | राइटर का नाम प्राप्त करता है या सेट करता है। |
| [hasRealMergedData()](#hasRealMergedData--) | इस उदाहरण में वास्तविक मर्ज्ड डेटा है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | निर्दिष्ट स्ट्रीम में रिसोर्स ब्लॉक को सहेजता है। |
| [setFileVersion(long value)](#setFileVersion-long-) | फ़ाइल संस्करण को प्राप्त करता है या सेट करता है। |
| [setID(short value)](#setID-short-) | रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है। |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | लेयर और मास्क जानकारी को प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | रिसोर्स नाम को प्राप्त करता है या सेट करता है। |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | रीडर का नाम प्राप्त करता है या सेट करता है। |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | इस उदाहरण में वास्तविक मर्ज्ड डेटा है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | रिसोर्स ब्लॉक स्थिति को प्राप्त करता है या सेट करता है। |
| [setVersion(long value)](#setVersion-long-) | संस्करण को प्राप्त करता है या सेट करता है। |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | राइटर का नाम प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | रिसोर्स मानों को वैध करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


नए [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) वर्ग का एक नया उदाहरण प्रारंभ करता है।

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady की रिसोर्स सिग्नेचर।

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


सामान्य Photoshop रिसोर्स सिग्नेचर।

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


रिसोर्स डेटा आकार को बाइट्स में प्राप्त करता है।

मान: संसाधन डेटा आकार।

**Returns:**
int
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


फ़ाइल संस्करण को प्राप्त करता है या सेट करता है।

मान: फ़ाइल संस्करण।

**Returns:**
long
### getID() {#getID--}
```
public final short getID()
```


रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है।

मान: संसाधन के लिए अद्वितीय पहचानकर्ता।

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है।

मान: न्यूनतम PSD संस्करण।

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


संसाधन नाम प्राप्त करता है या सेट करता है। Pascal स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट 0 का होता है)।

मान: संसाधन नाम।

**Returns:**
java.lang.String
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


रीडर का नाम प्राप्त करता है या सेट करता है।

मान: रीडर का नाम।

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


संसाधन हस्ताक्षर प्राप्त करता है। हमेशा '8BIM' होना चाहिए।

मान: संसाधन हस्ताक्षर।

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


डेटा सहित रिसोर्स ब्लॉक आकार को बाइट्स में प्राप्त करता है।

मान: संसाधन ब्लॉक आकार।

**Returns:**
int
### getVersion() {#getVersion--}
```
public final long getVersion()
```


संस्करण को प्राप्त करता है या सेट करता है।

मान: संस्करण।

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


राइटर का नाम प्राप्त करता है या सेट करता है।

Value: लेखक का नाम।

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


इस उदाहरण में वास्तविक मर्ज्ड डेटा है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

Value:  true  यदि इस इंस्टेंस में वास्तविक मर्ज्ड डेटा है; अन्यथा,  false .

**Returns:**
boolean
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


निर्दिष्ट स्ट्रीम में रिसोर्स ब्लॉक को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | संसाधन ब्लॉक को सहेजने के लिए स्ट्रीम। |

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


फ़ाइल संस्करण को प्राप्त करता है या सेट करता है।

मान: फ़ाइल संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है।

मान: संसाधन के लिए अद्वितीय पहचानकर्ता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


लेयर और मास्क जानकारी को प्राप्त करता है या सेट करता है।

मान: लेयर और मास्क जानकारी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


संसाधन नाम प्राप्त करता है या सेट करता है। Pascal स्ट्रिंग, आकार को सम बनाने के लिए पैड किया गया (एक शून्य नाम दो बाइट 0 का होता है)।

मान: संसाधन नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


रीडर का नाम प्राप्त करता है या सेट करता है।

मान: रीडर का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


इस उदाहरण में वास्तविक मर्ज्ड डेटा है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

Value:  true  यदि इस इंस्टेंस में वास्तविक मर्ज्ड डेटा है; अन्यथा,  false .

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| हस्ताक्षर | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


रिसोर्स ब्लॉक स्थिति को प्राप्त करता है या सेट करता है।

मान: संसाधन ब्लॉक स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


संस्करण को प्राप्त करता है या सेट करता है।

मान: संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


राइटर का नाम प्राप्त करता है या सेट करता है।

Value: लेखक का नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


रिसोर्स मानों को वैध करता है।

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

