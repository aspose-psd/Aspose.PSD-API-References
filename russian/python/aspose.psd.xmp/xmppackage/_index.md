---
title: "Класс XmpPackage"
type: docs
weight: 430
url: /ru/python-net/aspose.psd.xmp/xmppackage/
---

**Summary:** Defines the XmpPackage class that represents base abstraction for XMP package.

**Module:** [aspose.psd.xmp](/psd/python-net/aspose.psd.xmp/)

**Full Name:** aspose.psd.xmp.XmpPackage

**Inheritance:** IXmlValue

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| namespace_uri | string | r | Получает URI пространства имён. |
| префикс | string | r | Получает префикс. |
| xml_namespace | string | r | Получает пространство имён XML. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Добавляет значение. |
| clear() | Очищает этот экземпляр. |
| [contains_key(key)](#contains_key_key_2) | Определяет, содержит ли указанный ключ ключ. |
| [get_xml_value()](#get_xml_value__3) | Преобразует значение XMP в XML-представление. |
| [remove(key)](#remove_key_4) | Удалить значение с указанным ключом. |
| [set_value(key, value)](#set_value_key_value_5) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_6) | Устанавливает значение типа XMP. |


### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Добавляет значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного добавленным значением. |
| значение | string | Значение, к которому нужно добавить. |

### Method: contains_key(key) {#contains_key_key_2}


```
 contains_key(key) 
```

Определяет, содержит ли указанный ключ ключ.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Ключ для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Возвращает true, если указанный ключ содержит ключ. |


### Method: get_xml_value() {#get_xml_value__3}


```
 get_xml_value() 
```

Преобразует значение XMP в XML-представление.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает значение XMP, преобразованное в XML-представление. |


### Method: remove(key) {#remove_key_4}


```
 remove(key) 
```

Удалить значение с указанным ключом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного удалённым значением. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Возвращает true, если значение с указанным ключом было удалено. |


### Method: set_value(key, value) {#set_value_key_value_5}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного добавленным значением. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Значение, к которому нужно добавить. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_6}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного заданным значением. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Значение, которое нужно установить. |

