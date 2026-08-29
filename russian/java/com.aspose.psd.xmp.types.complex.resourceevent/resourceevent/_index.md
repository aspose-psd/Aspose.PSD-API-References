---
title: "ResourceEvent"
second_title: "Aspose.PSD for Java API Справочник"
description: "Содержит размеры для нарисованного объекта."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Содержит размеры для нарисованного объекта.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Инициализирует новый экземпляр класса  ResourceEvent  . |
## Методы

| Метод | Описание |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Добавляет указанный ключ. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Получает действие. |
| [getActionDate()](#getActionDate--) | Получает или задает дату действия. |
| [getChanged()](#getChanged--) | Получает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | Получает значение xmpMM:InstanceId. |
| [getNamespaceUri()](#getNamespaceUri--) | Получает URI пространства имён по умолчанию. |
| [getParameters()](#getParameters--) | Получает или задает дополнительное описание действия. |
| [getPrefix()](#getPrefix--) | Получает префикс. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Получает или задает имя программного агента. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение в формате XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Задает действие. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Получает или задает дату действия. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Задает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | Получает или задает значение xmpMM:InstanceId. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Получает или задает дополнительное описание действия. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Получает или задает имя программного агента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Инициализирует новый экземпляр класса  ResourceEvent  .

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Добавляет указанный ключ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного с добавленным значением. |
| значение | java.lang.Object | Значение для добавления. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Получает действие.

Определённые значения: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Новые значения должны быть глаголами в прошедшем времени.

**Returns:**
java.lang.String - действие.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Получает или задает дату действия.

**Returns:**
java.util.Date - дата действия.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Получает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий.

**Returns:**
java.lang.String - список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


Получает значение xmpMM:InstanceId.

**Returns:**
java.util.UUID - значение xmpMM:InstanceId.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Получает URI пространства имён по умолчанию.

**Returns:**
java.lang.String - Значение URI пространства имён по умолчанию.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Получает или задает дополнительное описание действия.

Значение: Дополнительное описание действия.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает префикс.

**Returns:**
java.lang.String - Префикс.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Получает или задает имя программного агента.

**Returns:**
java.lang.String - Имя программного агента.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Получает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Задает действие.

Определённые значения: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Новые значения должны быть глаголами в прошедшем времени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Действие. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Получает или задает дату действия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.Date | Дата действия. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Задает список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Список частей ресурса, разделённых точкой с запятой, которые были изменены с момента предыдущей истории событий. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


Получает или задает значение xmpMM:InstanceId.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID | Значение xmpMM:InstanceId. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Получает или задает дополнительное описание действия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Дополнительное описание действия. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Получает или задает имя программного агента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Имя программного агента. |

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

