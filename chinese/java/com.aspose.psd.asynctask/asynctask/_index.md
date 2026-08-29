---
title: "AsyncTask"
second_title: "Aspose.PSD 的 Java API 参考"
description: "用于创建异步任务的静态工厂类"
type: docs
weight: 10
url: /zh/java/com.aspose.psd.asynctask/asynctask/
---

**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

用于创建异步任务的静态工厂类
## Methods

| Method | 描述 |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.psd.asynctask.AsyncTaskAction-) | 创建没有任何结果的异步任务。 |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.psd.asynctask.AsyncTaskFunc-) | 创建具有泛型结果类型的异步任务。 |
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


创建没有任何结果的异步任务。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.psd.asynctask/asynctaskaction) | 任务操作。 |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.psd.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


创建具有泛型结果类型的异步任务。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.psd.asynctask/asynctaskfunc) | 任务函数。 |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

