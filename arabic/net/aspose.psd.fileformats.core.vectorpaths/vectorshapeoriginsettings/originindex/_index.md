---
title: VectorShapeOriginSettings.OriginIndex
second_title: Aspose.PSD لمرجع .NET API
description: VectorShapeOriginSettings ملكية. الحصول على فهرس شكل الأصل أو تعيينه.
type: docs
weight: 120
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/originindex/
---
## VectorShapeOriginSettings.OriginIndex property

الحصول على فهرس شكل الأصل أو تعيينه.

```csharp
public int OriginIndex { get; set; }
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

* class [VectorShapeOriginSettings](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* المجسم [Aspose.PSD](../../../)


