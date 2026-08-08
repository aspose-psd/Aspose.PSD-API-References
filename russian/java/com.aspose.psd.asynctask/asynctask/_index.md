---
title: "AsyncTask"
second_title: "Aspose.PSD for Java API Справочник"
description: "Статический фабричный класс для создания асинхронных задач"
type: docs
weight: 10
url: /ru/java/com.aspose.psd.asynctask/asynctask/
---

**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Статический фабричный класс для создания асинхронных задач
## Методы

| Метод | Описание |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.psd.asynctask.AsyncTaskAction-) | Создаёт асинхронную задачу без результата. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.psd.asynctask.AsyncTaskFunc-) | Создаёт асинхронную задачу с результатом обобщённого типа. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create(AsyncTaskAction taskAction) {#create-com.aspose.psd.asynctask.AsyncTaskAction-}
```
public static IAsyncTask create(AsyncTaskAction taskAction)
```


Создаёт асинхронную задачу без результата.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.psd.asynctask/asynctaskaction) | Действие задачи. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.psd.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Создаёт асинхронную задачу с результатом обобщённого типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.psd.asynctask/asynctaskfunc) | Функция задачи. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
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

