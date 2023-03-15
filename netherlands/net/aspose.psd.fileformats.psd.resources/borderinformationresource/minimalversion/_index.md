---
title: BorderInformationResource.MinimalVersion
second_title: Aspose.PSD voor .NET API-referentie
description: BorderInformationResource eigendom. Krijgt de minimaal vereiste PSDversie.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
## BorderInformationResource.MinimalVersion property

Krijgt de minimaal vereiste PSD-versie.

```csharp
public override int MinimalVersion { get; }
```

### Eigendoms-waarde

De minimale PSD-versie.

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


