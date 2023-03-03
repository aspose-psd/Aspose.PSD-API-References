---
title: BorderInformationResource.Unit
second_title: Aspose.PSD لمرجع .NET API
description: BorderInformationResource ملكية. الحصول على أو تعيين وحدات الحدود .
type: docs
weight: 40
url: /ar/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

الحصول على أو تعيين وحدات الحدود .

```csharp
public PhysicalUnit Unit { get; set; }
```

### أمثلة

يوضح المثال التالي دعم مورد BorderInformationResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // تحديث BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### أنظر أيضا

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* المجسم [Aspose.PSD](../../../)


