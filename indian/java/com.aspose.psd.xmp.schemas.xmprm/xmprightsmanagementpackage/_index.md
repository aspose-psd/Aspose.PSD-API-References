---
title: "XmpRightsManagementPackage"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "XMP अधिकार प्रबंधन नेमस्पेस का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class XmpRightsManagementPackage extends XmpPackage
```

XMP अधिकार प्रबंधन नेमस्पेस का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage--) | XmpRightsManagementPackage क्लास का नया उदाहरण प्रारंभ करता है। |
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
| [setCertificate(String certificate)](#setCertificate-java.lang.String-) | प्रमाणपत्र सेट करता है। |
| [setMarkedAsRightManagement(boolean value)](#setMarkedAsRightManagement-boolean-) | राइट मैनेजमेंट सामग्री के रूप में चिह्नित करता है। |
| [setOwners(String[] owners)](#setOwners-java.lang.String---) | मालिक सेट करता है। |
| [setUsageTerms(LangAlt usageTerms)](#setUsageTerms-com.aspose.psd.xmp.LangAlt-) | उपयोग शर्तें सेट करता है। |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | मान सेट करता है। |
| [setWebStatement(String webStatementUrl)](#setWebStatement-java.lang.String-) | वेब स्टेटमेंट सेट करता है। |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP बूलियन मान सेट करता है। |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP अद्वितीय पहचानकर्ता सेट करता है। |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP प्रकार मान सेट करता है। |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | निर्दिष्ट कुंजी के साथ  Object  सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRightsManagementPackage() {#XmpRightsManagementPackage--}
```
public XmpRightsManagementPackage()
```


XmpRightsManagementPackage क्लास का नया उदाहरण प्रारंभ करता है।

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
### setCertificate(String certificate) {#setCertificate-java.lang.String-}
```
public void setCertificate(String certificate)
```


प्रमाणपत्र सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रमाणपत्र | java.lang.String | यह प्रमाणपत्र। |

### setMarkedAsRightManagement(boolean value) {#setMarkedAsRightManagement-boolean-}
```
public void setMarkedAsRightManagement(boolean value)
```


राइट मैनेजमेंट सामग्री के रूप में चिह्नित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | यदि इसे true पर सेट किया गया है तो यह एक राइट्स-मैनेज्ड संसाधन है। |

### setOwners(String[] owners) {#setOwners-java.lang.String---}
```
public void setOwners(String[] owners)
```


मालिक सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मालिक | java.lang.String[] | मालिक। |

### setUsageTerms(LangAlt usageTerms) {#setUsageTerms-com.aspose.psd.xmp.LangAlt-}
```
public void setUsageTerms(LangAlt usageTerms)
```


उपयोग शर्तें सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| usageTerms | [LangAlt](../../com.aspose.psd.xmp/langalt) | उपयोग शर्तें। |

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

### setWebStatement(String webStatementUrl) {#setWebStatement-java.lang.String-}
```
public void setWebStatement(String webStatementUrl)
```


वेब स्टेटमेंट सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| webStatementUrl | java.lang.String | वेब स्टेटमेंट URL। |

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

