---
title: Class MlstResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MlstResource فصل. مورد mlst. تحتوي هذه الفئة  من بين أشياء أخرى  على معلومات حول موضع الطبقة على الخط الزمني.
type: docs
weight: 2830
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/
---
## MlstResource class

مورد mlst. تحتوي هذه الفئة ، من بين أشياء أخرى ، على معلومات حول موضع الطبقة على الخط الزمني.

```csharp
public class MlstResource : LayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [MlstResource](mlstresource/)() | Default_Constructor |

## الخصائص

| اسم | وصف |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/descriptorversion/) { get; } | الحصول على إصدار الوصف أو تعيينه . |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/) { get; } | الحصول على الهياكل أو تعيينها. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/psdversion/) { get; } | يحصل على نسخة مديرية الأمن العام . |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/signature/) { get; } | يحصل على التوقيع. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/save/)(StreamContainer, int) | يحفظ حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mlstresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### أمثلة

توضح التعليمة البرمجية التالية دعم مورد MlstResource الذي يوفر آلية منخفضة المستوى لمعالجة حالات الطبقة.

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

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


