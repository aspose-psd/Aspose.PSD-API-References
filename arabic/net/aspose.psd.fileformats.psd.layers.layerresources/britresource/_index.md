---
title: "الفئة BritResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource. الفئة BritResource. مورد طبقة تعديل السطوع/التباين."
type: docs
weight: 2600
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

الفئة BritResource. مورد لطبقة تعديل السطوع/التباين

```csharp
public class BritResource : AdjustmentLayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [BritResource](britresource/#constructor)() | يُنشئ مثيلاً جديدًا للفئة `BritResource`. |
| [BritResource](britresource/#constructor_1)(byte[]) | يُنشئ مثيلاً جديدًا للفئة `BritResource`. يحتوي مواصفات تنسيق PSD على الوصف التالي: 2 سطوع 2 تباين 2 قيمة متوسط للسطوع والتباين 1 لون Lab فقط. لا يُستخدم في ملفات PSD الحديثة (CS5 وما فوق) حيث يوجد CgEd. يقوم CgEd بتخزين خصائص المعلومات. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | يُنشئ مثيلاً جديدًا للفئة `BritResource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | يحصل أو يضبط السطوع. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | يحصل أو يضبط التباين. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | يحصل أو يضبط القيمة المتوسطة للسطوع والتباين. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### انظر أيضًا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


