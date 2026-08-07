---
title: "VstkResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "रिसोर्स क्लास VstkResource।"
type: docs
weight: 14
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class VstkResource extends LayerResource
```

रिसोर्स क्लास VstkResource। Vector Stroke डेटा के बारे में जानकारी रखता है। रिसोर्स को या तो resourcedata से AssignItems मेथड द्वारा, या क्लास की प्रॉपर्टीज़ को मान असाइन करके प्रारंभ किया जाना चाहिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [VstkResource()](#VstkResource--) | एक नया उदाहरण प्रारंभ करता है [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) क्लास का। |
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
| [assignItems_internalized(OSTypeStructure[] items)](#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Vstk रिसोर्स से आइटम संरचनाओं को असाइन करें। |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | जांचता है और सेट करता है यदि रिसोर्स PSB-विशिष्ट है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | ClassID इंस्टेंस को प्राप्त करता है या सेट करता है। |
| [getClassName_internalized()](#getClassName-internalized--) | क्लास नाम को प्राप्त करता है या सेट करता है। |
| [getFillEnabled()](#getFillEnabled--) | Stroke Fill सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getFillSettings()](#getFillSettings--) | Stroke के Fill सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [getStrokeEnabled()](#getStrokeEnabled--) | Stroke इफ़ेक्ट सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [getStrokeStyleBlendMode()](#getStrokeStyleBlendMode--) | प्राप्त करता है या सेट करता है Stroke Blend mode। |
| [getStrokeStyleContent()](#getStrokeStyleContent--) | प्राप्त करता है या सेट करता है Stroke entity। |
| [getStrokeStyleLineAlignment()](#getStrokeStyleLineAlignment--) | Stroke शैली की लाइन संरेखण को प्राप्त करता है या सेट करता है। |
| [getStrokeStyleLineCapType()](#getStrokeStyleLineCapType--) | प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन कैप का प्रकार। |
| [getStrokeStyleLineCapWidth()](#getStrokeStyleLineCapWidth--) | प्राप्त करता है या सेट करता है Stroke line cap width। |
| [getStrokeStyleLineDashOffset()](#getStrokeStyleLineDashOffset--) | प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन डैश ऑफसेट। |
| [getStrokeStyleLineDashSet()](#getStrokeStyleLineDashSet--) | लाइन डैश की एरे को प्राप्त करता है या सेट करता है। |
| [getStrokeStyleLineJoinType()](#getStrokeStyleLineJoinType--) | प्राप्त करता है या सेट करता है Stroke style line join type। |
| [getStrokeStyleLineWidth()](#getStrokeStyleLineWidth--) | प्राप्त करता है या सेट करता है Stroke line width। |
| [getStrokeStyleMiterLimit()](#getStrokeStyleMiterLimit--) | प्राप्त करता है या सेट करता है स्ट्रोक शैली मिटर लिमिट। |
| [getStrokeStyleOpacity()](#getStrokeStyleOpacity--) | प्राप्त करता है या सेट करता है Stroke style opacity (0-100%). |
| [getStrokeStyleResolution()](#getStrokeStyleResolution--) | प्राप्त करता है या सेट करता है Stroke style resolution। |
| [getStrokeStyleScaleLock()](#getStrokeStyleScaleLock--) | प्राप्त करता है या सेट करता है Stroke style scale lock। |
| [getStrokeStyleStrokeAdjust()](#getStrokeStyleStrokeAdjust--) | प्राप्त करता है या सेट करता है Stroke adjust। |
| [getStrokeStyleVersion()](#getStrokeStyleVersion--) | प्राप्त करता है या सेट करता है स्ट्रोक शैली संस्करण। |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | ClassID इंस्टेंस को प्राप्त करता है या सेट करता है। |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | क्लास नाम को प्राप्त करता है या सेट करता है। |
| [setFillEnabled(boolean value)](#setFillEnabled-boolean-) | Stroke Fill सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setFillSettings(IFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Stroke के Fill सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setStrokeEnabled(boolean value)](#setStrokeEnabled-boolean-) | Stroke इफ़ेक्ट सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [setStrokeStyleBlendMode(long value)](#setStrokeStyleBlendMode-long-) | प्राप्त करता है या सेट करता है Stroke Blend mode। |
| [setStrokeStyleContent(DescriptorStructure value)](#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) | प्राप्त करता है या सेट करता है Stroke entity। |
| [setStrokeStyleLineAlignment(short value)](#setStrokeStyleLineAlignment-short-) | Stroke शैली की लाइन संरेखण को प्राप्त करता है या सेट करता है। |
| [setStrokeStyleLineCapType(short value)](#setStrokeStyleLineCapType-short-) | प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन कैप का प्रकार। |
| [setStrokeStyleLineCapWidth(double value)](#setStrokeStyleLineCapWidth-double-) | प्राप्त करता है या सेट करता है Stroke line cap width। |
| [setStrokeStyleLineDashOffset(int value)](#setStrokeStyleLineDashOffset-int-) | प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन डैश ऑफसेट। |
| [setStrokeStyleLineDashSet(double[] value)](#setStrokeStyleLineDashSet-double---) | लाइन डैश की एरे को प्राप्त करता है या सेट करता है। |
| [setStrokeStyleLineJoinType(short value)](#setStrokeStyleLineJoinType-short-) | प्राप्त करता है या सेट करता है Stroke style line join type। |
| [setStrokeStyleLineWidth(double value)](#setStrokeStyleLineWidth-double-) | प्राप्त करता है या सेट करता है Stroke line width। |
| [setStrokeStyleMiterLimit(double value)](#setStrokeStyleMiterLimit-double-) | प्राप्त करता है या सेट करता है स्ट्रोक शैली मिटर लिमिट। |
| [setStrokeStyleOpacity(int value)](#setStrokeStyleOpacity-int-) | प्राप्त करता है या सेट करता है Stroke stryle opacity (0-100%). |
| [setStrokeStyleResolution(double value)](#setStrokeStyleResolution-double-) | प्राप्त करता है या सेट करता है Stroke style resolution। |
| [setStrokeStyleScaleLock(boolean value)](#setStrokeStyleScaleLock-boolean-) | प्राप्त करता है या सेट करता है Stroke style scale lock। |
| [setStrokeStyleStrokeAdjust(boolean value)](#setStrokeStyleStrokeAdjust-boolean-) | प्राप्त करता है या सेट करता है Stroke adjust। |
| [setStrokeStyleVersion(int value)](#setStrokeStyleVersion-int-) | प्राप्त करता है या सेट करता है स्ट्रोक शैली संस्करण। |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VstkResource() {#VstkResource--}
```
public VstkResource()
```


एक नया उदाहरण प्रारंभ करता है [VstkResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource) क्लास का।

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

### assignItems_internalized(OSTypeStructure[] items) {#assignItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void assignItems_internalized(OSTypeStructure[] items)
```


