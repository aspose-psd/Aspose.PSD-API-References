---
title: "Класс XmpArray"
type: docs
weight: 290
url: /ru/python-net/aspose.psd.xmp/xmparray/
---

**Summary:** Represents Xmp Array in [XmpPackage](/psd/python-net/aspose.psd.xmp/xmppackage/). TODO: Array may contain complex data.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpArray

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XmpArray(type)](#XmpArray_type_1) | Инициализирует новый экземпляр класса [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/). |
| [XmpArray(type, items)](#XmpArray_type_items_2) | Инициализирует новый экземпляр класса [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| values | string | r | Получает массив значений внутри [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_item(item)](#add_item_item_1) | Добавляет новый элемент. |
| [get_xml_value()](#get_xml_value__2) | Преобразует значение XMP в XML-представление. |


### Constructor: XmpArray(type) {#XmpArray_type_1}


```
 XmpArray(type) 
```

Инициализирует новый экземпляр класса [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | Тип массива. |

### Constructor: XmpArray(type, items) {#XmpArray_type_items_2}


```
 XmpArray(type, items) 
```

Инициализирует новый экземпляр класса [XmpArray](/psd/python-net/aspose.psd.xmp/xmparray/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [XmpArrayType](/psd/python-net/aspose.psd.xmp/xmparraytype) | Тип массива. |
| элементы | string | Список элементов. |

### Method: add_item(item) {#add_item_item_1}


```
 add_item(item) 
```

Добавляет новый элемент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| элемент | string | Элемент, который будет добавлен в список элементов. |

### Method: get_xml_value() {#get_xml_value__2}


```
 get_xml_value() 
```

Преобразует значение XMP в XML-представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в XML-представление. |


