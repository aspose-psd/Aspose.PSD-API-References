---
title: "PhotoshopPackage"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "Adobe Photoshop नेमस्पेस का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Adobe Photoshop नेमस्पेस का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | PhotoshopPackage क्लास की नई इंस्टेंस को प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | तत्कालता अधिकतम मान। |
| [UrgencyMin](#UrgencyMin) | तत्कालता न्यूनतम मान। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | जटिल प्रकार नेमस्पेस जोड़ता है। |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | स्ट्रिंग प्रॉपर्टी जोड़ता है। |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | निर्दिष्ट XMP पैकेज को वर्तमान वाले को असाइन करता है। |
| [clear()](#clear--) | इस इंस्टेंस को साफ़ करता है। |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | पैकेज को संयोजित करता है। |
| [containsKey(String key)](#containsKey-java.lang.String-) | निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी शामिल है या नहीं। |
| [deepClone_internalized()](#deepClone-internalized--) | इस उदाहरण को क्लोन करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | XMP पैकेज में कुंजियों को प्राप्त करता है। |
| [getNamespaceUri()](#getNamespaceUri--) | नेमस्पेस URI को प्राप्त करता है। |
| [getPrefix()](#getPrefix--) | प्रिफिक्स को प्राप्त करता है। |
| [getXmlNamespace()](#getXmlNamespace--) | XML नेमस्पेस को प्राप्त करता है। |
| [getXmlValue()](#getXmlValue--) | XMP मान को XML प्रतिनिधित्व में बदलता है। |
| [get_Item(String key)](#get-Item-java.lang.String-) | निर्दिष्ट कुंजी के साथ Object को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | निर्दिष्ट कुंजी के साथ मान को हटाएँ। |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | लेखकों की स्थिति सेट करता है। |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | कैप्शन लेखक सेट करता है। |
| [setCategory(String category)](#setCategory-java.lang.String-) | श्रेणी सेट करता है। |
| [setCity(String city)](#setCity-java.lang.String-) | शहर सेट करता है। |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | रंग मोड सेट करता है। |
| [setCountry(String country)](#setCountry-java.lang.String-) | देश सेट करता है। |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | निर्माण तिथि सेट करता है। |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | क्रेडिट सेट करता है। |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | दस्तावेज़ पूर्वज सेट करता है। |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | हेडलाइन सेट करता है। |
| [setHistory(String history)](#setHistory-java.lang.String-) | इतिहास सेट करता है। |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | icc प्रोफ़ाइल सेट करता है। |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | निर्देश सेट करता है। |
| [setSource(String source)](#setSource-java.lang.String-) | स्रोत सेट करता है। |
| [setState(String state)](#setState-java.lang.String-) | राज्य सेट करता है। |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | पूरक श्रेणियाँ सेट करता है। |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | ट्रांसमिशन रेफ़रेंस सेट करता है। |
| [setUrgency(int urgency)](#setUrgency-int-) | तत्कालता सेट करता है। |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | मान सेट करता है। |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP बूलियन मान सेट करता है। |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP अद्वितीय पहचानकर्ता सेट करता है। |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP प्रकार मान सेट करता है। |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट कुंजी के साथ  Object  सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


PhotoshopPackage क्लास की नई इंस्टेंस को प्रारंभ करता है।

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


तत्कालता अधिकतम मान।

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


तत्कालता न्यूनतम मान।

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


जटिल प्रकार नेमस्पेस जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| typePrefix | java.lang.String | प्रकार उपसर्ग। |
| typeNamespaceUri | java.lang.String | प्रकार नेमस्पेस URI। |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


स्ट्रिंग प्रॉपर्टी जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | कुंजी का स्ट्रिंग प्रतिनिधित्व जो जोड़े गए मान के साथ पहचाना जाता है। |
| मान | java.lang.String | स्ट्रिंग मान। |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


निर्दिष्ट XMP पैकेज को वर्तमान वाले को असाइन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | XMP पैकेज। |

### clear() {#clear--}
```
public void clear()
```


इस इंस्टेंस को साफ़ करता है।

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


पैकेज को संयोजित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | संयोजन के लिए अन्य पैकेज। |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


निर्धारित करता है कि निर्दिष्ट कुंजी में कुंजी शामिल है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | जाँचने के लिए कुंजी। |

**Returns:**
boolean - यदि निर्दिष्ट कुंजी में कुंजी मौजूद हो तो true लौटाता है।
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


इस उदाहरण को क्लोन करता है।

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
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
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


XMP पैकेज में कुंजियों को प्राप्त करता है।

मान: XMP पैकेज में कुंजियाँ।

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


नेमस्पेस URI को प्राप्त करता है।

मान: नेमस्पेस URI।

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


प्रिफिक्स को प्राप्त करता है।

मान: उपसर्ग।

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


XML नेमस्पेस को प्राप्त करता है।

मान: XML नेमस्पेस।

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP मान को XML प्रतिनिधित्व में बदलता है।

**Returns:**
java.lang.String - XMP मान को XML प्रतिनिधित्व में परिवर्तित करके लौटाता है।
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


निर्दिष्ट कुंजी के साथ Object को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान को पहचानने वाली कुंजी। |

**Returns:**
java.lang.Object - निर्दिष्ट कुंजी के साथ  Object  लौटाता है।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


कलेक्शन के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है।

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - एक  T:System.Collections.Generic.IEnumerator1  जो संग्रह के माध्यम से इटररेट करने के लिए उपयोग किया जा सकता है।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


निर्दिष्ट कुंजी के साथ मान को हटाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | हटाए गए मान के साथ पहचानी गई कुंजी का स्ट्रिंग प्रतिनिधित्व। |

**Returns:**
boolean - यदि निर्दिष्ट कुंजी के साथ मान हटाया गया हो तो true लौटाता है।
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


लेखकों की स्थिति सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| authorsPosition | java.lang.String | लेखकों की स्थिति। |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


कैप्शन लेखक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| captionWriter | java.lang.String | कैप्शन लेखक। |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


श्रेणी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| category | java.lang.String | श्रेणी। |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


शहर सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| city | java.lang.String | शहर का नाम। |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


रंग मोड सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorMode | byte | रंग मोड। |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


देश सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| country | java.lang.String | देश। |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


निर्माण तिथि सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createdDate | java.util.Date | निर्माण तिथि। |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


क्रेडिट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| credit | java.lang.String | क्रेडिट। |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


दस्तावेज़ पूर्वज सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| ancestors | java.lang.String[] | पूर्वज। |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


हेडलाइन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| headline | java.lang.String | हेडलाइन। |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


इतिहास सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| history | java.lang.String | इतिहास। |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


icc प्रोफ़ाइल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| iccProfile | java.lang.String | icc प्रोफ़ाइल। |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


निर्देश सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| निर्देश | java.lang.String | निर्देश। |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


स्रोत सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्रोत | java.lang.String | स्रोत। |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


राज्य सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्थिति | java.lang.String | स्थिति। |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


पूरक श्रेणियाँ सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | पूरक श्रेणियाँ। |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


ट्रांसमिशन रेफ़रेंस सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| transmissionReference | java.lang.String | प्रसारण संदर्भ। |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


तत्कालता सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | urgency | int | तत्कालता। |

तत्कालता 1 से 8 के बीच होनी चाहिए। |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | कुंजी का स्ट्रिंग प्रतिनिधित्व जो जोड़े गए मान के साथ पहचाना जाता है। |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | जोड़ने के लिए मान। |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


XMP बूलियन मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | सेट मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| boolValue | java.lang.String | बूलियन मान। |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


XMP अद्वितीय पहचानकर्ता सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | सेट GUID मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| guid | java.lang.String | अद्वितीय पहचानकर्ता। |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


XMP प्रकार मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | सेट मान के साथ पहचाने गए कुंजी का स्ट्रिंग प्रतिनिधित्व। |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | सेट करने के लिए मान। |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


निर्दिष्ट कुंजी के साथ  Object  सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान को पहचानने वाली कुंजी। |
| मान | java.lang.Object | ऑब्जेक्ट मान। |

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