Vstk रिसोर्स से आइटम संरचनाओं को असाइन करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| items | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | OSTypeStructure इंस्टेंस की सूची। |

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
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


ClassID इंस्टेंस को प्राप्त करता है या सेट करता है।

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


क्लास नाम को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### getFillEnabled() {#getFillEnabled--}
```
public final boolean getFillEnabled()
```


Stroke Fill सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### getFillSettings() {#getFillSettings--}
```
public final IFillSettings getFillSettings()
```


Stroke के Fill सेटिंग्स को प्राप्त करता है या सेट करता है।

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
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
### getStrokeEnabled() {#getStrokeEnabled--}
```
public final boolean getStrokeEnabled()
```


Stroke इफ़ेक्ट सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### getStrokeStyleBlendMode() {#getStrokeStyleBlendMode--}
```
public final long getStrokeStyleBlendMode()
```


प्राप्त करता है या सेट करता है Stroke Blend mode।

**Returns:**
long
### getStrokeStyleContent() {#getStrokeStyleContent--}
```
public final DescriptorStructure getStrokeStyleContent()
```


प्राप्त करता है या सेट करता है Stroke entity। प्रॉपर्टी स्ट्रोक की भराव सेटिंग्स निर्धारित करती है।

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### getStrokeStyleLineAlignment() {#getStrokeStyleLineAlignment--}
```
public final short getStrokeStyleLineAlignment()
```


Stroke शैली की लाइन संरेखण को प्राप्त करता है या सेट करता है।

**Returns:**
short
### getStrokeStyleLineCapType() {#getStrokeStyleLineCapType--}
```
public final short getStrokeStyleLineCapType()
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन कैप का प्रकार।

मान: स्ट्रोक शैली लाइन कैप का प्रकार।

**Returns:**
short
### getStrokeStyleLineCapWidth() {#getStrokeStyleLineCapWidth--}
```
public final double getStrokeStyleLineCapWidth()
```


प्राप्त करता है या सेट करता है Stroke line cap width।

**Returns:**
double
### getStrokeStyleLineDashOffset() {#getStrokeStyleLineDashOffset--}
```
public final int getStrokeStyleLineDashOffset()
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन डैश ऑफसेट।

मान: स्ट्रोक शैली लाइन डैश ऑफसेट।

**Returns:**
int
### getStrokeStyleLineDashSet() {#getStrokeStyleLineDashSet--}
```
public final Double[] getStrokeStyleLineDashSet()
```


लाइन डैश की एरे को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.Double[]
### getStrokeStyleLineJoinType() {#getStrokeStyleLineJoinType--}
```
public final short getStrokeStyleLineJoinType()
```


प्राप्त करता है या सेट करता है Stroke style line join type।

**Returns:**
short
### getStrokeStyleLineWidth() {#getStrokeStyleLineWidth--}
```
public final double getStrokeStyleLineWidth()
```


प्राप्त करता है या सेट करता है Stroke line width।

