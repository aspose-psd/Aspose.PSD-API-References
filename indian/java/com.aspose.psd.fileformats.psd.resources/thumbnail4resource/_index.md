---
title: "Thumbnail4Resource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "psd 4.0 के लिए थंबनेल संसाधन का प्रतिनिधित्व करता है।"
type: docs
weight: 34
url: /hi/java/com.aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock), [com.aspose.psd.fileformats.psd.resources.ThumbnailResource](../../com.aspose.psd.fileformats.psd.resources/thumbnailresource)
```
public final class Thumbnail4Resource extends ThumbnailResource
```

psd 4.0 के लिए थंबनेल संसाधन का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [Thumbnail4Resource()](#Thumbnail4Resource--) | नए [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) क्लास का एक नया उदाहरण आरंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady की रिसोर्स सिग्नेचर। |
| [ResouceBlockSignature](#ResouceBlockSignature) | सामान्य Photoshop रिसोर्स सिग्नेचर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPixel()](#getBitsPixel--) | बिट्स पिक्सेल को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | रिसोर्स डेटा आकार को बाइट्स में प्राप्त करता है। |
| [getFormat()](#getFormat--) | थंबनेल डेटा फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [getHeight()](#getHeight--) | थंबनेल की ऊँचाई पिक्सेल में प्राप्त करता है या सेट करता है। |
| [getID()](#getID--) | रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है। |
| [getJpegOptions()](#getJpegOptions--) | JPEG विकल्पों को प्राप्त करता है या सेट करता है। |
| [getMinimalVersion()](#getMinimalVersion--) | न्यूनतम आवश्यक PSD संस्करण को प्राप्त करता है। |
| [getName()](#getName--) | रिसोर्स नाम को प्राप्त करता है या सेट करता है। |
| [getPlanesCount()](#getPlanesCount--) | प्लेन की गिनती को प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | रिसोर्स सिग्नेचर को प्राप्त करता है। |
| [getSize()](#getSize--) | डेटा सहित रिसोर्स ब्लॉक आकार को बाइट्स में प्राप्त करता है। |
| [getSizeAfterCompression()](#getSizeAfterCompression--) | संपीड़न के बाद आकार को प्राप्त करता है या सेट करता है। |
| [getThumbnailArgb32Data()](#getThumbnailArgb32Data--) | 32-बिट ARGB थंबनेल डेटा को प्राप्त करता है या सेट करता है। |
| [getThumbnailData()](#getThumbnailData--) | थंबनेल डेटा को प्राप्त करता है या सेट करता है। |
| [getTotalSize()](#getTotalSize--) | कुल डेटा आकार को प्राप्त करता है। |
| [getWidth()](#getWidth--) | थंबनेल की चौड़ाई पिक्सेल में प्राप्त करता है या सेट करता है। |
| [getWidthBytes()](#getWidthBytes--) | पंक्ति की चौड़ाई बाइट्स में प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | निर्दिष्ट स्ट्रीम में रिसोर्स ब्लॉक को सहेजता है। |
| [setBitsPixel(short value)](#setBitsPixel-short-) | बिट्स पिक्सेल को प्राप्त करता है या सेट करता है। |
| [setFormat(int value)](#setFormat-int-) | थंबनेल डेटा फ़ॉर्मेट को प्राप्त करता है या सेट करता है। |
| [setHeight(int value)](#setHeight-int-) | थंबनेल की ऊँचाई पिक्सेल में प्राप्त करता है या सेट करता है। |
| [setID(short value)](#setID-short-) | रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है। |
| [setJpegOptions(JpegOptions value)](#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | JPEG विकल्पों को प्राप्त करता है या सेट करता है। |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | लेयर और मास्क जानकारी को प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | रिसोर्स नाम को प्राप्त करता है या सेट करता है। |
| [setPlanesCount(short value)](#setPlanesCount-short-) | प्लेन की गिनती को प्राप्त करता है या सेट करता है। |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | रिसोर्स ब्लॉक स्थिति को प्राप्त करता है या सेट करता है। |
| [setThumbnailArgb32Data(int[] value)](#setThumbnailArgb32Data-int---) | 32-बिट ARGB थंबनेल डेटा को प्राप्त करता है या सेट करता है। |
| [setThumbnailData(Color[] value)](#setThumbnailData-com.aspose.psd.Color---) | थंबनेल डेटा को प्राप्त करता है या सेट करता है। |
| [setWidth(int value)](#setWidth-int-) | थंबनेल की चौड़ाई पिक्सेल में प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | रिसोर्स मानों को वैध करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Thumbnail4Resource() {#Thumbnail4Resource--}
```
public Thumbnail4Resource()
```


नए [Thumbnail4Resource](../../com.aspose.psd.fileformats.psd.resources/thumbnail4resource) क्लास का एक नया उदाहरण आरंभ करता है।

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
### getBitsPixel() {#getBitsPixel--}
```
public final short getBitsPixel()
```


बिट्स पिक्सेल को प्राप्त करता है या सेट करता है।

मान: थंबनेल बिट्स पिक्सेल।

**Returns:**
short
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
### getFormat() {#getFormat--}
```
public final int getFormat()
```


थंबनेल डेटा फ़ॉर्मेट को प्राप्त करता है या सेट करता है।

मान: थंबनेल डेटा फ़ॉर्मेट।

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


थंबनेल की ऊँचाई पिक्सेल में प्राप्त करता है या सेट करता है।

मान: थंबनेल ऊँचाई।

**Returns:**
int
### getID() {#getID--}
```
public final short getID()
```


रिसोर्स के लिए यूनिक आइडेंटिफायर को प्राप्त करता है या सेट करता है।

मान: संसाधन के लिए अद्वितीय पहचानकर्ता।

**Returns:**
short
### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


JPEG विकल्पों को प्राप्त करता है या सेट करता है। यह तब उपयुक्त है जब थंबनेल रिसोर्स केवल JPEG फ़ाइल फ़ॉर्मेट में सहेजा जाता है। यह विकल्प तब प्रभावी नहीं होता जब RAW फ़ॉर्मेट परिभाषित किया गया हो।

मान: JPEG विकल्प।

**Returns:**
[JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions)
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


न्यूनतम आवश्यक PSD संस्करण को प्राप्त करता है।

मान: न्यूनतम psd संस्करण।

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
### getPlanesCount() {#getPlanesCount--}
```
public final short getPlanesCount()
```


प्लेन की गिनती को प्राप्त करता है या सेट करता है।

मान: थंबनेल प्लेन गिनती।

**Returns:**
short
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
### getSizeAfterCompression() {#getSizeAfterCompression--}
```
public final int getSizeAfterCompression()
```


संपीड़न के बाद आकार को प्राप्त करता है या सेट करता है। स्थिरता जाँच के लिए उपयोग किया जाता है।

मान: संपीड़न के बाद आकार।

**Returns:**
int
### getThumbnailArgb32Data() {#getThumbnailArgb32Data--}
```
public final int[] getThumbnailArgb32Data()
```


32-बिट ARGB थंबनेल डेटा को प्राप्त करता है या सेट करता है।

मान: 32-बिट ARGB थंबनेल डेटा।

**Returns:**
int[]
### getThumbnailData() {#getThumbnailData--}
```
public final Color[] getThumbnailData()
```


थंबनेल डेटा को प्राप्त करता है या सेट करता है।

मान: थंबनेल डेटा।

**Returns:**
com.aspose.psd.Color[]
### getTotalSize() {#getTotalSize--}
```
public final int getTotalSize()
```


कुल डेटा आकार को प्राप्त करता है।

मान: कुल डेटा आकार।

**Returns:**
int
### getWidth() {#getWidth--}
```
public final int getWidth()
```


थंबनेल की चौड़ाई पिक्सेल में प्राप्त करता है या सेट करता है।

मान: थंबनेल की चौड़ाई।

**Returns:**
int
### getWidthBytes() {#getWidthBytes--}
```
public final int getWidthBytes()
```


पंक्ति की चौड़ाई बाइट्स में प्राप्त करता है।

मान: बाइट्स में पंक्ति की चौड़ाई।

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

### setBitsPixel(short value) {#setBitsPixel-short-}
```
public final void setBitsPixel(short value)
```


बिट्स पिक्सेल को प्राप्त करता है या सेट करता है।

मान: थंबनेल बिट्स पिक्सेल।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setFormat(int value) {#setFormat-int-}
```
public final void setFormat(int value)
```


थंबनेल डेटा फ़ॉर्मेट को प्राप्त करता है या सेट करता है।

मान: थंबनेल डेटा फ़ॉर्मेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


थंबनेल की ऊँचाई पिक्सेल में प्राप्त करता है या सेट करता है।

मान: थंबनेल ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

### setJpegOptions(JpegOptions value) {#setJpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


JPEG विकल्पों को प्राप्त करता है या सेट करता है। यह तब उपयुक्त है जब थंबनेल रिसोर्स केवल JPEG फ़ाइल फ़ॉर्मेट में सहेजा जाता है। यह विकल्प तब प्रभावी नहीं होता जब RAW फ़ॉर्मेट परिभाषित किया गया हो।

मान: JPEG विकल्प।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) |  |

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

### setPlanesCount(short value) {#setPlanesCount-short-}
```
public final void setPlanesCount(short value)
```


प्लेन की गिनती को प्राप्त करता है या सेट करता है।

मान: थंबनेल प्लेन गिनती।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

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

### setThumbnailArgb32Data(int[] value) {#setThumbnailArgb32Data-int---}
```
public final void setThumbnailArgb32Data(int[] value)
```


32-बिट ARGB थंबनेल डेटा को प्राप्त करता है या सेट करता है।

मान: 32-बिट ARGB थंबनेल डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### setThumbnailData(Color[] value) {#setThumbnailData-com.aspose.psd.Color---}
```
public final void setThumbnailData(Color[] value)
```


थंबनेल डेटा को प्राप्त करता है या सेट करता है।

मान: थंबनेल डेटा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) |  |

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


थंबनेल की चौड़ाई पिक्सेल में प्राप्त करता है या सेट करता है।

मान: थंबनेल की चौड़ाई।

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

