---
title: "XmpBasicPackage"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "XMP बेसिक नेमस्पेस का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

XMP बेसिक नेमस्पेस का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | XmpBasicPackage वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | XmpBasicPackage वर्ग की एक नई इंस्टेंस को प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [RatingMax](#RatingMax) | रेटिंग अधिकतम मान। |
| [RatingMin](#RatingMin) | रेटिंग न्यूनतम मान। |
| [RatingRejected](#RatingRejected) | रेटिंग अस्वीकृत मान। |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | निर्दिष्ट कुंजी के साथ ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | कलेक्शन के माध्यम से इटररेट करने वाला एन्यूमरेटर लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | निर्दिष्ट कुंजी के साथ मान को हटाएँ। |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | संसाधन निर्माण तिथि जोड़ता है। |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | संसाधन निर्माण तिथि जोड़ता है। |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | निर्माता टूल सेट करता है। |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | पहचानकर्ता सेट करता है। |
| [setLabel(String label)](#setLabel-java.lang.String-) | लेबल सेट करता है। |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | मेटाडेटा अंतिम परिवर्तन तिथि जोड़ता है। |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | मेटाडेटा अंतिम परिवर्तन तिथि जोड़ता है। |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | संसाधन अंतिम संशोधित तिथि जोड़ता है। |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | संसाधन अंतिम संशोधित तिथि जोड़ता है। |
| [setRating(int choise)](#setRating-int-) | रेटिंग सेट करता है। |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | मान सेट करता है। |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP बूलियन मान सेट करता है। |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP अद्वितीय पहचानकर्ता सेट करता है। |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP प्रकार मान सेट करता है। |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट कुंजी के साथ ऑब्जेक्ट को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


XmpBasicPackage वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


XmpBasicPackage वर्ग की एक नई इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| उपसर्ग | java.lang.String | उपसर्ग। |
| namespaceUri | java.lang.String | नेमस्पेस URI। |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


रेटिंग अधिकतम मान।

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


रेटिंग न्यूनतम मान।

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


रेटिंग अस्वीकृत मान।

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


निर्दिष्ट कुंजी के साथ ऑब्जेक्ट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान को पहचानने वाली कुंजी। मान: ऑब्जेक्ट। |

**Returns:**
java.lang.Object - निर्दिष्ट कुंजी के साथ ऑब्जेक्ट लौटाता है।
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


संसाधन निर्माण तिथि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createdDate | java.lang.String | निर्माण तिथि। |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


संसाधन निर्माण तिथि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | निर्माण तिथि। |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


निर्माता टूल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| creatorTool | java.lang.String | टूल का नाम। |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


पहचानकर्ता सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पहचानकर्ता | java.lang.String[] | पहचानकर्ता। |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


लेबल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | java.lang.String | लेबल। |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


मेटाडेटा अंतिम परिवर्तन तिथि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| metadataDate | java.lang.String | मेटाडेटा तिथि। |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


मेटाडेटा अंतिम परिवर्तन तिथि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | मेटाडेटा तिथि। |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


संसाधन अंतिम संशोधित तिथि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| modifiedDate | java.lang.String | अंतिम संशोधित तिथि। |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


संसाधन अंतिम संशोधित तिथि जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | अंतिम संशोधित तिथि। |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


रेटिंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| चयन | int | -1 से 5 तक |

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


निर्दिष्ट कुंजी के साथ ऑब्जेक्ट को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | मान को पहचानने वाली कुंजी। मान: ऑब्जेक्ट। |
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

