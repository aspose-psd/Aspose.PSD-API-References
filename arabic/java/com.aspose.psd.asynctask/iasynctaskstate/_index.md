---
title: "IAsyncTaskState"
second_title: "مرجع API لـ Aspose.PSD للـ Java"
description: "يوفر الوصول إلى حالة المهمة غير المتزامنة."
type: docs
weight: 17
url: /ar/java/com.aspose.psd.asynctask/iasynctaskstate/
---
```
public interface IAsyncTaskState
```

يوفر الوصول إلى حالة المهمة غير المتزامنة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getProgress()](#getProgress--) | يحصل على تقدم المهمة غير المتزامنة. |
| [incrementProgressMaxValue(int value)](#incrementProgressMaxValue-int-) | يزيد من القيمة القصوى للتقدم. |
| [indicateProgress(EventType eventType)](#indicateProgress-com.aspose.psd.progressmanagement.EventType-) | يضبط تقدم المهمة غير المتزامنة. |
| [isCanceled()](#isCanceled--) | يحصل على قيمة تشير إلى ما إذا كانت المهمة غير المتزامنة ملغاة. |
### getProgress() {#getProgress--}
```
public abstract EventType getProgress()
```


يحصل على تقدم المهمة غير المتزامنة.

القيمة: تقدم المهمة غير المتزامنة.

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the progress of the asynchronous task.
### incrementProgressMaxValue(int value) {#incrementProgressMaxValue-int-}
```
public abstract void incrementProgressMaxValue(int value)
```


يزيد من القيمة القصوى للتقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | قيمة الزيادة. |

### indicateProgress(EventType eventType) {#indicateProgress-com.aspose.psd.progressmanagement.EventType-}
```
public abstract void indicateProgress(EventType eventType)
```


يضبط تقدم المهمة غير المتزامنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | حالة التقدم. |

### isCanceled() {#isCanceled--}
```
public abstract boolean isCanceled()
```


يحصل على قيمة تشير إلى ما إذا كانت المهمة غير المتزامنة ملغاة.

القيمة:  true  إذا تم إلغاء المهمة غير المتزامنة؛ وإلا،  false .

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت المهمة غير المتزامنة ملغاة.
