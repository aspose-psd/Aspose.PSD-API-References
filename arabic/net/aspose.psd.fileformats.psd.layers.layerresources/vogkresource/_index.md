---
title: Class VogkResource
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VogkResource فصل. مصدر بيانات إنشاء المتجه .
type: docs
weight: 3370
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/
---
## VogkResource class

مصدر بيانات إنشاء المتجه .

```csharp
public sealed class VogkResource : LayerResource
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [VogkResource](vogkresource/)() | يقوم بتهيئة مثيل جديد لملف`VogkResource` فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/key/) { get; } | يحصل على مفتاح مورد الطبقة. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/length/) { get; } | الحصول على طول مورد الطبقة بالبايت. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/) { get; } | يحصل على الحد الأدنى من إصدار psd المطلوب لمورد الطبقة. 0 يشير إلى عدم وجود قيود. |
| [ShapeOriginSettings](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/shapeoriginsettings/) { get; set; } | الحصول على أو تعيين إعدادات أصل الشكل. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/signature/) { get; } | يحصل على توقيع مورد الطبقة. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/version/) { get; set; } | الحصول على الإصدار أو تحديده. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/save/)(StreamContainer, int) | يحفظ المورد في حاوية التدفق المحددة. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | إرجاع أString الذي يمثل هذا المثال. |

## مجالات

| اسم | وصف |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vogkresource/typetoolkey/) | مفتاح معلومات أداة النوع. |

### أمثلة

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

    // التحرير
    resource.ShapeOriginSettings = new[]
    {
        resource.ShapeOriginSettings[0],
        new VectorShapeOriginSettings(true, 1)
    };

    psdImage.Save(outputFilePath);
}
```

### أنظر أيضا

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* المجسم [Aspose.PSD](../../)


