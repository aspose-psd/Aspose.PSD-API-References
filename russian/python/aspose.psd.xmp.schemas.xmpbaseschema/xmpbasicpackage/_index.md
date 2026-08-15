---
title: "Класс XmpBasicPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Summary:** Represents XMP basic namespace.

**Module:** [aspose.psd.xmp.schemas.xmpbaseschema](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/)

**Full Name:** aspose.psd.xmp.schemas.xmpbaseschema.XmpBasicPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XmpBasicPackage()](#XmpBasicPackage__1) | Инициализирует новый экземпляр класса [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) . |
| [XmpBasicPackage(prefix, namespace_uri)](#XmpBasicPackage_prefix_namespace_uri_2) | Инициализирует новый экземпляр класса [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| RATING_MAX [static] | int | r | Максимальное значение рейтинга. |
| RATING_MIN [static] | int | r | Минимальное значение рейтинга. |
| RATING_REJECTED [static] | int | r | Отвергнутое значение рейтинга. |
| namespace_uri | string | r | Получает URI пространства имён. |
| префикс | string | r | Получает префикс. |
| xml_namespace | string | r | Получает пространство имён XML. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_value(key, value)](#add_value_key_value_1) | Добавляет строковое свойство. |
| clear() | Очищает этот экземпляр. |
| [contains_key(key)](#contains_key_key_2) | Определяет, содержит ли указанный ключ ключ. |
| [get_xml_value()](#get_xml_value__3) | Преобразует значение XMP в XML-представление. |
| [remove(key)](#remove_key_4) | Удалить значение с указанным ключом. |
| [set_created_date(created_date)](#set_created_date_created_date_5) | Добавляет дату создания ресурса. |
| [set_created_date(created_date)](#set_created_date_created_date_6) | Добавляет дату создания ресурса. |
| [set_creator_tool(creator_tool)](#set_creator_tool_creator_tool_7) | Устанавливает инструмент создателя. |
| [set_identifier(idenfifier)](#set_identifier_idenfifier_8) | Устанавливает идентификатор. |
| [set_label(label)](#set_label_label_9) | Устанавливает метку. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_10) | Добавляет дату последнего изменения метаданных. |
| [set_metadata_date(metadata_date)](#set_metadata_date_metadata_date_11) | Добавляет дату последнего изменения метаданных. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_12) | Добавляет дату последнего изменения ресурса. |
| [set_modify_date(modified_date)](#set_modify_date_modified_date_13) | Добавляет дату последнего изменения ресурса. |
| [set_rating(choise)](#set_rating_choise_14) | Устанавливает рейтинг. |
| [set_value(key, value)](#set_value_key_value_15) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_16) | Устанавливает значение типа XMP. |


### Constructor: XmpBasicPackage() {#XmpBasicPackage__1}


```
 XmpBasicPackage() 
```

Инициализирует новый экземпляр класса [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) .

### Constructor: XmpBasicPackage(prefix, namespace_uri) {#XmpBasicPackage_prefix_namespace_uri_2}


```
 XmpBasicPackage(prefix, namespace_uri) 
```

Инициализирует новый экземпляр класса [XmpBasicPackage](/psd/python-net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| префикс | string | Префикс. |
| namespace_uri | string | URI пространства имён. |

### Method: add_value(key, value) {#add_value_key_value_1}


```
 add_value(key, value) 
```

Добавляет строковое свойство.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного добавленным значением. |
| значение | string | Строковое значение. |

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


### Method: set_created_date(created_date) {#set_created_date_created_date_5}


```
 set_created_date(created_date) 
```

Добавляет дату создания ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| created_date | datetime | Дата создания. |

### Method: set_created_date(created_date) {#set_created_date_created_date_6}


```
 set_created_date(created_date) 
```

Добавляет дату создания ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| created_date | string | Дата создания. |

### Method: set_creator_tool(creator_tool) {#set_creator_tool_creator_tool_7}


```
 set_creator_tool(creator_tool) 
```

Устанавливает инструмент создателя.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| creator_tool | string | Название инструмента. |

### Method: set_identifier(idenfifier) {#set_identifier_idenfifier_8}


```
 set_identifier(idenfifier) 
```

Устанавливает идентификатор.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| idenfifier | string | Идентификатор. |

### Method: set_label(label) {#set_label_label_9}


```
 set_label(label) 
```

Устанавливает метку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| label | string | Метка. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_10}


```
 set_metadata_date(metadata_date) 
```

Добавляет дату последнего изменения метаданных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata_date | datetime | Дата метаданных. |

### Method: set_metadata_date(metadata_date) {#set_metadata_date_metadata_date_11}


```
 set_metadata_date(metadata_date) 
```

Добавляет дату последнего изменения метаданных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| metadata_date | string | Дата метаданных. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_12}


```
 set_modify_date(modified_date) 
```

Добавляет дату последнего изменения ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modified_date | datetime | Дата последнего изменения. |

### Method: set_modify_date(modified_date) {#set_modify_date_modified_date_13}


```
 set_modify_date(modified_date) 
```

Добавляет дату последнего изменения ресурса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modified_date | string | Дата последнего изменения. |

### Method: set_rating(choise) {#set_rating_choise_14}


```
 set_rating(choise) 
```

Устанавливает рейтинг.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| choise | int | От -1 до 5 |

### Method: set_value(key, value) {#set_value_key_value_15}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного добавленным значением. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Значение, к которому нужно добавить. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_16}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного заданным значением. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Значение, которое нужно установить. |

