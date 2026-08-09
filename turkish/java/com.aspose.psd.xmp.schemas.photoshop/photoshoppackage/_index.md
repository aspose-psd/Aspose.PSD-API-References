---
title: "PhotoshopPackage"
second_title: "Java için Aspose.PSD API Referansı"
description: "Adobe Photoshop ad alanını temsil eder."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.xmp.schemas.photoshop/photoshoppackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PhotoshopPackage extends XmpPackage
```

Adobe Photoshop ad alanını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PhotoshopPackage()](#PhotoshopPackage--) | PhotoshopPackage sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [UrgencyMax](#UrgencyMax) | Aciliyet maksimum değeri. |
| [UrgencyMin](#UrgencyMin) | Aciliyet minimum değeri. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Belirtilen anahtara sahip Object'i alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratör döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Belirtilen anahtara sahip değeri kaldır. |
| [setAuthorsPosition(String authorsPosition)](#setAuthorsPosition-java.lang.String-) | Yazarın konumunu ayarlar. |
| [setCaptionWriter(String captionWriter)](#setCaptionWriter-java.lang.String-) | Altyazı yazarını ayarlar. |
| [setCategory(String category)](#setCategory-java.lang.String-) | Kategoriyi ayarlar. |
| [setCity(String city)](#setCity-java.lang.String-) | Şehri ayarlar. |
| [setColorMode(byte colorMode)](#setColorMode-byte-) | Renk modunu ayarlar. |
| [setCountry(String country)](#setCountry-java.lang.String-) | Ülkeyi ayarlar. |
| [setCreatedDate(Date createdDate)](#setCreatedDate-java.util.Date-) | Oluşturulma tarihini ayarlar. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setCredit(String credit)](#setCredit-java.lang.String-) | Krediyi ayarlar. |
| [setDocumentAncestors(String[] ancestors)](#setDocumentAncestors-java.lang.String---) | Belge atalarını ayarlar. |
| [setHeadline(String headline)](#setHeadline-java.lang.String-) | Manşeti ayarlar. |
| [setHistory(String history)](#setHistory-java.lang.String-) | Geçmişi ayarlar. |
| [setIccProfile(String iccProfile)](#setIccProfile-java.lang.String-) | ICC profilini ayarlar. |
| [setInstructions(String instructions)](#setInstructions-java.lang.String-) | Talimatları ayarlar. |
| [setSource(String source)](#setSource-java.lang.String-) | Kaynağı ayarlar. |
| [setState(String state)](#setState-java.lang.String-) | Durumu ayarlar. |
| [setSupplementalCategories(String[] supplementalCategories)](#setSupplementalCategories-java.lang.String---) | Ek kategorileri ayarlar. |
| [setTransmissionReference(String transmissionReference)](#setTransmissionReference-java.lang.String-) | İletim referansını ayarlar. |
| [setUrgency(int urgency)](#setUrgency-int-) | Aciliyeti ayarlar. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Değeri ayarlar. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | XMP boolean değerini ayarlar. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | XMP benzersiz tanımlayıcısını ayarlar. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | XMP tip değerini ayarlar. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Belirtilen anahtara sahip  Object  ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhotoshopPackage() {#PhotoshopPackage--}
```
public PhotoshopPackage()
```


PhotoshopPackage sınıfının yeni bir örneğini başlatır.

### UrgencyMax {#UrgencyMax}
```
public static final int UrgencyMax
```


Aciliyet maksimum değeri.

### UrgencyMin {#UrgencyMin}
```
public static final int UrgencyMin
```


Aciliyet minimum değeri.

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
### setAuthorsPosition(String authorsPosition) {#setAuthorsPosition-java.lang.String-}
```
public void setAuthorsPosition(String authorsPosition)
```


Yazarın konumunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| authorsPosition | java.lang.String | Yazarların konumu. |

### setCaptionWriter(String captionWriter) {#setCaptionWriter-java.lang.String-}
```
public void setCaptionWriter(String captionWriter)
```


Altyazı yazarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| captionWriter | java.lang.String | Altyazı yazarı. |

### setCategory(String category) {#setCategory-java.lang.String-}
```
public void setCategory(String category)
```


Kategoriyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| category | java.lang.String | Kategori. |

### setCity(String city) {#setCity-java.lang.String-}
```
public void setCity(String city)
```


Şehri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| city | java.lang.String | Şehir adı. |

### setColorMode(byte colorMode) {#setColorMode-byte-}
```
public void setColorMode(byte colorMode)
```


Renk modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| colorMode | byte | Renk modu. |

### setCountry(String country) {#setCountry-java.lang.String-}
```
public void setCountry(String country)
```


Ülkeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| country | java.lang.String | Ülke. |

### setCreatedDate(Date createdDate) {#setCreatedDate-java.util.Date-}
```
public void setCreatedDate(Date createdDate)
```


Oluşturulma tarihini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createdDate | java.util.Date | Oluşturulma tarihi. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime |  |

### setCredit(String credit) {#setCredit-java.lang.String-}
```
public void setCredit(String credit)
```


Krediyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kredi | java.lang.String | Bu kredi. |

### setDocumentAncestors(String[] ancestors) {#setDocumentAncestors-java.lang.String---}
```
public void setDocumentAncestors(String[] ancestors)
```


Belge atalarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| atalar | java.lang.String[] | Bu atalar. |

### setHeadline(String headline) {#setHeadline-java.lang.String-}
```
public void setHeadline(String headline)
```


Manşeti ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| başlık | java.lang.String | Bu başlık. |

### setHistory(String history) {#setHistory-java.lang.String-}
```
public void setHistory(String history)
```


Geçmişi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geçmiş | java.lang.String | Bu geçmiş. |

### setIccProfile(String iccProfile) {#setIccProfile-java.lang.String-}
```
public void setIccProfile(String iccProfile)
```


ICC profilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| iccProfile | java.lang.String | Bu icc profili. |

### setInstructions(String instructions) {#setInstructions-java.lang.String-}
```
public void setInstructions(String instructions)
```


Talimatları ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| talimatlar | java.lang.String | Bu talimatlar. |

### setSource(String source) {#setSource-java.lang.String-}
```
public void setSource(String source)
```


Kaynağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kaynak | java.lang.String | Bu kaynak. |

### setState(String state) {#setState-java.lang.String-}
```
public void setState(String state)
```


Durumu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| durum | java.lang.String | Bu durum. |

### setSupplementalCategories(String[] supplementalCategories) {#setSupplementalCategories-java.lang.String---}
```
public void setSupplementalCategories(String[] supplementalCategories)
```


Ek kategorileri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| supplementalCategories | java.lang.String[] | Bu tamamlayıcı kategoriler. |

### setTransmissionReference(String transmissionReference) {#setTransmissionReference-java.lang.String-}
```
public void setTransmissionReference(String transmissionReference)
```


İletim referansını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| transmissionReference | java.lang.String | Bu iletim referansı. |

### setUrgency(int urgency) {#setUrgency-int-}
```
public void setUrgency(int urgency)
```


Aciliyeti ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | aciliyet | int | Bu aciliyet. |

Aciliyet 1'den 8'e kadar bir aralıkta olmalıdır. |

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

