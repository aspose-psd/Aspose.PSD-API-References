---
title: "الفئة IccProfileResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Resources.IccProfileResource. تمثل مورد ملف تعريف ICC."
type: docs
weight: 4230
url: /ar/net/aspose.psd.fileformats.psd.resources/iccprofileresource/
---
{{< psd/tize >}}
## IccProfileResource class

يمثل مورد ملف تعريف ICC.

```csharp
public sealed class IccProfileResource : ResourceBlock
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [IccProfileResource](iccprofileresource/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/iccprofileresource/datasize/) { get; } | يحصل على حجم بيانات المورد بالبايت. |
| [IccProfile](../../aspose.psd.fileformats.psd.resources/iccprofileresource/iccprofile/) { get; set; } | يحصل أو يضبط ملف تعريف ICC. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | يحصل أو يضبط المعرف الفريد للمورد. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/iccprofileresource/minimalversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | يحصل أو يضبط اسم المورد. سلسلة باسكال، مملوءة لتصبح الحجم زوجيًا (اسم فارغ يتكون من بايتين من الصفر). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | يحصل على توقيع المورد. يجب أن يكون دائمًا '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | يحصل على حجم كتلة المورد بالبايت بما في ذلك بياناتها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | يحفظ كتلة المورد إلى الدفق المحدد. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | يتحقق من صحة قيم المورد. |

### انظر أيضًا

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


