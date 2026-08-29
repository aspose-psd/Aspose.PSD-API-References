---
title: "XmpPackage Sınıfı"
type: docs
weight: 430
url: /tr/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Ad alanı URI'sını alır. |
| önek | string | r | Öneki alır. |
| xml_namespace | string | r | XML ad alanını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Değeri ekler. |
| clear() | Bu örneği temizler. |
| [contains_key(key)](#contains_key_key_2) | Belirtilen anahtarın anahtar içerip içermediğini belirler. |
| [get_xml_value()](#get_xml_value__3) | XMP değerini XML temsiline dönüştürür. |
| [remove(key)](#remove_key_4) | Belirtilen anahtara sahip değeri kaldır. |
| [set_value(key, value)](#set_value_key_value_5) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | XMP tür değerini ayarlar. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Değeri ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | string | Eklenecek değer. |

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


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Eklenecek değer. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

XMP tür değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Ayarlanacak değer. |

