---
title: Class FileStreamContainer
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileStreamContainer فصل. مساعد لمعالجة دفق الملفات.
type: docs
weight: 4250
url: /ar/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

مساعد لمعالجة دفق الملفات.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم البحث. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | يحصل على مسار الملف. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق قد تم إنشاؤه بشكل صريح. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق سيتم التخلص منه عند الإغلاق. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان الدفق مؤقتًا. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | الحصول على طول الدفق بالبايت أو تحديده. هذه القيمة أقل منLengthمن خلال موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | الحصول على أو تحديد الموضع الحالي ضمن الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | الحصول على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## طُرق

| اسم | وصف |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | إنشاء دفق ملف جديد. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | يفتح تدفق ملف موجود. إذا لم يكن دفق الملف موجودًا ، فسيتم طرح الاستثناء المناسب. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | يمسح كافة المخازن المؤقتة لهذا الدفق ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | يقرأ البايت لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | يقرأ تسلسل البايت من الدفق الحالي ويقدم الموضع داخل الدفق بعدد البايت المقروء. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | يقرأ بايت من الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد ، أو يُرجع -1 إذا كان في نهاية الدفق . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) والدفق[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) والدفق[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | يضبط الموضع ضمن الدفق الحالي. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | يضبط موضع الدفق على بداية الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | يحول بيانات الدفق إلى ملفByte مجموعة . |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | يحول بيانات الدفق إلى ملفByte مجموعة . |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | يكتب كل وحدات البايت المحددة في الدفق. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدم الموضع الحالي ضمن هذا الدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | يكتب بايت إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer/) . |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | يقوم بإجراء تحويل صريح من`FileStreamContainer` لStream . (2 operators) |

### أنظر أيضا

* class [StreamContainer](../streamcontainer/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


