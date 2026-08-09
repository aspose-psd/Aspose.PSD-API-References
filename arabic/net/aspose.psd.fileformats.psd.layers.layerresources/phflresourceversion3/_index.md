---
title: "الفئة PhflResourceVersion3"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3. الفئة PhflResource. مورد طبقة تعديل التعرض 2 الإصدار 3 أو 2 12 4 بايت لكل لون XYZ فقط في الإصدار 3 10 2 بايت مساحة اللون تليها 4 2 بايت مكوّن اللون فقط في الإصدار 2 4 الكثافة 1 الحفاظ على الإضاءة"
type: docs
weight: 3260
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

الفئة PhflResource. مورد طبقة تعديل التعرض الإصدار 2 ( = 3 ) أو ( = 2 ) 12 4 بايت لكل لون XYZ (فقط في الإصدار 3) 10 2 بايت مساحة اللون تليها 4 * 2 بايت مكوّن اللون (فقط في الإصدار 2) 4 الكثافة 1 الحفاظ على الإضاءة

```csharp
public class PhflResourceVersion3 : PhflResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | ينشئ مثيلاً جديدًا للفئة `PhflResourceVersion3`. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | ينشئ مثيلاً جديدًا للفئة `PhflResourceVersion3`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | يحصل على مساحة اللون. |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | يحصل أو يضبط اللون X. |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | يحصل أو يضبط اللون Y. |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | يحصل أو يضبط اللون Z. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | يحصل أو يضبط الكثافة. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | يحصل على الإصدار. الافتراضي هو 2 أو 3. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | يحصل على اللون. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | يضبط لون RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

### انظر أيضًا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


