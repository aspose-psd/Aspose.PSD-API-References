---
title: "الفئة IAsyncTask"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.asynctask/iasynctask/
---

**Summary:** The asynchronous task.

**Module:** [aspose.psd.asynctask](/psd/python-net/aspose.psd.asynctask/)

**Full Name:** aspose.psd.asynctask.IAsyncTask

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| is_busy | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قيد التشغيل حاليًا. |
| is_canceled | bool | r | يحصل على قيمة تشير إلى ما إذا تم إلغاء هذه المهمة. |
| is_faulted | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المهمة قد فشلت. |
| progress | [AsyncTaskProgress](/psd/python-net/aspose.psd.asynctask/asynctaskprogress) | r | يحصل على تقدم المهمة غير المتزامنة. |
| result | object | r | يحصل على نتيجة هذه المهمة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| abort() | يوقف هذه المهمة.<br/>            تُكمل المهمة فورًا، مع خطر عدم تحرير الموارد غير المُدارة الداخلية. |
| cancel() | يلغي هذه المهمة.<br/>            تُكمل المهمة بأمان من خلال إيقاف الخوارزمية بشكل مُتحكم. |
| run_async() | يشغّل هذه المهمة. |


