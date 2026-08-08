---
title: "IAsyncTask"
second_title: "Aspose.PSD for Java API Справочник"
description: "Асинхронная задача."
type: docs
weight: 16
url: /ru/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

Асинхронная задача.
## Методы

| Метод | Описание |
| --- | --- |
| [abort()](#abort--) | Прерывает эту задачу. |
| [cancel()](#cancel--) | Отменяет эту задачу. |
| [getError()](#getError--) | Получает ошибку задачи, доступную после завершения задачи. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает обработчик события прогресса асинхронной задачи. |
| [getResult()](#getResult--) | Получает результат этой задачи. |
| [isBusy()](#isBusy--) | Получает значение, указывающее, выполняется ли эта задача в данный момент. |
| [isCanceled()](#isCanceled--) | Получает значение, указывающее, была ли эта задача отменена. |
| [isFaulted()](#isFaulted--) | Получает значение, указывающее, произошла ли ошибка в этой задаче. |
| [runAsync()](#runAsync--) | Запускает эту задачу. |
| [runAsync(int priority)](#runAsync-int-) | Запускает эту задачу. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | Устанавливает делегат обратного вызова завершения. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Устанавливает обработчик события прогресса асинхронной задачи. |
### abort() {#abort--}
```
public abstract void abort()
```


Прерывает эту задачу. Задача завершается немедленно, с риском неосвобождения внутренних неуправляемых ресурсов.

### cancel() {#cancel--}
```
public abstract void cancel()
```


Отменяет эту задачу. Задача завершается безопасно за счёт контролируемой остановки алгоритма.

### getError() {#getError--}
```
public abstract Throwable getError()
```


Получает ошибку задачи, доступную после завершения задачи.

Значение: Ошибка задачи.

**Returns:**
java.lang.Throwable — ошибка задачи, доступная после завершения задачи.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


Получает обработчик события прогресса асинхронной задачи.

Значение: Обработчик события прогресса асинхронной задачи.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


Получает результат этой задачи.

Значение: Результат этой задачи.

**Returns:**
java.lang.Object — результат этой задачи.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


Получает значение, указывающее, выполняется ли эта задача в данный момент.

Значение:  true  если эта задача в данный момент выполняется; иначе  false .

**Returns:**
boolean — значение, указывающее, выполняется ли эта задача в данный момент.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


Получает значение, указывающее, была ли эта задача отменена.

Значение:  true  если эта задача была отменена; иначе  false .

**Returns:**
boolean — значение, указывающее, была ли эта задача отменена.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


Получает значение, указывающее, произошла ли ошибка в этой задаче.

Значение:  true  если у этой задачи произошла ошибка; иначе  false .

**Returns:**
boolean — значение, указывающее, произошла ли ошибка у задачи.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


Запускает эту задачу.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


Запускает эту задачу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| приоритет | int | Приоритет потока. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


Устанавливает делегат обратного вызова завершения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | Полный обратный вызов. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


Устанавливает обработчик события прогресса асинхронной задачи.

Значение: Обработчик события прогресса асинхронной задачи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Обработчик события прогресса асинхронной задачи. |

