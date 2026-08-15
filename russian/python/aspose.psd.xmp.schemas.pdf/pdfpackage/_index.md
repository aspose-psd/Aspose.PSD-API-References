---
title: "Класс PdfPackage"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Summary:** Represents Adobe Pdf namespace.

**Module:** [aspose.psd.xmp.schemas.pdf](/psd/python-net/aspose.psd.xmp.schemas.pdf/)

**Full Name:** aspose.psd.xmp.schemas.pdf.PdfPackage

**Inheritance:** IXmlValue, XmpPackage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PdfPackage()](#PdfPackage__1) | Инициализирует новый экземпляр класса PdfPackage |
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
| [set_keywords(keywords)](#set_keywords_keywords_5) | Устанавливает ключевые слова. |
| [set_pdf_version(version)](#set_pdf_version_version_6) | Устанавливает версию PDF. |
| [set_producer(producer)](#set_producer_producer_7) | Устанавливает имя инструмента, создавшего Pdf. |
| [set_trapped(is_trapped)](#set_trapped_is_trapped_8) | Устанавливает trapped. |
| [set_value(key, value)](#set_value_key_value_9) | Устанавливает значение. |
| [set_xmp_type_value(key, value)](#set_xmp_type_value_key_value_10) | Устанавливает значение типа XMP. |


### Constructor: PdfPackage() {#PdfPackage__1}


```
 PdfPackage() 
```

Инициализирует новый экземпляр класса PdfPackage

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


### Method: set_keywords(keywords) {#set_keywords_keywords_5}


```
 set_keywords(keywords) 
```

Устанавливает ключевые слова.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ключевые слова | string | Ключевые слова. |

### Method: set_pdf_version(version) {#set_pdf_version_version_6}


```
 set_pdf_version(version) 
```

Устанавливает версию PDF.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| version | string | Версия PDF, например: 1.0, 1.3 и т.д. |

### Method: set_producer(producer) {#set_producer_producer_7}


```
 set_producer(producer) 
```

Устанавливает имя инструмента, создавшего Pdf.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| producer | string | Имя producer. |

### Method: set_trapped(is_trapped) {#set_trapped_is_trapped_8}


```
 set_trapped(is_trapped) 
```

Устанавливает trapped.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| is_trapped | bool | если установлено <c>true</c> документ был trapped. |

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

### Method: set_xmp_type_value(key, value) {#set_xmp_type_value_key_value_10}


```
 set_xmp_type_value(key, value) 
```

Устанавливает значение типа XMP.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | string | Строковое представление ключа, идентифицированного заданным значением. |
| value | [XmpTypeBase](/psd/python-net/aspose.psd.xmp.types/xmptypebase/) | Значение, которое нужно установить. |

