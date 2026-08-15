---
title: "Класс XmpMeta"
type: docs
weight: 410
url: /ru/python-net/aspose.psd.xmp/xmpmeta/
---

**Summary:** Represents xmpmeta. Optional.<br/>            The purpose of this element is to identify XMP metadata within general XML text that might contain other non-XMP uses of RDF.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpMeta

**Inheritance:** IXmlValue, XmpElementBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XmpMeta()](#XmpMeta__1) | Инициализирует новый экземпляр класса [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
| [XmpMeta(toolkit_version)](#XmpMeta_toolkit_version_2) | Инициализирует новый экземпляр класса [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| adobe_xmp_toolkit | string | r/w | Получает или задаёт версию Adobe Xmp toolkit. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_attribute(attribute, value)](#add_attribute_attribute_value_1) | Добавляет атрибут. |
| clear_attributes() | Удаляет все атрибуты. |
| [get_attribute(attribute)](#get_attribute_attribute_2) | Получает атрибут. |
| [get_xml_value()](#get_xml_value__3) | Преобразует значение XMP в XML-представление. |


### Constructor: XmpMeta() {#XmpMeta__1}


```
 XmpMeta() 
```

Инициализирует новый экземпляр класса [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

### Constructor: XmpMeta(toolkit_version) {#XmpMeta_toolkit_version_2}


```
 XmpMeta(toolkit_version) 
```

Инициализирует новый экземпляр класса [XmpMeta](/psd/python-net/aspose.psd.xmp/xmpmeta/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| toolkit_version | string | Версия набора инструментов Adobe XMP. |

### Method: add_attribute(attribute, value) {#add_attribute_attribute_value_1}


```
 add_attribute(attribute, value) 
```

Добавляет атрибут.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| атрибут | string | Атрибут. |
| значение | string | Значение. |

### Method: get_attribute(attribute) {#get_attribute_attribute_2}


```
 get_attribute(attribute) 
```

Получает атрибут.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| атрибут | string | Атрибут. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает атрибут для указанного имени атрибута. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Преобразует значение XMP в XML-представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в XML-представление. |


