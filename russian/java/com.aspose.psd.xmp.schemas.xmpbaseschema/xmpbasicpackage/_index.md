---
title: "XmpBasicPackage"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет базовое пространство имён XMP."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpPackage](../../com.aspose.psd.xmp/xmppackage)
```
public class XmpBasicPackage extends XmpPackage
```

Представляет базовое пространство имён XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpBasicPackage()](#XmpBasicPackage--) | Инициализирует новый экземпляр класса  XmpBasicPackage  . |
| [XmpBasicPackage(String prefix, String namespaceUri)](#XmpBasicPackage-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса  XmpBasicPackage  . |
## Поля

| Поле | Описание |
| --- | --- |
| [RatingMax](#RatingMax) | Максимальное значение рейтинга. |
| [RatingMin](#RatingMin) | Минимальное значение рейтинга. |
| [RatingRejected](#RatingRejected) | Отклонённое значение рейтинга. |
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
| [get_Item(String key)](#get-Item-java.lang.String-) | Получает или задаёт объект с указанным ключом. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает коллекцию. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(String key)](#remove-java.lang.String-) | Удаляет значение с указанным ключом. |
| [setCreatedDate(String createdDate)](#setCreatedDate-java.lang.String-) | Добавляет дату создания ресурса. |
| [setCreatedDate_internalized(System.DateTime createdDate)](#setCreatedDate-internalized-com.aspose.ms.System.DateTime-) | Добавляет дату создания ресурса. |
| [setCreatorTool(String creatorTool)](#setCreatorTool-java.lang.String-) | Устанавливает инструмент создателя. |
| [setIdentifier(String[] idenfifier)](#setIdentifier-java.lang.String---) | Устанавливает идентификатор. |
| [setLabel(String label)](#setLabel-java.lang.String-) | Устанавливает метку. |
| [setMetadataDate(String metadataDate)](#setMetadataDate-java.lang.String-) | Добавляет дату последнего изменения метаданных. |
| [setMetadataDate_internalized(System.DateTime metadataDate)](#setMetadataDate-internalized-com.aspose.ms.System.DateTime-) | Добавляет дату последнего изменения метаданных. |
| [setModifyDate(String modifiedDate)](#setModifyDate-java.lang.String-) | Добавляет дату последнего изменения ресурса. |
| [setModifyDate_internalized(System.DateTime modifiedDate)](#setModifyDate-internalized-com.aspose.ms.System.DateTime-) | Добавляет дату последнего изменения ресурса. |
| [setRating(int choise)](#setRating-int-) | Устанавливает рейтинг. |
| [setValue(String key, IXmlValue value)](#setValue-java.lang.String-com.aspose.psd.xmp.IXmlValue-) | Устанавливает значение. |
| [setXmpBoolean(String key, String boolValue)](#setXmpBoolean-java.lang.String-java.lang.String-) | Устанавливает логическое значение XMP. |
| [setXmpGuid(String key, String guid)](#setXmpGuid-java.lang.String-java.lang.String-) | Устанавливает уникальный идентификатор XMP. |
| [setXmpTypeValue(String key, XmpTypeBase value)](#setXmpTypeValue-java.lang.String-com.aspose.psd.xmp.types.XmpTypeBase-) | Устанавливает типовое значение XMP. |
| [set_Item(String key, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Получает или задаёт объект с указанным ключом. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpBasicPackage() {#XmpBasicPackage--}
```
public XmpBasicPackage()
```


Инициализирует новый экземпляр класса  XmpBasicPackage  .

### XmpBasicPackage(String prefix, String namespaceUri) {#XmpBasicPackage-java.lang.String-java.lang.String-}
```
public XmpBasicPackage(String prefix, String namespaceUri)
```


Инициализирует новый экземпляр класса  XmpBasicPackage  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| префикс | java.lang.String | Префикс. |
| namespaceUri | java.lang.String | URI пространства имён. |

### RatingMax {#RatingMax}
```
public static final int RatingMax
```


Максимальное значение рейтинга.

### RatingMin {#RatingMin}
```
public static final int RatingMin
```


Минимальное значение рейтинга.

### RatingRejected {#RatingRejected}
```
public static final int RatingRejected
```


Отклонённое значение рейтинга.

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


Получает или задаёт объект с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, идентифицирующий значение. Значение: Объект. |

**Returns:**
java.lang.Object — возвращает объект с указанным ключом.
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
### setCreatedDate(String createdDate) {#setCreatedDate-java.lang.String-}
```
public void setCreatedDate(String createdDate)
```


Добавляет дату создания ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createdDate | java.lang.String | Дата создания. |

### setCreatedDate_internalized(System.DateTime createdDate) {#setCreatedDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setCreatedDate_internalized(System.DateTime createdDate)
```


Добавляет дату создания ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| createdDate | com.aspose.ms.System.DateTime | Дата создания. |

### setCreatorTool(String creatorTool) {#setCreatorTool-java.lang.String-}
```
public void setCreatorTool(String creatorTool)
```


Устанавливает инструмент создателя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| creatorTool | java.lang.String | Название инструмента. |

### setIdentifier(String[] idenfifier) {#setIdentifier-java.lang.String---}
```
public void setIdentifier(String[] idenfifier)
```


Устанавливает идентификатор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| idenfifier | java.lang.String[] | Идентификатор idenfifier. |

### setLabel(String label) {#setLabel-java.lang.String-}
```
public void setLabel(String label)
```


Устанавливает метку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| label | java.lang.String | Метка label. |

### setMetadataDate(String metadataDate) {#setMetadataDate-java.lang.String-}
```
public void setMetadataDate(String metadataDate)
```


Добавляет дату последнего изменения метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadataDate | java.lang.String | Дата метаданных. |

### setMetadataDate_internalized(System.DateTime metadataDate) {#setMetadataDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setMetadataDate_internalized(System.DateTime metadataDate)
```


Добавляет дату последнего изменения метаданных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| metadataDate | com.aspose.ms.System.DateTime | Дата метаданных. |

### setModifyDate(String modifiedDate) {#setModifyDate-java.lang.String-}
```
public void setModifyDate(String modifiedDate)
```


Добавляет дату последнего изменения ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| modifiedDate | java.lang.String | Дата последнего изменения. |

### setModifyDate_internalized(System.DateTime modifiedDate) {#setModifyDate-internalized-com.aspose.ms.System.DateTime-}
```
public void setModifyDate_internalized(System.DateTime modifiedDate)
```


Добавляет дату последнего изменения ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| modifiedDate | com.aspose.ms.System.DateTime | Дата последнего изменения. |

### setRating(int choise) {#setRating-int-}
```
public void setRating(int choise)
```


Устанавливает рейтинг.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| выбор | int | От -1 до 5 |

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


Получает или задаёт объект с указанным ключом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, идентифицирующий значение. Значение: Объект. |
| значение | java.lang.Object |  |

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

