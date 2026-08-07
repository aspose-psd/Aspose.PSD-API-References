---
title: "LayerGroupInformationResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "लेयर समूह जानकारी संसाधन"
type: docs
weight: 25
url: /hi/java/com.aspose.psd.fileformats.psd.resources/layergroupinformationresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class LayerGroupInformationResource extends ResourceBlock
```

लेयर समूह जानकारी संसाधन
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [LayerGroupInformationResource()](#LayerGroupInformationResource--) | नए उदाहरण को प्रारंभ करता है [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource) क्लास का। |
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
| [getGroups()](#getGroups--) | समूहों को प्राप्त करता है या सेट करता है। |
| [getID()](#getID--) | रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है। |
| [getMinimalVersion()](#getMinimalVersion--) | आवश्यक न्यूनतम PSD संस्करण को प्राप्त करता है। |
| [getName()](#getName--) | रिसोर्स नाम को प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | रिसोर्स सिग्नेचर को प्राप्त करता है। |
| [getSize()](#getSize--) | डेटा सहित रिसोर्स ब्लॉक आकार को बाइट्स में प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | निर्दिष्ट स्ट्रीम में रिसोर्स ब्लॉक को सहेजता है। |
| [setGroups(short[] value)](#setGroups-short---) | समूहों को प्राप्त करता है या सेट करता है। |
| [setID(short value)](#setID-short-) | रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है। |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | लेयर और मास्क जानकारी को प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | रिसोर्स नाम को प्राप्त करता है या सेट करता है। |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | रिसोर्स ब्लॉक स्थिति को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [updateLayerGroupIds_internalized()](#updateLayerGroupIds-internalized--) | समूहों प्रॉपर्टी से लेयर्स में LinkGroupId को अपडेट करता है। |
| [updateResourceGroupIds_internalized()](#updateResourceGroupIds-internalized--) | लेयर्स से समूहों प्रॉपर्टी में मानों को अपडेट करता है। |
| [validateValues()](#validateValues--) | रिसोर्स मानों को वैध करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerGroupInformationResource() {#LayerGroupInformationResource--}
```
public LayerGroupInformationResource()
```


नए उदाहरण को प्रारंभ करता है [ResolutionInfoResource](../../com.aspose.psd.fileformats.psd.resources/resolutioninforesource) क्लास का।

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
### getGroups() {#getGroups--}
```
public final short[] getGroups()
```


समूहों को प्राप्त करता है या सेट करता है।

मान: समूह।

**Returns:**
short[]
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

### setGroups(short[] value) {#setGroups-short---}
```
public final void setGroups(short[] value)
```


समूहों को प्राप्त करता है या सेट करता है।

मान: समूह।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short[] |  |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateLayerGroupIds_internalized() {#updateLayerGroupIds-internalized--}
```
public final void updateLayerGroupIds_internalized()
```


समूहों प्रॉपर्टी से लेयर्स में LinkGroupId को अपडेट करता है।

### updateResourceGroupIds_internalized() {#updateResourceGroupIds-internalized--}
```
public final void updateResourceGroupIds_internalized()
```


लेयर्स से समूहों प्रॉपर्टी में मानों को अपडेट करता है।

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

