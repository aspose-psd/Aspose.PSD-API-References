---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD لمرجع .NET API
description: BorderInformationResource ملكية. يحصل على الحد الأدنى من إصدار PSD المطلوب.
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

يحصل على الحد الأدنى من إصدار PSD المطلوب.

```csharp
public override int MinimalVersion { get; }
```

### Property_Value

الحد الأدنى من إصدار PSD .

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

* class [BorderInformationResource](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* المجسم [Aspose.PSD](../../../)


