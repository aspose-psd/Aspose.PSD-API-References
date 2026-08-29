---
title: "الواجهة IAsyncTask"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الواجهة Aspose.PSD.AsyncTask.IAsyncTask. المهمة غير المتزامنة"
type: docs
weight: 80
url: /ar/net/aspose.psd.asynctask/iasynctask/
---
{{< psd/tize >}}
## IAsyncTask interface

المهمة غير المتزامنة.

```csharp
public interface IAsyncTask : IAsyncResult, IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Error](../../aspose.psd.asynctask/iasynctask/error/) { get; } | يحصل على خطأ المهمة المتاح بعد إكمال المهمة. |
| [IsBusy](../../aspose.psd.asynctask/iasynctask/isbusy/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا. |
| [IsCanceled](../../aspose.psd.asynctask/iasynctask/iscanceled/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد أُلغيت. |
| [IsFaulted](../../aspose.psd.asynctask/iasynctask/isfaulted/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد حدث فيها خطأ. |
| [Progress](../../aspose.psd.asynctask/iasynctask/progress/) { get; } | يحصل على تقدم المهمة غير المتزامنة. |
| [Result](../../aspose.psd.asynctask/iasynctask/result/) { get; } | يحصل على نتيجة هذه المهمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Abort](../../aspose.psd.asynctask/iasynctask/abort/)() | يُوقف هذه المهمة. تُكتمل المهمة فورًا، مع خطر عدم تحرير الموارد غير المُدارة الداخلية. |
| [Cancel](../../aspose.psd.asynctask/iasynctask/cancel/)() | يلغي هذه المهمة. تُكتمل المهمة بأمان عن طريق إيقاف الخوارزمية بشكل مُتحكم. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync)() | يشغّل هذه المهمة. |
| [RunAsync](../../aspose.psd.asynctask/iasynctask/runasync/#runasync_1)(ThreadPriority) | يشغّل هذه المهمة. |
| [SetCompleteCallback](../../aspose.psd.asynctask/iasynctask/setcompletecallback/)(CompleteCallback) | يضبط مفوض الاستدعاء عند الاكتمال. |
| [SetProgressCallback](../../aspose.psd.asynctask/iasynctask/setprogresscallback/)(ProgressCallback) | يضبط مفوض الاستدعاء لتحديث التقدم. |

### انظر أيضًا

* namespace [Aspose.PSD.AsyncTask](../../aspose.psd.asynctask/)
* assembly [Aspose.PSD](../../)


