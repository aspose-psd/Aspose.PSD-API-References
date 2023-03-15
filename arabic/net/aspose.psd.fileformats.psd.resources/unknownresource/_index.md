---
title: Class UnknownResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Resources.UnknownResource فصل. المورد غير المعروف. عندما لا يتم التعرف على كتلة المورد  يتم إنشاء كتلة المورد هذه.
type: docs
weight: 3940
url: /ar/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
## UnknownResource class

المورد غير المعروف. عندما لا يتم التعرف على كتلة المورد ، يتم إنشاء كتلة المورد هذه.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## الخصائص

| اسم | وصف |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | يحصل على بيانات المورد . |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | الحصول على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | الحصول على أو تحديد المعرف الفريد للمورد. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | يحصل على الحد الأدنى من إصدار psd المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | الحصول على اسم المورد أو تعيينه. سلسلة باسكال ، مبطن لجعل الحجم زوجياً (يتكون الاسم الفارغ من وحدتي بايت من 0) . |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا "8BIM" . |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | الحصول على حجم كتلة المورد بالبايت بما في ذلك البيانات الخاصة به. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد في الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد . |

### أنظر أيضا

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* المجسم [Aspose.PSD](../../)


