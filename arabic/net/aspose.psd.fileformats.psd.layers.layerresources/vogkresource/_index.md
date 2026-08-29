---
title: "الفئة VogkResource"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource. مورد بيانات الأصل المتجهة"
type: docs
weight: 3770
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
{{< psd/tize >}}
## VogkResource class

مورد بيانات أصل المتجه.

```csharp
public sealed class VogkResource : LayerResource
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [VogkResource](vogkresource/)() | ينشئ مثيلًا جديدًا للفئة `VogkResource`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | يحصل على طول مورد الطبقة بالبايت. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | يحصل على الحد الأدنى لإصدار PSD المطلوب لمورد الطبقة. 0 يعني عدم وجود قيود. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | يحصل أو يضبط إعدادات أصل الشكل. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | يحصل على التوقيع. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | يحصل أو يضبط الإصدار. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية الدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع String تمثل هذا المثيل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

## أمثلة

يوضح المثال التالي دعم مورد VogkResource.

```csharp
[C#]

VogkResource GetVogkResource(PsdImage image)
{
    var layer = image.Layers[1];

    VogkResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VogkResource)
        {
            resource = (VogkResource)resources[i];
            break;
        }
    }

    if (resource == null)
    {
        throw new Exception("VogkResourcenot found.");
    }

    return resource;
}

string sourceFilePath = "VectorOriginationDataResource.psd";
string outputFilePath = "out_VectorOriginationDataResource_.psd";

using (var psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    var resource = GetVogkResource(psdImage);

    // قراءة
    if (resource.ShapeOriginSettings.Length != 1 ||
        !resource.ShapeOriginSettings[0].IsShapeInvalidated ||
        resource.ShapeOriginSettings[0].OriginIndex != 0)
    {
        throw new Exception("VogkResource were read wrong.");
    }

    // تحرير
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### انظر أيضًا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


