---
title: "TypeToolInfo6Resource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "यह टाइप टूल जानकारी।"
type: docs
weight: 78
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfo6Resource extends LayerResource
```

type tool जानकारी। PSD संस्करण 6.0 या उससे अधिक के लिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)](#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | नया उदाहरण प्रारंभ करता है [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource) क्लास का। |
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
| [getBottom()](#getBottom--) | नीचे की स्थिति को प्राप्त करता है या सेट करता है। |
| [getBoundingBox_internalized()](#getBoundingBox-internalized--) | टेक्स्ट बॉक्स में टेक्स्ट बाउंड्स को प्राप्त करता है या सेट करता है। |
| [getBounds_internalized()](#getBounds-internalized--) | टेक्स्ट बॉक्स बाउंड्स को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getClassID()](#getClassID--) | क्लास ID को प्राप्त करता है या सेट करता है। |
| [getClassName()](#getClassName--) | क्लास नाम को प्राप्त करता है या सेट करता है। |
| [getDescriptorVersion()](#getDescriptorVersion--) | डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getItems()](#getItems--) | आइटम्स को प्राप्त या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLeft()](#getLeft--) | बाएँ स्थिति को प्राप्त करता है या सेट करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getParsedTyShModel_internalized()](#getParsedTyShModel-internalized--) | कच्चे डेटा को TyShRoot क्लास उदाहरण में पार्स करें। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getRawDataStructure_internalized()](#getRawDataStructure-internalized--) | यदि मौजूद हो तो [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) आइटम प्राप्त करता है। |
| [getRight()](#getRight--) | दाईं स्थिति प्राप्त करता है या सेट करता है। |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [getTextIndex_internalized()](#getTextIndex-internalized--) | इस संसाधन में पाठ का अनुक्रमांक प्राप्त करता है। |
| [getTextVersion()](#getTextVersion--) | पाठ संस्करण प्राप्त करता है या सेट करता है। |
| [getTop()](#getTop--) | ऊपरी स्थिति प्राप्त करता है या सेट करता है। |
| [getTransformMatrix()](#getTransformMatrix--) | रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है. |
| [getVersion()](#getVersion--) | टाइप टूल संस्करण प्राप्त करता है या सेट करता है। |
| [getWarpClassID()](#getWarpClassID--) | क्लास ID को प्राप्त करता है या सेट करता है। |
| [getWarpClassName()](#getWarpClassName--) | वार्प क्लास नाम को प्राप्त करता है या सेट करता है। |
| [getWarpDescriptorVersion()](#getWarpDescriptorVersion--) | वार्प डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है। |
| [getWarpItems()](#getWarpItems--) | warp आइटम्स को प्राप्त करता है या सेट करता है। |
| [getWarpVersion()](#getWarpVersion--) | वार्प संस्करण को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setBottom(int value)](#setBottom-int-) | नीचे की स्थिति को प्राप्त करता है या सेट करता है। |
| [setBoundingBox_internalized(RectangleF value)](#setBoundingBox-internalized-com.aspose.psd.RectangleF-) | टेक्स्ट बॉक्स में टेक्स्ट बाउंड्स को प्राप्त करता है या सेट करता है। |
| [setClassID(ClassID value)](#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | क्लास ID को प्राप्त करता है या सेट करता है। |
| [setClassName(String value)](#setClassName-java.lang.String-) | क्लास नाम को प्राप्त करता है या सेट करता है। |
| [setDescriptorVersion(int value)](#setDescriptorVersion-int-) | डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | आइटम्स को प्राप्त या सेट करता है। |
| [setLeft(int value)](#setLeft-int-) | बाएँ स्थिति को प्राप्त करता है या सेट करता है। |
| [setRight(int value)](#setRight-int-) | दाईं स्थिति प्राप्त करता है या सेट करता है। |
| [setTextVersion(short value)](#setTextVersion-short-) | पाठ संस्करण प्राप्त करता है या सेट करता है। |
| [setTop(int value)](#setTop-int-) | ऊपरी स्थिति प्राप्त करता है या सेट करता है। |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है. |
| [setVersion(short value)](#setVersion-short-) | टाइप टूल संस्करण प्राप्त करता है या सेट करता है। |
| [setWarpClassID(ClassID value)](#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | क्लास ID को प्राप्त करता है या सेट करता है। |
| [setWarpClassName(String value)](#setWarpClassName-java.lang.String-) | वार्प क्लास नाम को प्राप्त करता है या सेट करता है। |
| [setWarpDescriptorVersion(int value)](#setWarpDescriptorVersion-int-) | वार्प डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है। |
| [setWarpItems(OSTypeStructure[] value)](#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | warp आइटम्स को प्राप्त करता है या सेट करता है। |
| [setWarpVersion(short value)](#setWarpVersion-short-) | वार्प संस्करण को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [updateFromTyShModel_internalized(TyShRoot dataModel)](#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-) | TyShRoot डेटा को कच्चे रूप में क्रमबद्ध करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfo6Resource(ClassID classID, ClassID warpClassID) {#TypeToolInfo6Resource-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public TypeToolInfo6Resource(ClassID classID, ClassID warpClassID)
```


