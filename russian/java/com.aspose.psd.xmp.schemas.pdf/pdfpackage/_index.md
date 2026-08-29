---
title: "PdfPackage"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет пространство имён Adobe Pdf."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.xmp.schemas.pdf/pdfpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public final class PdfPackage extends XmpPackage
```

Представляет пространство имён Adobe Pdf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfPackage()](#PdfPackage--) | Инициализирует новый экземпляр класса  PdfPackage  . |
## Методы

| Метод | Описание |
| --- | --- |
| [addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)](#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-) | Добавляет пространство имён сложного типа. |
| [addValue(String key, String value)](#addValue-java.lang.String-java.lang.String-) | Добавляет строковое свойство. |
| [assign_internalized(XmpPackage xmpPackege)](#assign-internalized-com.aspose.psd.xmp.XmpPackage-) | Назначает указанный XMP‑пакет текущему. |
| [clear()](#clear--) | Очищает этот экземпляр. |
| [combinePackage_internalized(XmpPackage other)](#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-) | Объединяет пакет. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Определяет, содержит ли указанный ключ ключ. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getKeys()](#getKeys--) | Получает ключи в пакете XMP. |
| [getNamespaceUri()](#getNamespaceUri--) | Получает URI пространства имён. |
| [getPrefix()](#getPrefix--) | Получает префикс. |
| [getXmlNamespace()](#getXmlNamespace--) | Получает пространство имён XML. |
| [getXmlValue()](#getXmlValue--) | Преобразует значение XMP в представление XML. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Получает или задаёт  Object  с указанным ключом. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Удаляет значение с указанным ключом. |
| [setKeywords(String keywords)](#setKeywords-java.lang.String-) | Устанавливает ключевые слова. |
| [setPdfVersion(String version)](#setPdfVersion-java.lang.String-) | Устанавливает версию Pdf. |
| [setProducer(String producer)](#setProducer-java.lang.String-) | Устанавливает имя инструмента, создавшего Pdf. |
| [setTrapped(boolean isTrapped)](#setTrapped-boolean-) | Устанавливает trapped. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Устанавливает значение. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Устанавливает логическое значение XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Устанавливает уникальный идентификатор XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Устанавливает типовое значение XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Устанавливает  Object  с указанным ключом. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPackage() {#PdfPackage--}
```
public PdfPackage()
```


Инициализирует новый экземпляр класса  PdfPackage  .

### addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri) {#addComplexTypeNamespace-internalized-java.lang.String-java.lang.String-}
```
public void addComplexTypeNamespace_internalized(String typePrefix, String typeNamespaceUri)
```


Добавляет пространство имён сложного типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typePrefix | java.lang.String | Префикс типа. |
| typeNamespaceUri | java.lang.String | URI пространства имён типа. |

### addValue(String key, String value) {#addValue-java.lang.String-java.lang.String-}
```
public void addValue(String key, String value)
```


Добавляет строковое свойство.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного с добавленным значением. |
| значение | java.lang.String | Строковое значение. |

### assign_internalized(XmpPackage xmpPackege) {#assign-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void assign_internalized(XmpPackage xmpPackege)
```


Назначает указанный XMP‑пакет текущему.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| xmpPackege | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Пакет XMP. |

### clear() {#clear--}
```
public void clear()
```


Очищает этот экземпляр.

### combinePackage_internalized(XmpPackage other) {#combinePackage-internalized-com.aspose.psd.xmp.XmpPackage-}
```
public void combinePackage_internalized(XmpPackage other)
```


Объединяет пакет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Другой пакет для объединения. |

### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Определяет, содержит ли указанный ключ ключ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ для проверки. |

**Returns:**
boolean - Возвращает true, если указанный ключ содержит ключ.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPackage deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - The cloned object
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKeys() {#getKeys--}
```
public System.Collections.Generic.Dictionary.KeyCollection<String,Object> getKeys()
```


Получает ключи в пакете XMP.

Значение: Ключи в пакете XMP.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary.KeyCollection<java.lang.String,java.lang.Object>
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Получает URI пространства имён.

Значение: URI пространства имён.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает префикс.

Значение: Префикс.

**Returns:**
java.lang.String
### getXmlNamespace() {#getXmlNamespace--}
```
public String getXmlNamespace()
```


Получает пространство имён XML.

Значение: Пространство имён XML.

**Returns:**
java.lang.String
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


Преобразует значение XMP в представление XML.

**Returns:**
java.lang.String - Возвращает значение XMP, преобразованное в представление XML.
### get_Item(String key) {#get-Item-java.lang.String-}
```
public Object get_Item(String key)
```


Получает или задаёт  Object  с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, идентифицирующий значение. |

**Returns:**
java.lang.Object - Возвращает  Object  с указанным ключом.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,Object>> iterator()
```


Возвращает перечислитель, который перебирает коллекцию.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.Object>> - A  T:System.Collections.Generic.IEnumerator1  который может использоваться для перебора коллекции.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(String key) {#remove-java.lang.String-}
```
public boolean remove(String key)
```


Удаляет значение с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, иденфицированного удалённым значением. |

**Returns:**
boolean - Возвращает true, если значение с указанным ключом было удалено.
### setKeywords(String keywords) {#setKeywords-java.lang.String-}
```
public void setKeywords(String keywords)
```


Устанавливает ключевые слова.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| keywords | java.lang.String | Ключевые слова. |

### setPdfVersion(String version) {#setPdfVersion-java.lang.String-}
```
public void setPdfVersion(String version)
```


Устанавливает версию Pdf.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| version | java.lang.String | Версия Pdf, например: 1.0, 1.3 и т.д. |

### setProducer(String producer) {#setProducer-java.lang.String-}
```
public void setProducer(String producer)
```


Устанавливает имя инструмента, создавшего Pdf.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| producer | java.lang.String | Имя производителя. |

### setTrapped(boolean isTrapped) {#setTrapped-boolean-}
```
public void setTrapped(boolean isTrapped)
```


Устанавливает trapped.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isTrapped | boolean | если установлено в  true  документ был trapped. |

### setValue(String key, IXmlValue value) {#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-}
```
public void setValue(String key, IXmlValue value)
```


Устанавливает значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного с добавленным значением. |
| value | [IXmlValue](../../com.aspose.psd.xmp/ixmlvalue) | Значение для добавления. |

### setXmpBoolean(String key, String boolValue) {#setXmpBoolean-java.lang.String-java.lang.String-}
```
public void setXmpBoolean(String key, String boolValue)
```


Устанавливает логическое значение XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного заданным значением. |
| boolValue | java.lang.String | Булево значение. |

### setXmpGuid(String key, String guid) {#setXmpGuid-java.lang.String-java.lang.String-}
```
public void setXmpGuid(String key, String guid)
```


Устанавливает уникальный идентификатор XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного заданным значением GUID. |
| guid | java.lang.String | Уникальный идентификатор. |

### setXmpTypeValue(String key, XmpTypeBase value) {#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-}
```
public void setXmpTypeValue(String key, XmpTypeBase value)
```


Устанавливает типовое значение XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного заданным значением. |
| value | [XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase) | Значение для установки. |

### set_Item(String key, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public void set_Item(String key, Object value)
```


Устанавливает  Object  с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, идентифицирующий значение. |
| значение | java.lang.Object | Значение  Object  . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

