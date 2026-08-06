---
title: "IAsyncTask"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "المهمة غير المتزامنة."
type: docs
weight: 16
url: /ar/java/com.aspose.psd.asynctask/iasynctask/
---

**All Implemented Interfaces:**
com.aspose.ms.System.IAsyncResult, com.aspose.ms.System.IDisposable
```
public interface IAsyncTask extends System.IAsyncResult, System.IDisposable
```

المهمة غير المتزامنة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [abort()](#abort--) | يلغي هذه المهمة. |
| [cancel()](#cancel--) | يلغي هذه المهمة. |
| [getError()](#getError--) | يحصل على خطأ المهمة المتاح بعد إكمال المهمة. |
| [getProgressEventHandler()](#getProgressEventHandler--) | يحصل على معالج حدث التقدم للمهمة غير المتزامنة. |
| [getResult()](#getResult--) | يحصل على نتيجة هذه المهمة. |
| [isBusy()](#isBusy--) | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا. |
| [isCanceled()](#isCanceled--) | يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة. |
| [isFaulted()](#isFaulted--) | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة بها خطأ. |
| [runAsync()](#runAsync--) | يشغل هذه المهمة. |
| [runAsync(int priority)](#runAsync-int-) | يشغل هذه المهمة. |
| [setCompleteCallback(CompleteCallback completeCallback)](#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-) | يضبط مفوض رد النداء المكتمل. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | يضبط معالج حدث التقدم للمهمة غير المتزامنة. |
### abort() {#abort--}
```
public abstract void abort()
```


يلغي هذه المهمة. تُكمل المهمة فورًا، مع خطر عدم تحرير الموارد الداخلية غير المُدارة.

### cancel() {#cancel--}
```
public abstract void cancel()
```


يلغي هذه المهمة. تُكمل المهمة بأمان عبر إيقاف الخوارزمية بشكل مُتحكم.

### getError() {#getError--}
```
public abstract Throwable getError()
```


يحصل على خطأ المهمة المتاح بعد إكمال المهمة.

القيمة: خطأ المهمة.

**Returns:**
java.lang.Throwable - خطأ المهمة المتاح بعد إكمال المهمة.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public abstract ProgressEventHandler getProgressEventHandler()
```


يحصل على معالج حدث التقدم للمهمة غير المتزامنة.

القيمة: معالج حدث التقدم للمهمة غير المتزامنة.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler of the asynchronous task.
### getResult() {#getResult--}
```
public abstract Object getResult()
```


يحصل على نتيجة هذه المهمة.

القيمة: نتيجة هذه المهمة.

**Returns:**
java.lang.Object - نتيجة هذه المهمة.
### isBusy() {#isBusy--}
```
public abstract boolean isBusy()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا.

القيمة:  true  إذا كانت هذه المهمة قيد التشغيل حاليًا؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت هذه المهمة تعمل حاليًا.
### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة.

القيمة:  true  إذا تم إلغاء هذه المهمة؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا تم إلغاء هذه المهمة.
### isFaulted() {#isFaulted--}
```
public abstract boolean isFaulted()
```


يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة بها خطأ.

القيمة:  true  إذا حدث خطأ في هذه المهمة؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا حدث خطأ في هذه المهمة.
### runAsync() {#runAsync--}
```
public abstract void runAsync()
```


يشغل هذه المهمة.

### runAsync(int priority) {#runAsync-int-}
```
public abstract void runAsync(int priority)
```


يشغل هذه المهمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الأولوية | int | أولوية الخيط. |

### setCompleteCallback(CompleteCallback completeCallback) {#setCompleteCallback-com.aspose.psd.asynctask.CompleteCallback-}
```
public abstract void setCompleteCallback(CompleteCallback completeCallback)
```


يضبط مفوض رد النداء المكتمل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| completeCallback | [CompleteCallback](../../com.aspose.psd.asynctask/completecallback) | استدعاء الإكمال. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public abstract void setProgressEventHandler(ProgressEventHandler value)
```


يضبط معالج حدث التقدم للمهمة غير المتزامنة.

القيمة: معالج حدث التقدم للمهمة غير المتزامنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | معالج حدث التقدم للمهمة غير المتزامنة. |

