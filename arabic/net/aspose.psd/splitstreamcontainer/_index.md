---
title: "الفئة SplitStreamContainer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.SplitStreamContainer. تمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق"
type: docs
weight: 6130
url: /ar/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق.

```csharp
public class SplitStreamContainer : StreamContainer
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | يُهيئ مثلاً جديداً من الفئة `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | يُهيئ مثلاً جديداً من الفئة `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | يُهيئ مثلاً جديداً من الفئة `SplitStreamContainer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | يحصل أو يضبط طول التدفق بالبايت. هذه القيمة أقل من الطول بمقدار موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | يحصل أو يضبط الموضع الحالي داخل التدفق. هذه القيمة تمثل الإزاحة من موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | يحصل على تدفق البيانات. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | يدرج حاوية التدفق في الموضع المحدد. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | يقرأ تسلسلًا من البايتات من التدفق الحالي ويتقدم بالموقع داخل التدفق بعدد البايتات المقروءة. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | يقرأ بايتًا واحدًا من التدفق ويتقدم بالموقع داخل التدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية التدفق. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) وقيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | يحفظ (ينسخ) جميع بيانات التدفق إلى التدفق المحدد. يستخدم قيمة طول التدفق [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم قيمة طول التدفق [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | يضبط الموقع داخل التدفق الحالي. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | يضبط موقع التدفق إلى بداية التدفق. تمثل هذه القيمة الإزاحة من موقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | يحوّل بيانات التدفق إلى مصفوفة Byte. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | يحوّل بيانات التدفق إلى مصفوفة Byte. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | يكتب جميع البايتات المحددة إلى التدفق. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى التدفق الحالي ويتقدم بالموقع الحالي داخل هذا التدفق بعدد البايتات المكتوبة. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | يكتب بايتًا إلى الموقع الحالي في التدفق ويتقدم بالموقع داخل التدفق بايتًا واحدًا. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/) آخر. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | ينسخ البيانات المحتواة إلى [`StreamContainer`](../streamcontainer/) آخر. |

### انظر أيضًا

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


