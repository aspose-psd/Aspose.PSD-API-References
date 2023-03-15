---
title: BorderInformationResource.Width
second_title: Aspose.PSD voor .NET API-referentie
description: BorderInformationResource eigendom. Haalt of stelt de randbreedte in.
type: docs
weight: 50
url: /nl/net/aspose.psd.fileformats.psd.resources/borderinformationresource/width/
---
## BorderInformationResource.Width property

Haalt of stelt de randbreedte in.

```csharp
public double Width { get; set; }
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

* class [BorderInformationResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* montage [Aspose.PSD](../../../)


