---
title: Class SplitStreamContainer
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.SplitStreamContainer فصل. يمثل حاوية الدفق المنقسمة التي تحتوي على الدفق وتوفر إجراءات معالجة الدفق.
type: docs
weight: 5630
url: /ar/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

يمثل حاوية الدفق المنقسمة التي تحتوي على الدفق وتوفر إجراءات معالجة الدفق.

```csharp
public class SplitStreamContainer : StreamContainer
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | يقوم بتهيئة مثيل جديد لملف`SplitStreamContainer` فئة . |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | يقوم بتهيئة مثيل جديد لملف`SplitStreamContainer` فئة . |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | يقوم بتهيئة مثيل جديد لملف`SplitStreamContainer` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم القراءة. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم البحث. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا المثيل قد تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق سيتم التخلص منه عند الإغلاق. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | الحصول على طول الدفق بالبايت أو تحديده. هذه القيمة أقل منLengthمن خلال موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | الحصول على أو تحديد الموضع الحالي ضمن الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | يحصل على دفق البيانات. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | الحصول على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | التخلص من المثيل الحالي. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | يمسح كافة المخازن المؤقتة لهذا الدفق ويسبب كتابة أي بيانات مخزنة إلى الجهاز الأساسي. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | إدراج حاوية التدفق في الموضع المحدد. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | يقرأ البايت لملء المخزن المؤقت للبايتات المحدد. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | يقرأ تسلسل البايت من الدفق الحالي ويقدم الموضع داخل الدفق بعدد البايت المقروء. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | يقرأ بايت من الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد ، أو يُرجع -1 إذا كان في نهاية الدفق . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) والدفق[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) والدفق[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length/) القيمة . |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم تيار[`Length`](../streamcontainer/length/) القيمة . |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | يضبط الموضع ضمن الدفق الحالي. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | يضبط موضع الدفق على بداية الدفق. تمثل هذه القيمة الإزاحة من موضع دفق البداية الذي تم تمريره في مُنشئ StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | يحول بيانات الدفق إلى ملفByte مجموعة . |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | يحول بيانات الدفق إلى ملفByte مجموعة . |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | يكتب كل وحدات البايت المحددة في الدفق. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدم الموضع الحالي ضمن هذا الدفق بعدد البايتات المكتوبة. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | يكتب بايت إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | نسخ البيانات المضمنة إلى آخر[`StreamContainer`](../streamcontainer/) . |

### أنظر أيضا

* class [StreamContainer](../streamcontainer/)
* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


