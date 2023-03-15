---
title: BorderInformationResource.DataSize
second_title: Aspose.PSD för .NET API-referens
description: BorderInformationResource fast egendom. Hämtar resursdatastorleken i byte.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
## BorderInformationResource.DataSize property

Hämtar resursdatastorleken i byte.

```csharp
public override int DataSize { get; }
```

### Fastighetsvärde

Resursdatastorleken.

### Exempel

Följande exempel visar stödet för BorderInformationResource-resursen.

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

    // uppdatera BorderInformationResource
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Se även

* class [BorderInformationResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../borderinformationresource/)
* hopsättning [Aspose.PSD](../../../)


