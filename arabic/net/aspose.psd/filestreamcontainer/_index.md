---
title: "الفئة FileStreamContainer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.FileStreamContainer. مساعد لمعالجة تدفق الملفات"
type: docs
weight: 4720
url: /ar/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

مساعد لمعالجة تدفق الملفات.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | يحصل على مسار الملف. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | يحصل على قيمة تشير إلى ما إذا تم إنشاء التدفق صراحةً. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان التدفق مؤقتًا. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | يحصل أو يضبط طول التدفق بالبايت. هذه القيمة أقل من الطول بمقدار موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | يحصل أو يضبط الموضع الحالي داخل التدفق. هذه القيمة تمثل الإزاحة من موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | يحصل على تدفق البيانات. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | ينشئ تدفق ملفات جديد. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | يفتح تدفق ملفات موجود. إذا لم يكن تدفق الملفات موجودًا يتم إلقاء الاستثناء المناسب. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | يقرأ تسلسلًا من البايتات من التدفق الحالي ويتقدم بالموقع داخل التدفق بعدد البايتات المقروءة. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | يقرأ بايتًا واحدًا من التدفق ويتقدم بالموقع داخل التدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية التدفق. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | يحفظ (ينسخ) جميع بيانات التدفق إلى التدفق المحدد. يستخدم قيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم قيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | يضبط الموقع داخل التدفق الحالي. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | يضبط موقع التدفق إلى بداية التدفق. تمثل هذه القيمة الإزاحة من موقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | يحوّل بيانات التدفق إلى مصفوفة Byte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | يحوّل بيانات التدفق إلى مصفوفة Byte. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | يكتب جميع البايتات المحددة إلى التدفق. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى التدفق الحالي ويتقدم بالموقع الحالي داخل هذا التدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | يكتب بايتًا إلى الموقع الحالي في التدفق ويتقدم بالموقع داخل التدفق بايتًا واحدًا. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/) آخر. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/) آخر. |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | يُجري تحويلًا صريحًا من `FileStreamContainer` إلى Stream. (عاملان) |

### انظر أيضًا

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


