---
title: "AsyncTask"
second_title: "Aspose.PSD voor Java API-referentie"
description: "The statische fabrieksklasse voor het maken van de asynchrone taken"
type: docs
weight: 10
url: /nl/java/com.aspose.psd.asynctask/asynctask/
---

**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

The statische fabrieksklasse voor het maken van de asynchrone taken
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.psd.asynctask.AsyncTaskAction-) | Maakt de asynchrone taak aan zonder resultaat. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.psd.asynctask.AsyncTaskFunc-) | Maakt de asynchrone taak aan met een generiek type resultaat. |
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


Maakt de asynchrone taak aan zonder resultaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.psd.asynctask/asynctaskaction) | De taakactie. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.psd.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Maakt de asynchrone taak aan met een generiek type resultaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.psd.asynctask/asynctaskfunc) | De taakfunctie. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

