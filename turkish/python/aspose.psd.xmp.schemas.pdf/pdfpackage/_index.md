---
title: "PdfPackage Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | PdfPackage sınıfının yeni bir örneğini başlatır. |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | Anahtar kelimeleri ayarlar. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | PDF sürümünü ayarlar. |
| [set_producer(producer)](#set_producer_producer_7) | Pdf'i oluşturan aracın adını ayarlar. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Trapped değerini ayarlar. |
| [set_value(key, value)](#set_value_key_value_9) | Değeri ayarlar. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | XMP tür değerini ayarlar. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

PdfPackage sınıfının yeni bir örneğini başlatır.

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Anahtar kelimeleri ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| anahtar kelimeler | string | Anahtar kelimeler. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

PDF sürümünü ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| version | string | Pdf sürümü, örneğin: 1.0, 1.3 vb. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Pdf'i oluşturan aracın adını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| üretici | string | Üretici adı. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Trapped değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| is_trapped | bool | eğer <c>true</c> olarak ayarlanırsa belge trapped edilmiştir. |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

XMP tür değerini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| key | string | Ayarlanan değerle tanımlanan anahtarın dize temsili. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Ayarlanacak değer. |

