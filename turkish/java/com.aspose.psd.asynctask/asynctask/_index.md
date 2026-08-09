---
title: "AsyncTask"
second_title: "Java için Aspose.PSD API Referansı"
description: "Asenkron görevleri oluşturmak için statik fabrika sınıfı"
type: docs
weight: 10
url: /tr/java/com.aspose.psd.asynctask/asynctask/
---

**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Asenkron görevleri oluşturmak için statik fabrika sınıfı
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.psd.asynctask.AsyncTaskAction-) | Herhangi bir sonuç olmadan asenkron görevi oluşturur. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.psd.asynctask.AsyncTaskFunc-) | Genel tip sonuçlu asenkron görevi oluşturur. |
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


Herhangi bir sonuç olmadan asenkron görevi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.psd.asynctask/asynctaskaction) | Görev eylemi. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.psd.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Genel tip sonuçlu asenkron görevi oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.psd.asynctask/asynctaskfunc) | Görev işlevi. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

