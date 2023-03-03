---
title: Class MixrResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource فصل. Class MixrResource. مورد طبقة ضبط مازج القنوات
type: docs
weight: 2820
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Class MixrResource. مورد طبقة ضبط مازج القنوات

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | يقوم بتهيئة مثيل جديد لملف`MixrResource` class. تحتوي مواصفات تنسيق PSD على الوصف التالي: 2 Version (= 1) 2 Monochrome 20 RGB أو CMYK بالإضافة إلى ثابت لإعدادات جهاز المزج. 4 * 2 بايت من اللون مع 2 بايت من الثابت . |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | يقوم بتهيئة مثيل جديد لملف`MixrResource` class. تحتوي مواصفات تنسيق PSD على الوصف التالي: 2 Version (= 1) 2 Monochrome 20 RGB أو CMYK بالإضافة إلى ثابت لإعدادات جهاز المزج. 4 * 2 بايت من اللون مع 2 بايت من الثابت . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | الحصول على أو تعيين قيمة تشير إلى ما إذا كان هذا`MixrResource` أحادي اللون. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | يحصل على نسخة مديرية الأمن العام . |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | يحصل على التوقيع. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | الحصول على الإصدار أو تحديده. |

## طُرق

| اسم | وصف |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | يحصل على بيانات أولية لمعلومات القناة |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | يضبط معلومات القناة . |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


