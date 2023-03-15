---
title: VogkResource.PsdVersion
second_title: Aspose.PSD لمرجع .NET API
description: VogkResource ملكية. يحصل على الحد الأدنى من إصدار psd المطلوب لمورد الطبقة. 0 يشير إلى عدم وجود قيود.
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/psdversion/
---
## VogkResource.PsdVersion property

يحصل على الحد الأدنى من إصدار psd المطلوب لمورد الطبقة. 0 يشير إلى عدم وجود قيود.

```csharp
public override int PsdVersion { get; }
```

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

* class [VogkResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vogkresource/)
* المجسم [Aspose.PSD](../../../)


