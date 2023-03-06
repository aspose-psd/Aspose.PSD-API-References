---
title: WorkingPathResource.WorkingPathResource
second_title: Aspose.PSD voor .NET API-referentie
description: WorkingPathResource constructeur. Initialiseert een nieuw exemplaar van hetWorkingPathResource klasse.
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
## WorkingPathResource constructor

Initialiseert een nieuw exemplaar van het[`WorkingPathResource`](../) klasse.

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataBytes | Byte[] | De gegevens van het vectorpad. |

### Voorbeelden

Dit voorbeeld demonstreert de ondersteuning van de 'WorkingPathResource'-resource in PsdImage.ImageResources voor een correcte werking van de bewerking Gewas.

```csharp
[C#]

// Afbeelding bijsnijden en opslaan.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Zoek WorkingPathResource-bron.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 2572506 || record.Points[0].Y != 8535408)
    {
        throw new Exception("Values is incorrect.");
    }

    // Bijsnijden en opslaan.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Laad de opgeslagen afbeelding en controleer de wijzigingen.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Zoek WorkingPathResource-bron.
    ResourceBlock[] imageResources = psdImage.ImageResources;
    WorkingPathResource workingPathResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is WorkingPathResource)
        {
            workingPathResource = (WorkingPathResource)imageResource;
            break;
        }
    }
    BezierKnotRecord record = workingPathResource.Paths[3] as BezierKnotRecord;

    if (record.Points[0].X != 4630510 || record.Points[0].Y != 22761088)
    {
        throw new Exception("Values is incorrect.");
    }
}
```

### Zie ook

* class [WorkingPathResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* montage [Aspose.PSD](../../../)


