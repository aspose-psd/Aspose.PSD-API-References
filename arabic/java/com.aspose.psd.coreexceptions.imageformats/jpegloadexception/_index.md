---
title: "JpegLoadException"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل استثناء تحميل صورة JPEG."
type: docs
weight: 14
url: /ar/java/com.aspose.psd.coreexceptions.imageformats/jpegloadexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.ImageException](../../com.aspose.psd.coreexceptions/imageexception), [com.aspose.psd.coreexceptions.imageformats.JpegException](../../com.aspose.psd.coreexceptions.imageformats/jpegexception)
```
public class JpegLoadException extends JpegException
```

يمثل استثناء تحميل صورة JPEG.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [JpegLoadException(String message)](#JpegLoadException-java.lang.String-) | يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  . |
| [JpegLoadException(String message, Throwable innerException)](#JpegLoadException-java.lang.String-java.lang.Throwable-) | يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  . |
| [JpegLoadException(String message, int reason)](#JpegLoadException-java.lang.String-int-) | يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  . |
| [JpegLoadException(String message, Throwable innerException, int reason)](#JpegLoadException-java.lang.String-java.lang.Throwable-int-) | يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getComponentsInfo_internalized()](#getComponentsInfo-internalized--) | يحصل أو يعيّن معلومات مكوّنات صورة JPEG. |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getReason()](#getReason--) | يحصل أو يعيّن سبب الخطأ. |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressed()](#getSuppressed--) |  |
| [getType()](#getType--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setComponentsInfo_internalized(JpegComponentInfo[] value)](#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---) | يحصل أو يعيّن معلومات مكوّنات صورة JPEG. |
| [setReason(int value)](#setReason-int-) | يحصل أو يعيّن سبب الخطأ. |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegLoadException(String message) {#JpegLoadException-java.lang.String-}
```
public JpegLoadException(String message)
```


يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |

### JpegLoadException(String message, Throwable innerException) {#JpegLoadException-java.lang.String-java.lang.Throwable-}
```
public JpegLoadException(String message, Throwable innerException)
```


يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | الرسالة. |
| innerException | java.lang.Throwable | الاستثناء الداخلي. |

### JpegLoadException(String message, int reason) {#JpegLoadException-java.lang.String-int-}
```
public JpegLoadException(String message, int reason)
```


يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |
| السبب | int | سبب الخطأ. |

### JpegLoadException(String message, Throwable innerException, int reason) {#JpegLoadException-java.lang.String-java.lang.Throwable-int-}
```
public JpegLoadException(String message, Throwable innerException, int reason)
```


يقوم بإنشاء نسخة جديدة من الفئة  JpegLoadException  .

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| message | java.lang.String | رسالة الاستثناء. |
| innerException | java.lang.Throwable | الاستثناء الداخلي. |
| السبب | int | سبب الخطأ. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComponentsInfo_internalized() {#getComponentsInfo-internalized--}
```
public JpegComponentInfo[] getComponentsInfo_internalized()
```


يحصل أو يعيّن معلومات مكوّنات صورة JPEG.

القيمة: معلومات مكوّنات صورة JPEG.

**Returns:**
com.aspose.internal.fileformats.jpeg.JpegComponentInfo[]
### getInnerException() {#getInnerException--}
```
public Throwable getInnerException()
```




**Returns:**
java.lang.Throwable
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```




**Returns:**
java.lang.String
### getReason() {#getReason--}
```
public int getReason()
```


يحصل أو يعيّن سبب الخطأ.

القيمة: سبب الخطأ.

**Returns:**
int
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### getType() {#getType--}
```
public System.Type getType()
```




**Returns:**
com.aspose.ms.System.Type
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setComponentsInfo_internalized(JpegComponentInfo[] value) {#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---}
```
public void setComponentsInfo_internalized(JpegComponentInfo[] value)
```


يحصل أو يعيّن معلومات مكوّنات صورة JPEG.

القيمة: معلومات مكوّنات صورة JPEG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | com.aspose.internal.fileformats.jpeg.JpegComponentInfo[] |  |

### setReason(int value) {#setReason-int-}
```
public void setReason(int value)
```


يحصل أو يعيّن سبب الخطأ.

القيمة: سبب الخطأ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

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

