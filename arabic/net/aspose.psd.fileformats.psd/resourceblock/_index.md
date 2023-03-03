---
title: Class ResourceBlock
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.ResourceBlock فصل. كتلة المورد .
type: docs
weight: 3610
url: /ar/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

كتلة المورد .

```csharp
public abstract class ResourceBlock
```

## الخصائص

| اسم | وصف |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | الحصول على حجم بيانات المورد بالبايت. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | الحصول على أو تحديد المعرف الفريد للمورد. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | يحصل على الحد الأدنى من إصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | الحصول على اسم المورد أو تعيينه. سلسلة باسكال ، مبطن لجعل الحجم زوجياً (يتكون الاسم الفارغ من وحدتي بايت من 0) . |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا "8BIM" . |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | الحصول على حجم كتلة المورد بالبايت بما في ذلك البيانات الخاصة به. |

## طُرق

| اسم | وصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد في الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد . |

## مجالات

| اسم | وصف |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | توقيع المورد ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | توقيع مورد Photoshop العادي . |

## أعضاء آخرون

| اسم | وصف |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | يمثل حالة كتلة المورد. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* المجسم [Aspose.PSD](../../)


