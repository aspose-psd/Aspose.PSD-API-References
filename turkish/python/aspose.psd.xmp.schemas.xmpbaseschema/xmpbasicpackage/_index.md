---
title: "XmpBasicPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Yeni bir [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının örneğini başlatır. |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Yeni bir [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Maksimum puan değeri. |
| RATING_MIN [static] | int | r | Minimum puan değeri. |
| RATING_REJECTED [static] | int | r | Reddedilen puan değeri. |
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
| [set_created_date(created_date)](#set_created_date_created_date_5) | Kaynak oluşturulma tarihini ekler. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Kaynak oluşturulma tarihini ekler. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Oluşturucu aracı ayarlar. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Tanımlayıcıyı ayarlar. |
| [set_label(label)](#set_label_label_9) | Etiketi ayarlar. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Meta verinin son değiştirilme tarihini ekler. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Meta verinin son değiştirilme tarihini ekler. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Kaynağın son değiştirilme tarihini ekler. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Kaynağın son değiştirilme tarihini ekler. |
| [set_rating(choise)](#set_rating_choise_14) | Derecelendirmeyi ayarlar. |
| [set_value(key, value)](#set_value_key_value_15) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | XMP tür değerini ayarlar. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Yeni bir [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının örneğini başlatır.

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Yeni bir [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) sınıfının örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| önek | string | Önek. |
| namespace_uri | string | Ad alanı URI'si. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Kaynak oluşturulma tarihini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| created_date | datetime | Oluşturulma tarihi. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Kaynak oluşturulma tarihini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| created_date | string | Oluşturulma tarihi. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Oluşturucu aracı ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| creator_tool | string | Araç adı. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Tanımlayıcıyı ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| idenfifier | string | Bu idenfifier. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Etiketi ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| label | string | Bu label. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Meta verinin son değiştirilme tarihini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| metadata_date | datetime | Meta veri tarihi. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Meta verinin son değiştirilme tarihini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| metadata_date | string | Meta veri tarihi. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Kaynağın son değiştirilme tarihini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| modified_date | datetime | Son değiştirilme tarihi. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Kaynağın son değiştirilme tarihini ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| modified_date | string | Son değiştirilme tarihi. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Derecelendirmeyi ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| choise | int | -1'den 5'e kadar |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

XMP tür değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Ayarlanacak değer. |

