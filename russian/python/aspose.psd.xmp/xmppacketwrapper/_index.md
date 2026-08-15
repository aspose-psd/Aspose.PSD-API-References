---
title: "Класс XmpPacketWrapper"
type: docs
weight: 450
url: /ru/python-net/aspose.psd.xmp/xmppacketwrapper/
---

**Summary:** Contains serialized xmp package including header and trailer.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPacketWrapper

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XmpPacketWrapper()](#XmpPacketWrapper__1) | Инициализирует новый экземпляр класса [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
| [XmpPacketWrapper(header, trailer, xmp_meta)](#XmpPacketWrapper_header_trailer_xmp_meta_2) | Инициализирует новый экземпляр класса [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| header_pi | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | r | Получает инструкцию обработки заголовка. |
| meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | r/w | Получает метаданные XMP. Необязательно. |
| packages | [XmpPackage[]](/psd/python-net/aspose.psd.xmp/xmppackage) | r | Получает массив [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) внутри XMP. |
| packages_count | int | r | Получает количество пакетов внутри структуры XMP. |
| trailer_pi | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | r | Получает инструкцию обработки трейлера. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_package(package)](#add_package_package_1) | Добавляет пакет. |
| clear_packages() | Удаляет все [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/) внутри XMP. |
| [contains_package(namespace_uri)](#contains_package_namespace_uri_2) | Определяет, существует ли пакет в XMP-обёртке. |
| [get_package(namespace_uri)](#get_package_namespace_uri_3) | Получает пакет по URI пространства имён. |
| [remove_package(package)](#remove_package_package_4) | Удаляет пакет XMP. |


### Constructor: XmpPacketWrapper() {#XmpPacketWrapper__1}


```
 XmpPacketWrapper() 
```

Инициализирует новый экземпляр класса [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

### Constructor: XmpPacketWrapper(header, trailer, xmp_meta) {#XmpPacketWrapper_header_trailer_xmp_meta_2}


```
 XmpPacketWrapper(header, trailer, xmp_meta) 
```

Инициализирует новый экземпляр класса [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| header | [XmpHeaderPi](/psd/python-net/aspose.psd.xmp/xmpheaderpi) | Заголовок XMP инструкции обработки. |
| trailer | [XmpTrailerPi](/psd/python-net/aspose.psd.xmp/xmptrailerpi) | Трейлер XMP инструкции обработки. |
| xmp_meta | [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta) | Метаданные XMP. |

### Method: add_package(package) {#add_package_package_1}


```
 add_package(package) 
```

Добавляет пакет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Пакет. |

### Method: contains_package(namespace_uri) {#contains_package_namespace_uri_2}


```
 contains_package(namespace_uri) 
```

Определяет, существует ли пакет в XMP-обёртке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| namespace_uri | string | URI схемы пакета. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Возвращает true, если пакет с указанным URI пространства имён существует в XMP-обёртке. |


### Method: get_package(namespace_uri) {#get_package_namespace_uri_3}


```
 get_package(namespace_uri) 
```

Получает пакет по URI пространства имён.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| namespace_uri | string | URI схемы пакета. |

**Returns**

| Тип | Описание |
| :- | :- |
| [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Возвращает XMP‑пакет для указанного URI пространства имён. |


### Method: remove_package(package) {#remove_package_package_4}


```
 remove_package(package) 
```

Удаляет пакет XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| package | [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage) | Пакет. |

