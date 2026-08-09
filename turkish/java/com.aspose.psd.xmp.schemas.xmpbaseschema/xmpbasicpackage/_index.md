---
title: "XmpBasicPackage"
second_title: "Java için Aspose.PSD API Referansı"
description: "XMP temel ad alanını temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

XMP temel ad alanını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | XmpBasicPackage sınıfının yeni bir örneğini başlatır. |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | XmpBasicPackage sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [RatingMax](#RatingMax) | Derecelendirme maksimum değeri. |
| [RatingMin](#RatingMin) | Derecelendirme minimum değeri. |
| [RatingRejected](#RatingRejected) | Derecelendirme reddedilen değeri. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Karmaşık tip ad alanını ekler. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Dize özelliğini ekler. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratör döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Belirtilen anahtara sahip değeri kaldır. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Kaynak oluşturulma tarihini ekler. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Kaynak oluşturulma tarihini ekler. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Oluşturucu aracını ayarlar. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Tanımlayıcıyı ayarlar. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Etiketi ayarlar. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Meta verilerin son değiştirilme tarihini ekler. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Meta verilerin son değiştirilme tarihini ekler. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Kaynağın son değiştirilme tarihini ekler. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Kaynağın son değiştirilme tarihini ekler. |
| [setRating(int choise)](#setRating-int-) | Derecelendirmeyi ayarlar. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Değeri ayarlar. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP boolean değerini ayarlar. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP benzersiz tanımlayıcısını ayarlar. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP tip değerini ayarlar. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen anahtara sahip nesneyi alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


XmpBasicPackage sınıfının yeni bir örneğini başlatır.

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


XmpBasicPackage sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | java.lang.String | Önek. |
| namespaceUri | java.lang.String | Namespace URI'si. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Derecelendirme maksimum değeri.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Derecelendirme minimum değeri.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Derecelendirme reddedilen değeri.

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


Dize özelliğini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.String | Dize değeri. |

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


Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Değeri tanımlayan anahtar. Değer: Nesne. |

**Returns:**
java.lang.Object - Belirtilen anahtara sahip nesneyi döndürür.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Kaynak oluşturulma tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createdDate | java.lang.String | Oluşturulma tarihi. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Kaynak oluşturulma tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Oluşturulma tarihi. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Oluşturucu aracını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| creatorTool | java.lang.String | Aracın adı. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Tanımlayıcıyı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idenfifier | java.lang.String[] | Tanımlayıcı. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Etiketi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Etiket. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Meta verilerin son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadataDate | java.lang.String | Meta veri tarihi. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Meta verilerin son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Meta veri tarihi. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Kaynağın son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| modifiedDate | java.lang.String | Son değiştirilme tarihi. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Kaynağın son değiştirilme tarihini ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Son değiştirilme tarihi. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Derecelendirmeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| choise | int | -1'den 5'e kadar |

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


Belirtilen anahtara sahip nesneyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Değeri tanımlayan anahtar. Değer: Nesne. |
| değer | java.lang.Object |  |

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

