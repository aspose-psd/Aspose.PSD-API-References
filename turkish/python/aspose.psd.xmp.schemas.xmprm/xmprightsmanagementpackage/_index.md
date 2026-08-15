---
title: "XmpRightsManagementPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Yeni bir XmpRightsManagementPackage sınıfının örneğini başlatır |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Sertifikayı ayarlar. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Hak yönetimi içeriği olarak işaretler. |
| [set_owners(owners)](#set_owners_owners_7) | Sahipleri ayarlar. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Kullanım koşullarını ayarlar. |
| [set_value(key, value)](#set_value_key_value_9) | Değeri ayarlar. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Web beyanını ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | XMP tür değerini ayarlar. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Yeni bir XmpRightsManagementPackage sınıfının örneğini başlatır

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Sertifikayı ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sertifika | string | Sertifika. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Hak yönetimi içeriği olarak işaretler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değer | bool | eğer <c>true</c> olarak ayarlanırsa bunun hak yönetimli bir kaynak olduğunu gösterir. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Sahipleri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sahipler | string | Sahipler. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Kullanım koşullarını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Kullanım şartları. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Değeri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Eklenen değerle tanımlanan anahtarın dize temsili. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Eklenecek değer. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Web beyanını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| web_statement_url | string | Web beyanı URL'si. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

XMP tür değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Ayarlanacak değer. |

