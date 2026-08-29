---
title: "BorderInformationResource.Width"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية BorderInformationResource. يحصل أو يضبط عرض الحد"
type: docs
weight: 50
url: /ar/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
{{< psd/tize >}}
## BorderInformationResource.Width property

يحصل أو يضبط عرض الحدود.

```csharp
public double Width { get; set; }
```

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


