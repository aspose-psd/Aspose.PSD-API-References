---
title: "XmpMeta Sınıfı"
type: docs
weight: 410
url: /tr/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Yeni bir [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) sınıf örneği başlatır. |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Yeni bir [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Adobe Xmp araç takımı sürümünü alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Özniteliği ekler. |
| clear_attributes() | Tüm öznitelikleri kaldırır. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Özniteliği alır. |
| [get_xml_value()](#get_xml_value__3) | XMP değerini XML temsiline dönüştürür. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Yeni bir [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) sınıf örneği başlatır.

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Yeni bir [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| toolkit_version | string | Adobe XMP araç takımı sürümü. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Özniteliği ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| öznitelik | string | Öznitelik. |
| değer | string | Değer. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Özniteliği alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| öznitelik | string | Öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Belirtilen öznitelik adı için özniteliği döndürür. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

XMP değerini XML temsiline dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP değerini XML temsiline dönüştürülmüş olarak döndürür. |


