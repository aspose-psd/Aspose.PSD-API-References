---
title: "الفئة LevlResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource. الفئة LevlResource. مورد طبقة تعديل التعرض."
type: docs
weight: 2950
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

الفئة LevlResource. مورد طبقة تعديل التعرض

```csharp
public class LevlResource : AdjustmentLayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | يُنشئ مثيلاً جديدًا للفئة `LevlResource`. مدعوم في أوضاع اللون GrayScale، Duotone، RGB، CMYK، Lab. 2 بايت - الإصدار (=2) 29 * 10 بايت - مجموعات سجلات المستوى مع 5 أعداد صحيحة قصيرة 4 بايت - رأس Lvls (يبدأ عند الفهرس 292) 2 بايت - الإصدار (=3) 2 بايت - عدد السجلات الكلية للمستوى 10 * (الإجمالي - 29) يجب أن يكون انتهاء الصفر لمورد Lvls مطويًا لأربعة أيضًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | يحصل على الإصدار. القيمة الافتراضية هي 2 |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | يحصل على القناة. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### انظر أيضًا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


