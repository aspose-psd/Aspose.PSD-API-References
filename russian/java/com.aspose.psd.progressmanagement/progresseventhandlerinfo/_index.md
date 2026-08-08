---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD for Java API Справочник"
description: "Этот класс представляет информацию о прогрессе операций загрузки/сохранения/экспорта изображений, которую можно использовать во внешнем приложении для отображения прогресса конвертации пользователю."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Этот класс представляет информацию о прогрессе операций загрузки/сохранения/экспорта изображений, которую можно использовать во внешнем приложении для отображения прогресса конвертации пользователю
## Методы

| Метод | Описание |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | Добавляет обработчик события прогресса. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Получает описание события. |
| [getEventType()](#getEventType--) | Получает тип события. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | Получает последний обработчик события прогресса. |
| [getMaxValue()](#getMaxValue--) | Получает верхний предел значения прогресса. |
| [getValue()](#getValue--) | Получает текущее значение прогресса. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Указывает прогресс. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | Указывает прогресс. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | Верхний предел значения прогресса. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | Текущее значение прогресса. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


Добавляет обработчик события прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Обработчик события прогресса. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| всего | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Получает описание события.

Значение: Описание.

**Returns:**
java.lang.String - описание события
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Получает тип события.

Значение: Тип события.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


Получает последний обработчик события прогресса.

Значение: Последний обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Получает верхний предел значения прогресса.

Значение: Верхний предел значения прогресса.

**Returns:**
int - верхний предел значения прогресса.
### getValue() {#getValue--}
```
public final int getValue()
```


Получает текущее значение прогресса.

Значение: Значение прогресса.

**Returns:**
int - текущее значение прогресса.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


Указывает прогресс.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Тип события. |

**Returns:**
boolean - true если успешно, false иначе
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


Указывает прогресс.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Тип события. |
| значение | int | Значение. |

**Returns:**
boolean - true если успешно, false иначе
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


Верхний предел значения прогресса.

Значение: Верхний предел значения прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | верхний предел значения прогресса. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


Текущее значение прогресса.

Значение: Значение прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | текущее значение прогресса. |

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

