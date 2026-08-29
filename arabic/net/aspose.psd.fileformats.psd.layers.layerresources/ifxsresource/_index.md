---
title: "الفئة IfxsResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource. مورد مجموعة Ifxs لتأثيرات طبقة الموارد"
type: docs
weight: 2840
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

مورد Ifxs (مورد تأثيرات طبقة المجموعة)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [IfxsResource](ifxsresource/)() | الباني الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | يحصل على إصدار الوصف. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## أمثلة

الكود التالي يوضح دعم IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // المثال يحتوي على طبقتين مجموعتين مع تأثيرات
    // طبقة مجموعة بتأثير واحد
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // طبقة مجموعة بعدة تأثيرات
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // احصل على عدد التأثيرات وتحقق من كميتها
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // تأثير واحد في طبقة المجموعة موجود في المورد 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // اثنان أو أكثر من التأثيرات في طبقة المجموعة موجودة في المورد 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // أضف ظلًا ثالثًا إلى طبقة المجموعة التي تحتوي على تأثيرات متعددة
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### انظر أيضًا

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


