---
title: "الفئة StreamContainer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.StreamContainer. تمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق."
type: docs
weight: 6140
url: /ar/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

يمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق.

```csharp
public class StreamContainer : DisposableObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | يُهيئ نسخة جديدة من الفئة `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | يُهيئ نسخة جديدة من الفئة `StreamContainer`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | يحصل أو يضبط طول التدفق بالبايت. هذه القيمة أقل من الطول بمقدار موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | يحصل أو يضبط الموضع الحالي داخل التدفق. هذه القيمة تمثل الإزاحة من موضع بدء التدفق الممرّر في مُنشئ StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | يحصل على تدفق البيانات. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | يتخلص من المثيل الحالي. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | يقرأ تسلسلًا من البايتات من التدفق الحالي ويتقدم بالموقع داخل التدفق بعدد البايتات المقروءة. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | يقرأ بايتًا واحدًا من التدفق ويتقدم بالموقع داخل التدفق بايتًا واحدًا، أو يُعيد -1 إذا كان عند نهاية التدفق. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](./readwritebytescount/) وقيمة التدفق [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [`ReadWriteBytesCount`](./readwritebytescount/) وقيمة التدفق [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | يحفظ (ينسخ) جميع بيانات التدفق إلى التدفق المحدد. يستخدم قيمة التدفق [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. يستخدم قيمة التدفق [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | يحفظ (ينسخ) بيانات التدفق إلى التدفق المحدد. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | يضبط الموقع داخل التدفق الحالي. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | يضبط موقع التدفق إلى بداية التدفق. تمثل هذه القيمة الإزاحة من موقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | يحوّل بيانات التدفق إلى مصفوفة Byte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | يحوّل بيانات التدفق إلى مصفوفة Byte. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | يكتب جميع البايتات المحددة إلى التدفق. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | يكتب تسلسلًا من البايتات إلى التدفق الحالي ويتقدم بالموقع الحالي داخل هذا التدفق بعدد البايتات المكتوبة. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | يكتب بايتًا إلى الموقع الحالي في التدفق ويتقدم بالموقع داخل التدفق بايتًا واحدًا. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | ينسخ البيانات المحتواة إلى `StreamContainer` آخر. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | ينسخ البيانات المحتواة إلى `StreamContainer` آخر. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | يُجري تحويلًا صريحًا من `StreamContainer` إلى Stream. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة. |

### انظر أيضًا

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


