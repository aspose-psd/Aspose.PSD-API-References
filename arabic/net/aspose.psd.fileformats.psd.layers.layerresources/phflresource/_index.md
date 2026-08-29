---
title: "الفئة PhflResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource. الفئة PhflResource. مورد طبقة تعديل التعرض الإصدار 2. الإصدار 3 أو 2. 12-4 بايت لكل لون XYZ فقط في الإصدار 3 10 بايت مساحة اللون يتبعها 4-2 بايت مكوّن اللون فقط في الإصدار 2 4 الكثافة 1 الحفاظ على السطوع."
type: docs
weight: 3240
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

الفئة PhflResource. مورد طبقة تعديل التعرض الإصدار 2 ( = 3 ) أو ( = 2 ) 12 4 بايت لكل لون XYZ (فقط في الإصدار 3) 10 2 بايت مساحة اللون تليها 4 * 2 بايت مكوّن اللون (فقط في الإصدار 2) 4 الكثافة 1 الحفاظ على الإضاءة

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | يحصل أو يضبط الكثافة. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | الحصول أو تعيين قيمة تشير إلى ما إذا كان [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | يحصل على الإصدار. الافتراضي هو 2 أو 3. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | يحصل على لون RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | يضبط لون RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### انظر أيضًا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


