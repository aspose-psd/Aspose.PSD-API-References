---
title: "Класс XmpRightsManagementPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.xmp.schemas.xmprm/xmprightsmanagementpackage/
---

**Summary:** Represents XMP Rights Management namespace.

**Module:** [aspose.psd.xmp.schemas.xmprm](/psd/python-net/aspose.psd.xmp.schemas.xmprm/)

**Full Name:** aspose.psd.xmp.schemas.xmprm.XmpRightsManagementPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XmpRightsManagementPackage()](#XmpRightsManagementPackage__1) | Инициализирует новый экземпляр класса XmpRightsManagementPackage |
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
| [set_certificate(certificate)](#set_certificate_certificate_5) | Устанавливает сертификат. |
| [set_marked_as_right_management(value)](#set_marked_as_right_management_value_6) | Помечает как контент с управлением правами |
| [set_owners(owners)](#set_owners_owners_7) | Устанавливает владельцев. |
| [set_usage_terms(usage_terms)](#set_usage_terms_usage_terms_8) | Устанавливает условия использования. |
| [set_value(key, value)](#set_value_key_value_9) | Устанавливает значение. |
| [set_web_statement(web_statement_url)](#set_web_statement_web_statement_url_10) | Устанавливает веб‑заявление. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_11) | Устанавливает значение типа XMP. |


### Constructor: XmpRightsManagementPackage() {#XmpRightsManagementPackage__1}


```
 XmpRightsManagementPackage() 
```

Инициализирует новый экземпляр класса XmpRightsManagementPackage

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


### Method: set_certificate(certificate) {#set_certificate_certificate_5}


```
 set_certificate(certificate) 
```

Устанавливает сертификат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| сертификат | string | Сертификат. |

### Method: set_marked_as_right_management(value) {#set_marked_as_right_management_value_6}


```
 set_marked_as_right_management(value) 
```

Помечает как контент с управлением правами

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| значение | bool | если установлено в <c>true</c>, что это ресурс с управлением правами. |

### Method: set_owners(owners) {#set_owners_owners_7}


```
 set_owners(owners) 
```

Устанавливает владельцев.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| владельцы | string | Владельцы. |

### Method: set_usage_terms(usage_terms) {#set_usage_terms_usage_terms_8}


```
 set_usage_terms(usage_terms) 
```

Устанавливает условия использования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| usage_terms | [LangAlt](/psd/python-net/aspose.psd.xmp/langalt) | Условия использования. |

### Method: set_value(key, value) {#set_value_key_value_9}


```
 set_value(key, value) 
```

Устанавливает значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного добавленным значением. |
| value | [IXmlValue](/psd/python-net/aspose.psd.xmp/ixmlvalue) | Значение, к которому нужно добавить. |

### Method: set_web_statement(web_statement_url) {#set_web_statement_web_statement_url_10}


```
 set_web_statement(web_statement_url) 
```

Устанавливает веб‑заявление.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| web_statement_url | string | URL веб‑заявления. |

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_11}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного заданным значением. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Значение, которое нужно установить. |

