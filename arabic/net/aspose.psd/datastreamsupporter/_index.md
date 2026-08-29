---
title: "الفئة DataStreamSupporter"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.DataStreamSupporter. حاوية تدفق البيانات"
type: docs
weight: 750
url: /ar/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

حاوية تدفق البيانات.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على تدفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من الـ [`DataStreamContainer`](./datastreamcontainer/) الأساسي. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | يحفظ بيانات الكائن إلى `DataStreamSupporter` الحالي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


