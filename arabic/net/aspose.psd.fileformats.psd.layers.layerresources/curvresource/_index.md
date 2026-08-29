---
title: "الفئة CurvResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource. الفئة CurvResource. مورد طبقة تعديل المنحنيات 1 بايت 0 إذا تم استخدام المنحنيات 1 إذا تم استخدام بكسلات على الخريطة إذا 0 ثم 2 بايت قصير. القيمة الافتراضية هي 1 4 بايت عدد صحيح. يُستخدم فقط البايت الأخير بت. البت الأول للقناة الواحدة والبت الرابع للقنوات الأربعة على سبيل المثال 2 بايت قصير عدد النقاط 4 بايت عدد النقاط لمنحنى 2 قصير الموقع الأول الارتفاع الثاني 4 بايت كلمة Crv 2 بايت قصير القيمة الافتراضية هي 4 للمنحنيات 4 بايت عدد صحيح. القيمة الافتراضية هي 1 4 بايت عدد النقاط 4 بايت عدد النقاط لمنحنى 2 قصير الموقع الأول الارتفاع الثاني 04 بايت يؤدي إلى طي لأربعة إذا 1 ثم 2 بايت قصير. القيمة الافتراضية هي 1 4 بايت عدد صحيح. يُستخدم فقط البايت الأخير. قناة واحدة في بت واحد. البت الأول للقناة الواحدة والبت الرابع للقنوات الأربعة على سبيل المثال 256 عدد القنوات المتغيرة القيم المرتبة للقناة في النطاق 0-255 4 بايت كلمة Crv 2 بايت قصير. القيمة الافتراضية هي 3 للبكسلات على الخريطة 4 بايت عدد صحيح عدد القنوات 2 256 بايت قصير 2 لفهرس القناة 256 هي القيم المرتبة للقناة في النطاق 0-255."
type: docs
weight: 2660
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

الفئة CurvResource. مورد لطبقة تعديل المنحنيات 1 بايت - 0 إذا تم استخدام المنحنيات، 1 إذا تم استخدام خريطة البكسلات إذا 0 ثم: 2 بايت - short. القيمة الافتراضية هي 1 4 بايت - int. يُستخدم البايت الأخير فقط بت. البت الأول للقناة الواحدة، والبت الرابع للقنوات الأربعة على سبيل المثال 2 بايت - عدد نقاط short 4 بايت * عدد النقاط - نقاط المنحنى 2 short: الموقع الأول، الارتفاع الثاني 4 بايت - كلمة \"Crv \" 2 بايت - short القيمة الافتراضية هي 4 للمنحنيات 4 بايت - int. القيمة الافتراضية هي 1 4 بايت - عدد النقاط 4 بايت * عدد النقاط - نقاط المنحنى 2 short: الموقع الأول، الارتفاع الثاني 0-4 بايت - Leading to be fold for four إذا 1 ثم: 2 بايت - short. القيمة الافتراضية هي 1 4 بايت - int. يُستخدم البايت الأخير فقط. قناة واحدة في بت واحد. البت الأول للقناة الواحدة، والبت الرابع للقنوات الأربعة على سبيل المثال 256 * عدد القنوات المتغيرة - قيم مرتبة للقناة في النطاق 0 - 255 4 بايت - كلمة \"Crv \" 2 بايت - short. القيمة الافتراضية هي 3 للبكسلات على الخريطة 4 بايت - int عدد القنوات (2 + 256) بايت - short 2 لفهرس القناة، 256 هي القيم المرتبة للقناة في النطاق 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | يُنشئ مثيلاً جديدًا للفئة `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | يُنشئ مثيلاً جديدًا للفئة `CurvResource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | يحصل على أو يضبط قيمة تشير إلى ما إذا كانت هذه المثيلة تخزن البيانات بشكل منفصل. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | يحصل على المدير النشط. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | يحصل على بيانات القناة. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | يحصل على مدير المنحنى. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### انظر أيضًا

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


