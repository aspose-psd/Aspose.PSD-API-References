---
title: "فئة XmpPacketWrapper"
type: docs
weight: 450
url: /ar/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | ينشئ مثلاً جديداً من الفئة [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) . |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | ينشئ مثلاً جديداً من الفئة [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) . |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | يسترجع تعليمات معالجة الرأس. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | يسترجع بيانات XMP الوصفية. اختياري. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | يسترجع مصفوفة من [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) داخل XMP. |
| packages_count | int | r | يسترجع عدد الحزم داخل بنية XMP. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | يسترجع تعليمات معالجة الذيل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | يضيف الحزمة. |
| clear_packages() | يزيل جميع [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) داخل XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | يحدد ما إذا كانت الحزمة موجودة في غلاف XMP. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | يسترجع الحزمة حسب مساحة الاسم URI. |
| [remove_package(package)](#remove_package_package_4) | يزيل حزمة XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

ينشئ مثلاً جديداً من الفئة [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) .

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

ينشئ مثلاً جديداً من الفئة [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) .

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | رأس XMP لتعليمات المعالجة. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | ذيل XMP لتعليمات المعالجة. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | بيانات XMP الوصفية. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

يضيف الحزمة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | الحزمة. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

يحدد ما إذا كانت الحزمة موجودة في غلاف XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| namespace_uri | string | URI مخطط الحزمة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | يرجع true إذا كانت الحزمة ذات مساحة الاسم المحددة موجودة في غلاف XMP. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

يسترجع الحزمة حسب مساحة الاسم URI.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| namespace_uri | string | معرّف URI لمخطط الحزمة. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | يعيد حزمة XMP للمعرّف URI للمساحة الاسمية المحددة. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

يزيل حزمة XMP.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | الحزمة. |

