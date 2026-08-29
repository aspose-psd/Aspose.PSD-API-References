---
title: "الفئة MlstResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource. مورد mlst. تحتوي هذه الفئة، من بين أمور أخرى، على معلومات حول موضع الطبقة على المخطط الزمني"
type: docs
weight: 3170
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
{{< psd/tize >}}
## MlstResource class

المورد mlst. هذه الفئة، من بين أمور أخرى، تحتوي على معلومات حول موضع الطبقة على المخطط الزمني.

```csharp
public class MlstResource : LayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MlstResource](mlstresource/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | يحصل أو يضبط نسخة الوصف. |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | يحصل أو يضبط البُنى. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | يحفظ حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## أمثلة

الكود التالي يوضح دعم مورد MlstResource الذي يوفر آلية منخفضة المستوى للتعامل مع حالات الطبقة.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // تعطيل الطبقة 1 في الإطار 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


