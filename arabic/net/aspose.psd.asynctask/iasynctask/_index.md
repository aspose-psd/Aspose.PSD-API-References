---
title: Interface IAsyncTask
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.AsyncTask.IAsyncTask واجهه المستخدم. المهمة غير المتزامنة .
type: docs
weight: 80
url: /ar/net/aspose.psd.asynctask/iasynctask/
---
## IAsyncTask interface

المهمة غير المتزامنة .

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | يحصل على خطأ المهمة المتاح بعد اكتمال المهمة. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | يحصل على قيمة تشير إلى ما إذا كان قد تم إلغاء هذه المهمة. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | الحصول على قيمة تشير إلى ما إذا كانت هذه المهمة معيبة. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | يحصل على تقدم المهمة غير المتزامنة. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | الحصول على نتيجة هذه المهمة . |

## طُرق

| اسم | وصف |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | إحباط هذه المهمة. تكتمل المهمة على الفور ، مع المخاطرة بعدم تحرير الموارد الداخلية غير المُدارة . |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | إلغاء هذه المهمة. تكتمل المهمة بأمان من خلال الإيقاف المتحكم فيه للخوارزمية . |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | يقوم بتشغيل هذه المهمة. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | يقوم بتشغيل هذه المهمة. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | يعين مفوض رد الاتصال الكامل. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | يعين مفوض رد الاتصال للتقدم . |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* المجسم [Aspose.PSD](../../)


