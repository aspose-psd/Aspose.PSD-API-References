---
title: "Класс XmpMediaManagementPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.xmp.schemas.xmpmm/xmpmediamanagementpackage/
---

**Summary:** Represents XMP Media Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmpmm](/psd/python-net/aspose.psd.xmp.schemas.xmpmm/)

**Full Name:** aspose.psd.xmp.schemas.xmpmm.XmpMediaManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XmpMediaManagementPackage()](#XmpMediaManagementPackage__1) | Инициализирует новый экземпляр класса XmpMediaManagementPackage |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
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
| [set_derived_from(resource_ref)](#set_derived_from_resource_ref_5) | Устанавливает значение derived from. |
| [set_document_id(guid)](#set_document_id_guid_6) | Устанавливает идентификатор документа. |
| [set_document_id(guid)](#set_document_id_guid_7) | Устанавливает идентификатор документа. |
| [set_instance_id(guid)](#set_instance_id_guid_8) | Устанавливает идентификатор экземпляра. |
| [set_instance_id(guid)](#set_instance_id_guid_9) | Устанавливает идентификатор экземпляра. |
| [set_original_document_id(guid)](#set_original_document_id_guid_10) | Устанавливает идентификатор оригинального документа. |
| [set_original_document_id(guid)](#set_original_document_id_guid_11) | Устанавливает идентификатор оригинального документа. |
| [set_value(key, value)](#set_value_key_value_12) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_13) | Устанавливает значение типа XMP. |


### Constructor: XmpMediaManagementPackage() {#XmpMediaManagementPackage__1}


```
 XmpMediaManagementPackage() 
```

Инициализирует новый экземпляр класса XmpMediaManagementPackage

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


### Method: set_derived_from(resource_ref) {#set_derived_from_resource_ref_5}


```
 set_derived_from(resource_ref) 
```

Устанавливает значение derived from.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| resource_ref | [ResourceRef](/psd/python-net/aspose.psd.xmp.types.complex.resourceref/resourceref/) | Ссылка на ресурс. |

### Method: set_document_id(guid) {#set_document_id_guid_6}


```
 set_document_id(guid) 
```

Устанавливает идентификатор документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | Guid | Уникальный идентификатор. |

### Method: set_document_id(guid) {#set_document_id_guid_7}


```
 set_document_id(guid) 
```

Устанавливает идентификатор документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | Уникальный идентификатор. |

### Method: set_instance_id(guid) {#set_instance_id_guid_8}


```
 set_instance_id(guid) 
```

Устанавливает идентификатор экземпляра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | Guid | Уникальный идентификатор. |

### Method: set_instance_id(guid) {#set_instance_id_guid_9}


```
 set_instance_id(guid) 
```

Устанавливает идентификатор экземпляра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | Уникальный идентификатор. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_10}


```
 set_original_document_id(guid) 
```

Устанавливает идентификатор оригинального документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | Guid | Уникальный идентификатор. |

### Method: set_original_document_id(guid) {#set_original_document_id_guid_11}


```
 set_original_document_id(guid) 
```

Устанавливает идентификатор оригинального документа.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| guid | string | Уникальный идентификатор. |

### Method: set_value(key, value) {#set_value_key_value_12}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного добавленным значением. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Значение, к которому нужно добавить. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_13}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного заданным значением. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Значение, которое нужно установить. |

