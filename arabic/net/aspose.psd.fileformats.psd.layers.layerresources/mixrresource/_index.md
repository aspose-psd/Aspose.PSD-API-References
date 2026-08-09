---
title: "الفئة MixrResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource. الفئة MixrResource. مورد لطبقة تعديل خلاط القنوات"
type: docs
weight: 3160
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

الفئة MixrResource. مورد طبقة تعديل خالط القنوات

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | يُنشئ مثيلًا جديدًا من الفئة `MixrResource`. يحتوي مواصفات تنسيق PSD على الوصف التالي: 2 نسخة (= 1) 2 أحادي اللون 20 لون RGB أو CMYK بالإضافة إلى ثابت لإعدادات الخلاط. 4 * 2 بايت من اللون مع 2 بايت من الثابت. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | يُنشئ مثيلًا جديدًا من الفئة `MixrResource`. يحتوي مواصفات تنسيق PSD على الوصف التالي: 2 نسخة (= 1) 2 أحادي اللون 20 لون RGB أو CMYK بالإضافة إلى ثابت لإعدادات الخلاط. 4 * 2 بايت من اللون مع 2 بايت من الثابت. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا `MixrResource` أحادي اللون. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | يحصل أو يضبط الإصدار. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | يحصل على البيانات الخام لمعلومات القناة. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | يضبط معلومات القناة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


