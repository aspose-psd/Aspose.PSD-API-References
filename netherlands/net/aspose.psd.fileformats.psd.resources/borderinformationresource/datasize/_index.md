---
title: BorderInformationResource.DataSize
second_title: Aspose.PSD voor .NET API-referentie
description: BorderInformationResource eigendom. Haalt de gegevensgrootte van de bron op in bytes.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
## BorderInformationResource.DataSize property

Haalt de gegevensgrootte van de bron op in bytes.

```csharp
public override int DataSize { get; }
```

### Eigendoms-waarde

De grootte van de brongegevens.

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


