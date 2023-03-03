---
title: Class DataStreamSupporter
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.DataStreamSupporter فصل. حاوية دفق البيانات .
type: docs
weight: 740
url: /ar/net/aspose.psd/datastreamsupporter/
---
## DataStreamSupporter class

حاوية دفق البيانات .

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | يحصل على دفق بيانات الكائن. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتًا حاليًا ولا يلزم قراءة البيانات. |

## طُرق

| اسم | وصف |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | يخزن البيانات ويضمن عدم إجراء أي تحميل إضافي للبيانات من الأساس[`DataStreamContainer`](./datastreamcontainer/) . |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | يحفظ بيانات الكائن في الوضع الحالي`DataStreamSupporter` . |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | يحفظ بيانات الكائن في الدفق المحدد. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | يحفظ بيانات الكائن في موقع الملف المحدد. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | يحفظ بيانات الكائن في موقع الملف المحدد. |

### أنظر أيضا

* class [DisposableObject](../disposableobject/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


