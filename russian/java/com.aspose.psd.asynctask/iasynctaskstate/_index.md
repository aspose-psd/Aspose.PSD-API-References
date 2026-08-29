---
title: "IAsyncTaskState"
second_title: "Aspose.PSD for Java API Справочник"
description: "Предоставляет доступ к состоянию асинхронной задачи."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

Предоставляет доступ к состоянию асинхронной задачи.
## Методы

| Метод | Описание |
| --- | --- |
| [getProgress()](#getProgress--) | Возвращает прогресс асинхронной задачи. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | Увеличивает максимальное значение прогресса. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | Устанавливает прогресс асинхронной задачи. |
| [isCanceled()](#isCanceled--) | Получает значение, указывающее, отменена ли асинхронная задача. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


Возвращает прогресс асинхронной задачи.

Значение: Прогресс асинхронной задачи.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


Увеличивает максимальное значение прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Значение увеличения. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


Устанавливает прогресс асинхронной задачи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | Состояние прогресса. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Получает значение, указывающее, отменена ли асинхронная задача.

Значение:  true  если асинхронная задача отменена; иначе,  false .

**Returns:**
boolean — значение, указывающее, отменена ли асинхронная задача.
