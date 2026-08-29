---
title: "BorderInformationResource.MinimalVersion"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية BorderInformationResource. يحصل على النسخة المطلوبة الأدنى من PSD"
type: docs
weight: 30
url: /ar/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
{{< psd/tize >}}
## BorderInformationResource.MinimalVersion property

يحصل على الحد الأدنى لإصدار PSD المطلوب.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

إصدار PSD الأدنى.

## أمثلة

المثال التالي يوضح دعم مورد BorderInformationResource.

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

### انظر أيضًا

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


