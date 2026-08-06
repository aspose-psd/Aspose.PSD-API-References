---
title: "InterruptMonitor"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يمثل معلومات حول الانقطاع."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

يمثل معلومات حول الانقطاع.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | يقوم بتهيئة نسخة جديدة من الفئة  InterruptMonitor  . |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | يحصل على نسخة IInterruptMonitor التي تكون فريدة لكل خيط. |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | يرسل طلبًا لإيقاف العمليات. |
| [isInterrupted()](#isInterrupted--) | يحصل على القيمة التي تشير إلى ما إذا كان يجب إيقاف العمليات. |
| [isThreadInterrupted()](#isThreadInterrupted--) | يعيد  true  إذا كان مراقب المقاطعة للخط الحالي موجودًا وتم مقاطعته وإلا  false . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | يضبط نسخة IInterruptMonitor التي تكون فريدة لكل خيط. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


يقوم بتهيئة نسخة جديدة من الفئة  InterruptMonitor  .

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
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


يحصل على نسخة IInterruptMonitor التي تكون فريدة لكل خيط.

**Returns:**
[IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### interrupt() {#interrupt--}
```
public void interrupt()
```


يرسل طلبًا لإيقاف العمليات.

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


يحصل على القيمة التي تشير إلى ما إذا كان يجب إيقاف العمليات.

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


يعيد  true  إذا كان مراقب المقاطعة للخط الحالي موجودًا وتم مقاطعته وإلا  false .

**Returns:**
منطقي -  true  إذا كان مراقب المقاطعة للخط الحالي موجودًا وتم مقاطعته وإلا  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


يضبط نسخة IInterruptMonitor التي تكون فريدة لكل خيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor) |  |

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

