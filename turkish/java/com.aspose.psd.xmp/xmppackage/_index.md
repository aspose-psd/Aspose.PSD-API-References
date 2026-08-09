---
title: "XmpPackage"
second_title: "Java için Aspose.PSD API Referansı"
description: "XMP paketi için temel soyutlamayı temsil eder."
type: docs
weight: 18
url: /tr/java/com.aspose.psd.xmp/xmppackage/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class XmpPackage implements IXmlValue, System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,Object>>
```

XMP paketi için temel soyutlamayı temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpPackage(String prefix, String namespaceUri)](#XmpPackage-java.lang.String-java.lang.String-) | XmpPackage sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Karmaşık tip ad alanını ekler. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Değeri ekler. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Belirtilen XMP paketini mevcut olana atar. |
| [clear()](#clear--) | Bu örneği temizler. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Paketi birleştirir. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Belirtilen anahtarın anahtar içerip içermediğini belirler. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | XMP paketindeki anahtarları alır. |
| [getNamespaceUri()](#getNamespaceUri--) | Ad alanı URI'sını alır. |
| [getPrefix()](#getPrefix--) | Ön eki alır. |
| [getXmlNamespace()](#getXmlNamespace--) | XML ad alanını alır. |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Belirtilen anahtara sahip Object'i alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratör döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Belirtilen anahtara sahip değeri kaldır. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Değeri ayarlar. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP boolean değerini ayarlar. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP benzersiz tanımlayıcısını ayarlar. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP tip değerini ayarlar. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen anahtara sahip  Object  ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPackage(String prefix, String namespaceUri) {#XmpPackage-java.lang.String-java.lang.String-}
```
public XmpPackage(String prefix, String namespaceUri)
```


XmpPackage sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | java.lang.String | Önek. |
| namespaceUri | java.lang.String | Namespace URI'si. |

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Karmaşık tip ad alanını ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typePrefix | java.lang.String | Tür öneki. |
| typeNamespaceUri | java.lang.String | Tür ad alanı URI'si. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Değeri ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.String | Eklenecek değer. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Belirtilen XMP paketini mevcut olana atar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | XMP paketi. |

### clear() {#clear--}
```
public void clear()
```


Bu örneği temizler.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Paketi birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Birleştirilecek diğer paket. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Belirtilen anahtarın anahtar içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Kontrol edilecek anahtar. |

**Returns:**
boolean - Belirtilen anahtar anahtarı içeriyorsa true döndürür.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Bu örneği klonlar.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


XMP paketindeki anahtarları alır.

Değer: XMP paketindeki anahtarlar.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Ad alanı URI'sını alır.

Değer: Ad alanı URI'si.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ön eki alır.

Değer: Önek.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


XML ad alanını alır.

Değer: XML ad alanı.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML temsiline dönüştürülmüş olarak döndürür.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Belirtilen anahtara sahip Object'i alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Değeri tanımlayan anahtar. |

**Returns:**
java.lang.Object - Belirtilen anahtara sahip  Object  nesnesini döndürür.
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


Koleksiyon içinde yineleme yapan bir enumeratör döndürür.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir  T:System.Collections.Generic.IEnumerator1  .
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


Belirtilen anahtara sahip değeri kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Kaldırılan değerle tanımlanan anahtarın dize temsili. |

**Returns:**
boolean - Belirtilen anahtara sahip değer kaldırıldıysa true döndürür.
### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | Eklenecek değer. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


XMP boolean değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Anahtarın ayarlanmış değer ile tanımlanan dize temsili. |
| boolValue | java.lang.String | Boolean değeri. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


XMP benzersiz tanımlayıcısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Ayarlanan GUID değeriyle tanımlanan anahtarın dize temsili. |
| guid | java.lang.String | Benzersiz tanımlayıcı. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


XMP tip değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Anahtarın ayarlanmış değer ile tanımlanan dize temsili. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | Ayarlanacak değer. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Belirtilen anahtara sahip  Object  ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Değeri tanımlayan anahtar. |
| değer | java.lang.Object | Bu  Object  değeri. |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

