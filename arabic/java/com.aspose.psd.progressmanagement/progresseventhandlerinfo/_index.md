---
title: "ProgressEventHandlerInfo"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "تمثل هذه الفئة معلومات حول تقدم عمليات تحميل/حفظ/تصدير الصورة التي يمكن استخدامها في تطبيق خارجي لعرض تقدم التحويل للمستخدم النهائي."
type: docs
weight: 10
url: /ar/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

هذه الفئة تمثل معلومات حول تقدم عمليات تحميل/حفظ/تصدير الصورة، والتي يمكن استخدامها في تطبيق خارجي لعرض تقدم التحويل للمستخدم النهائي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | يضيف معالج حدث التقدم. |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | يحصل على وصف الحدث |
| [getEventType()](#getEventType--) | يحصل على نوع الحدث. |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | يحصل على أحدث معالج حدث التقدم. |
| [getMaxValue()](#getMaxValue--) | يحصل على الحد الأعلى لقيمة التقدم. |
| [getValue()](#getValue--) | يحصل على قيمة التقدم الحالية. |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | يشير إلى التقدم. |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | يشير إلى التقدم. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | الحد الأعلى لقيمة التقدم. |
| [setValue_internalized(int value)](#setValue-internalized-int-) | قيمة التقدم الحالية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


يضيف معالج حدث التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | معالج حدث التقدم. |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الإجمالي | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


يحصل على وصف الحدث

القيمة: الوصف.

**Returns:**
java.lang.String - وصف الحدث
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


يحصل على نوع الحدث.

القيمة: نوع الحدث.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


يحصل على أحدث معالج حدث التقدم.

القيمة: أحدث معالج حدث التقدم.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


يحصل على الحد الأعلى لقيمة التقدم.

القيمة: الحد الأعلى لقيمة التقدم.

**Returns:**
int - الحد الأعلى لقيمة التقدم.
### getValue() {#getValue--}
```
public final int getValue()
```


يحصل على قيمة التقدم الحالية.

القيمة: قيمة التقدم.

**Returns:**
int - قيمة التقدم الحالية.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


يشير إلى التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | نوع الحدث. |

**Returns:**
boolean - true إذا نجح، false إذا لم ينجح
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


يشير إلى التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | نوع الحدث. |
| القيمة | int | القيمة. |

**Returns:**
boolean - true إذا نجح، false إذا لم ينجح
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


الحد الأعلى لقيمة التقدم.

القيمة: الحد الأعلى لقيمة التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | الحد الأعلى لقيمة التقدم. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


قيمة التقدم الحالية.

القيمة: قيمة التقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | قيمة التقدم الحالية. |

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

