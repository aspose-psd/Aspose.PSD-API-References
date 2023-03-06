---
title: BorderInformationResource.Unit
second_title: Aspose.PSD voor .NET API-referentie
description: BorderInformationResource eigendom. Haalt of stelt de grenseenheden in.
type: docs
weight: 40
url: /nl/net/aspose.psd.fileformats.psd.resources/borderinformationresource/unit/
---
## BorderInformationResource.Unit property

Haalt of stelt de grenseenheden in.

```csharp
public PhysicalUnit Unit { get; set; }
```

### Voorbeelden

Het volgende voorbeeld demonstreert de ondersteuning van de BorderInformationResource-resource.

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

    // update BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Zie ook

* enum [PhysicalUnit](../../../aspose.psd.fileformats.psd.resources.resolutionenums/physicalunit/)
* class [BorderInformationResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* montage [Aspose.PSD](../../../)


