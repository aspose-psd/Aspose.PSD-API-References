---
title: "XmpMediaManagementPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | XmpMediaManagementPackage sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Ad alanı URI'sını alır. |
| önek | string | r | Öneki alır. |
| xml_namespace | string | r | XML ad alanını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Dize özelliği ekler. |
| clear() | Bu örneği temizler. |
| [contains_key(key)](#contains_key_key_2) | Belirtilen anahtarın anahtar içerip içermediğini belirler. |
| [get_xml_value()](#get_xml_value__3) | XMP değerini XML temsiline dönüştürür. |
| [remove(key)](#remove_key_4) | Belirtilen anahtara sahip değeri kaldır. |
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Türetilen kaynağı ayarlar. |
| [set_document_id(guid)](#set_document_id_guid_6) | Belge tanımlayıcısını ayarlar. |
| [set_document_id(guid)](#set_document_id_guid_7) | Belge tanımlayıcısını ayarlar. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Örnek kimliğini ayarlar. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Örnek kimliğini ayarlar. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Orijinal belge kimliğini ayarlar. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Orijinal belge kimliğini ayarlar. |
| [set_value(key, value)](#set_value_key_value_12) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | XMP tür değerini ayarlar. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

XmpMediaManagementPackage sınıfının yeni bir örneğini başlatır

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Dize özelliği ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | string | Dize değeri. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Belirtilen anahtarın anahtar içerip içermediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Kontrol edilecek anahtar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen anahtar anahtar içeriyorsa true döndürür. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP değerini XML temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML temsiline dönüştürülmüş olarak döndürür. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Belirtilen anahtara sahip değeri kaldır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Kaldırılan değerle tanımlanan anahtarın dize temsili. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Belirtilen anahtara sahip değer kaldırıldıysa true döndürür. |


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Türetilen kaynağı ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | Kaynak referansı. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Belge tanımlayıcısını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | Guid | Benzersiz tanımlayıcı. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Belge tanımlayıcısını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Benzersiz tanımlayıcı. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Örnek kimliğini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | Guid | Benzersiz tanımlayıcı. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Örnek kimliğini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Benzersiz tanımlayıcı. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Orijinal belge kimliğini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | Guid | Benzersiz tanımlayıcı. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Orijinal belge kimliğini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| guid | string | Benzersiz tanımlayıcı. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

XMP tür değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Ayarlanacak değer. |

