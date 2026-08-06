---
title: "FileSource"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل مصدر ملف قادر على معالجة الملفات."
type: docs
weight: 12
url: /ar/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

يمثل مصدر ملف قادر على معالجة الملفات.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | يحصل على حاوية التدفق. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | يحصل على قيمة تُشير إلى ما إذا كان الملف سيكون مؤقتًا. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSource() {#FileSource--}
```
public FileSource()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
```


يحصل على حاوية التدفق.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

استخدم بحذر. ستحتاج إلى التخلص من حاوية التدفق بعد الاسترجاع.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public abstract boolean isTemporal()
```


يحصل على قيمة تُشير إلى ما إذا كان الملف سيكون مؤقتًا.

**Returns:**
منطقي -  true  إذا كان الملف سيكون مؤقتًا؛ وإلا،  false .
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