नया उदाहरण प्रारंभ करता है [TypeToolInfo6Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource) क्लास का।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| classID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | क्लास ID। |
| warpClassID | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) | वॉर्प क्लास आईडी। |

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
### getBottom() {#getBottom--}
```
public final int getBottom()
```


नीचे की स्थिति को प्राप्त करता है या सेट करता है।

मान: नीचे की स्थिति।

**Returns:**
int
### getBoundingBox_internalized() {#getBoundingBox-internalized--}
```
public final RectangleF getBoundingBox_internalized()
```


टेक्स्ट बॉक्स में टेक्स्ट बाउंड्स को प्राप्त करता है या सेट करता है।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getBounds_internalized() {#getBounds-internalized--}
```
public final RectangleF getBounds_internalized()
```


टेक्स्ट बॉक्स बाउंड्स को प्राप्त करता है या सेट करता है।

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassID() {#getClassID--}
```
public final ClassID getClassID()
```


क्लास ID को प्राप्त करता है या सेट करता है।

मान: क्लास आईडी।

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName() {#getClassName--}
```
public final String getClassName()
```


क्लास नाम को प्राप्त करता है या सेट करता है।

मान: क्लास नाम।

**Returns:**
java.lang.String
### getDescriptorVersion() {#getDescriptorVersion--}
```
public final int getDescriptorVersion()
```


डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है।

मान: डिस्क्रिप्टर संस्करण।

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


आइटम्स को प्राप्त या सेट करता है।

मान: आइटम।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getKey() {#getKey--}
```
public final int getKey()
```


लेयर रिसोर्स कुंजी प्राप्त करता है।

**Returns:**
int
### getLeft() {#getLeft--}
```
public final int getLeft()
```


बाएँ स्थिति को प्राप्त करता है या सेट करता है।

मान: बाईं स्थिति।

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है।

**Returns:**
int
### getParsedTyShModel_internalized() {#getParsedTyShModel-internalized--}
```
public final TyShRoot getParsedTyShModel_internalized()
```


कच्चे डेटा को TyShRoot क्लास उदाहरण में पार्स करें।

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot - TyShRoot क्लास इंस्टेंस के रूप में कच्चा डेटा।
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
### getRawDataStructure_internalized() {#getRawDataStructure-internalized--}
```
public final RawDataStructure getRawDataStructure_internalized()
```


यदि मौजूद हो तो [RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) आइटम प्राप्त करता है।

**Returns:**
[RawDataStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/rawdatastructure) - The raw data structure.
### getRight() {#getRight--}
```
public final int getRight()
```


दाईं स्थिति प्राप्त करता है या सेट करता है।

मान: दाईं स्थिति।

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


लेयर रिसोर्स सिग्नेचर प्राप्त करता है।

**Returns:**
int
### getTextIndex_internalized() {#getTextIndex-internalized--}
```
public final int getTextIndex_internalized()
```


इस संसाधन में पाठ का अनुक्रमांक प्राप्त करता है।

**Returns:**
int - इस संसाधन में पाठ का अनुक्रमांक लौटाता है।
### getTextVersion() {#getTextVersion--}
```
public final short getTextVersion()
```


पाठ संस्करण प्राप्त करता है या सेट करता है।

मान: पाठ संस्करण।

**Returns:**
short
### getTop() {#getTop--}
```
public final int getTop()
```


ऊपरी स्थिति प्राप्त करता है या सेट करता है।

मान: ऊपरी स्थिति।

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है.

मान: ट्रांसफ़ॉर्म मैट्रिक्स।

**Returns:**
double[]
### getVersion() {#getVersion--}
```
public final short getVersion()
```


टाइप टूल संस्करण प्राप्त करता है या सेट करता है।

मान: टाइप टूल संस्करण।

**Returns:**
short
### getWarpClassID() {#getWarpClassID--}
```
public final ClassID getWarpClassID()
```


क्लास ID को प्राप्त करता है या सेट करता है।

मान: क्लास आईडी।

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getWarpClassName() {#getWarpClassName--}
```
public final String getWarpClassName()
```


वार्प क्लास नाम को प्राप्त करता है या सेट करता है।

मान: वॉर्प क्लास नाम।

**Returns:**
java.lang.String
### getWarpDescriptorVersion() {#getWarpDescriptorVersion--}
```
public final int getWarpDescriptorVersion()
```


वार्प डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है।

मान: वॉर्प डिस्क्रिप्टर संस्करण।

**Returns:**
int
### getWarpItems() {#getWarpItems--}
```
public final OSTypeStructure[] getWarpItems()
```


warp आइटम्स को प्राप्त करता है या सेट करता है।

मान: वॉर्प वस्तुएँ।

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getWarpVersion() {#getWarpVersion--}
```
public final short getWarpVersion()
```


वार्प संस्करण को प्राप्त करता है या सेट करता है।

मान: वॉर्प संस्करण।

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

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


नीचे की स्थिति को प्राप्त करता है या सेट करता है।

मान: नीचे की स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBoundingBox_internalized(RectangleF value) {#setBoundingBox-internalized-com.aspose.psd.RectangleF-}
```
public final void setBoundingBox_internalized(RectangleF value)
```


टेक्स्ट बॉक्स में टेक्स्ट बाउंड्स को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### setClassID(ClassID value) {#setClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassID(ClassID value)
```


क्लास ID को प्राप्त करता है या सेट करता है।

मान: क्लास आईडी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName(String value) {#setClassName-java.lang.String-}
```
public final void setClassName(String value)
```


क्लास नाम को प्राप्त करता है या सेट करता है।

मान: क्लास नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDescriptorVersion(int value) {#setDescriptorVersion-int-}
```
public final void setDescriptorVersion(int value)
```


डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है।

मान: डिस्क्रिप्टर संस्करण।

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


आइटम्स को प्राप्त या सेट करता है।

मान: आइटम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


बाएँ स्थिति को प्राप्त करता है या सेट करता है।

मान: बाईं स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


दाईं स्थिति प्राप्त करता है या सेट करता है।

मान: दाईं स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTextVersion(short value) {#setTextVersion-short-}
```
public final void setTextVersion(short value)
```


पाठ संस्करण प्राप्त करता है या सेट करता है।

मान: पाठ संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


ऊपरी स्थिति प्राप्त करता है या सेट करता है।

मान: ऊपरी स्थिति।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है.

मान: ट्रांसफ़ॉर्म मैट्रिक्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double[] |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


टाइप टूल संस्करण प्राप्त करता है या सेट करता है।

मान: टाइप टूल संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setWarpClassID(ClassID value) {#setWarpClassID-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setWarpClassID(ClassID value)
```


क्लास ID को प्राप्त करता है या सेट करता है।

मान: क्लास आईडी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setWarpClassName(String value) {#setWarpClassName-java.lang.String-}
```
public final void setWarpClassName(String value)
```


वार्प क्लास नाम को प्राप्त करता है या सेट करता है।

मान: वॉर्प क्लास नाम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setWarpDescriptorVersion(int value) {#setWarpDescriptorVersion-int-}
```
public final void setWarpDescriptorVersion(int value)
```


वार्प डिस्क्रिप्टर संस्करण को प्राप्त करता है या सेट करता है।

मान: वॉर्प डिस्क्रिप्टर संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setWarpItems(OSTypeStructure[] value) {#setWarpItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setWarpItems(OSTypeStructure[] value)
```


warp आइटम्स को प्राप्त करता है या सेट करता है।

मान: वॉर्प वस्तुएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setWarpVersion(short value) {#setWarpVersion-short-}
```
public final void setWarpVersion(short value)
```


वार्प संस्करण को प्राप्त करता है या सेट करता है।

मान: वॉर्प संस्करण।

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
### updateFromTyShModel_internalized(TyShRoot dataModel) {#updateFromTyShModel-internalized-com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot-}
```
public final void updateFromTyShModel_internalized(TyShRoot dataModel)
```


TyShRoot डेटा को कच्चे रूप में क्रमबद्ध करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| डेटा मॉडल | com.aspose.internal.fileformats.psd.layers.text.tyshresource.tyshmodels.TyShRoot |  |

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

