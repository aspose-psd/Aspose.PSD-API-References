---
title: "XmpDate Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.psd.xmp.types.basic/xmpdate/
---

**Summary:** Represents Date in XMP packet.

**Module:** [aspose.psd.xmp.types.basic](/psd/python-net/aspose.psd.xmp.types.basic/)

**Full Name:** aspose.psd.xmp.types.basic.XmpDate

**Inheritance:** IXmpType, XmpTypeBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpDate(date_string)](#XmpDate_date_string_1) | Yeni bir [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) sınıfı örneği başlatır. |
| [XmpDate(date_time)](#XmpDate_date_time_2) | Yeni bir [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| ISO_8601_FORMAT [statik] | string | r | ISO 8601 (roundtrip) biçim dizesi. |
| biçim | string | r | Geçerli değer için biçim dizesini alır. |
| değer | datetime | r/w | Tarih değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__1) | XMP formatında içerilen dize değerini döndürür. |


### Constructor: XmpDate(date_string) {#XmpDate_date_string_1}


```
 XmpDate(date_string) 
```

Yeni bir [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| date_string | string | Tarihin dize temsili. |

### Constructor: XmpDate(date_time) {#XmpDate_date_time_2}


```
 XmpDate(date_time) 
```

Yeni bir [XmpDate](/psd/python-net/aspose.psd.xmp.types.basic/xmpdate/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| date_time | datetime | ISO RFC 8601 biçimlendirmesinin bir alt kümesi kullanılarak temsil edilen bir tarih‑zaman değeri. |

### Method: get_xmp_representation() {#get_xmp_representation__1}


```
 get_xmp_representation() 
```

XMP formatında içerilen dize değerini döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP formatında içerilen dize değerini döndürür. |