**Returns:**
double
### getStrokeStyleMiterLimit() {#getStrokeStyleMiterLimit--}
```
public final double getStrokeStyleMiterLimit()
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली मिटर लिमिट।

मान: स्ट्रोक शैली मिटर लिमिट।

**Returns:**
double
### getStrokeStyleOpacity() {#getStrokeStyleOpacity--}
```
public final int getStrokeStyleOpacity()
```


प्राप्त करता है या सेट करता है Stroke style opacity (0-100%).

**Returns:**
int
### getStrokeStyleResolution() {#getStrokeStyleResolution--}
```
public final double getStrokeStyleResolution()
```


प्राप्त करता है या सेट करता है Stroke style resolution।

**Returns:**
double
### getStrokeStyleScaleLock() {#getStrokeStyleScaleLock--}
```
public final boolean getStrokeStyleScaleLock()
```


प्राप्त करता है या सेट करता है Stroke style scale lock।

**Returns:**
boolean
### getStrokeStyleStrokeAdjust() {#getStrokeStyleStrokeAdjust--}
```
public final boolean getStrokeStyleStrokeAdjust()
```


प्राप्त करता है या सेट करता है Stroke adjust।

**Returns:**
boolean
### getStrokeStyleVersion() {#getStrokeStyleVersion--}
```
public final int getStrokeStyleVersion()
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली संस्करण।

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

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


ClassID इंस्टेंस को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


क्लास नाम को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFillEnabled(boolean value) {#setFillEnabled-boolean-}
```
public final void setFillEnabled(boolean value)
```


Stroke Fill सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setFillSettings(IFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillSettings(IFillSettings value)
```


Stroke के Fill सेटिंग्स को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

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

### setStrokeEnabled(boolean value) {#setStrokeEnabled-boolean-}
```
public final void setStrokeEnabled(boolean value)
```


Stroke इफ़ेक्ट सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStrokeStyleBlendMode(long value) {#setStrokeStyleBlendMode-long-}
```
public final void setStrokeStyleBlendMode(long value)
```


प्राप्त करता है या सेट करता है Stroke Blend mode।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setStrokeStyleContent(DescriptorStructure value) {#setStrokeStyleContent-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public final void setStrokeStyleContent(DescriptorStructure value)
```


प्राप्त करता है या सेट करता है Stroke entity। प्रॉपर्टी स्ट्रोक की भराव सेटिंग्स निर्धारित करती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

### setStrokeStyleLineAlignment(short value) {#setStrokeStyleLineAlignment-short-}
```
public final void setStrokeStyleLineAlignment(short value)
```


Stroke शैली की लाइन संरेखण को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setStrokeStyleLineCapType(short value) {#setStrokeStyleLineCapType-short-}
```
public final void setStrokeStyleLineCapType(short value)
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन कैप का प्रकार।

मान: स्ट्रोक शैली लाइन कैप का प्रकार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setStrokeStyleLineCapWidth(double value) {#setStrokeStyleLineCapWidth-double-}
```
public final void setStrokeStyleLineCapWidth(double value)
```


प्राप्त करता है या सेट करता है Stroke line cap width।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setStrokeStyleLineDashOffset(int value) {#setStrokeStyleLineDashOffset-int-}
```
public final void setStrokeStyleLineDashOffset(int value)
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली लाइन डैश ऑफसेट।

मान: स्ट्रोक शैली लाइन डैश ऑफसेट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStrokeStyleLineDashSet(double[] value) {#setStrokeStyleLineDashSet-double---}
```
public final void setStrokeStyleLineDashSet(double[] value)
```


लाइन डैश की एरे को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double[] |  |

### setStrokeStyleLineJoinType(short value) {#setStrokeStyleLineJoinType-short-}
```
public final void setStrokeStyleLineJoinType(short value)
```


प्राप्त करता है या सेट करता है Stroke style line join type।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setStrokeStyleLineWidth(double value) {#setStrokeStyleLineWidth-double-}
```
public final void setStrokeStyleLineWidth(double value)
```


प्राप्त करता है या सेट करता है Stroke line width।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setStrokeStyleMiterLimit(double value) {#setStrokeStyleMiterLimit-double-}
```
public final void setStrokeStyleMiterLimit(double value)
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली मिटर लिमिट।

मान: स्ट्रोक शैली मिटर लिमिट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setStrokeStyleOpacity(int value) {#setStrokeStyleOpacity-int-}
```
public final void setStrokeStyleOpacity(int value)
```


प्राप्त करता है या सेट करता है Stroke stryle opacity (0-100%).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStrokeStyleResolution(double value) {#setStrokeStyleResolution-double-}
```
public final void setStrokeStyleResolution(double value)
```


प्राप्त करता है या सेट करता है Stroke style resolution।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setStrokeStyleScaleLock(boolean value) {#setStrokeStyleScaleLock-boolean-}
```
public final void setStrokeStyleScaleLock(boolean value)
```


प्राप्त करता है या सेट करता है Stroke style scale lock।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStrokeStyleStrokeAdjust(boolean value) {#setStrokeStyleStrokeAdjust-boolean-}
```
public final void setStrokeStyleStrokeAdjust(boolean value)
```


प्राप्त करता है या सेट करता है Stroke adjust।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setStrokeStyleVersion(int value) {#setStrokeStyleVersion-int-}
```
public final void setStrokeStyleVersion(int value)
```


प्राप्त करता है या सेट करता है स्ट्रोक शैली संस्करण।

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

