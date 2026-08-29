---
title: "AsyncTask"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Η στατική κλάση εργοστασίου για τη δημιουργία των ασύγχρονων εργασιών"
type: docs
weight: 10
url: /el/java/com.aspose.psd.asynctask/asynctask/
---

**Inheritance:**
java.lang.Object
```
public final class AsyncTask
```

Η στατική κλάση εργοστασίου για τη δημιουργία των ασύγχρονων εργασιών
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [create(AsyncTaskAction taskAction)](#create-com.aspose.psd.asynctask.AsyncTaskAction-) | Δημιουργεί την ασύγχρονη εργασία χωρίς κανένα αποτέλεσμα. |
| [create(AsyncTaskFunc taskFunc)](#create-com.aspose.psd.asynctask.AsyncTaskFunc-) | Δημιουργεί την ασύγχρονη εργασία με αποτέλεσμα γενικού τύπου. |
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


Δημιουργεί την ασύγχρονη εργασία χωρίς κανένα αποτέλεσμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| taskAction | [AsyncTaskAction](../../com.aspose.psd.asynctask/asynctaskaction) | Η ενέργεια της εργασίας. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### create(AsyncTaskFunc taskFunc) {#create-com.aspose.psd.asynctask.AsyncTaskFunc-}
```
public static IAsyncTask create(AsyncTaskFunc taskFunc)
```


Δημιουργεί την ασύγχρονη εργασία με αποτέλεσμα γενικού τύπου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| taskFunc | [AsyncTaskFunc](../../com.aspose.psd.asynctask/asynctaskfunc) | Η συνάρτηση της εργασίας. |

**Returns:**
[IAsyncTask](../../com.aspose.psd.asynctask/iasynctask) - The asynchronous task
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

