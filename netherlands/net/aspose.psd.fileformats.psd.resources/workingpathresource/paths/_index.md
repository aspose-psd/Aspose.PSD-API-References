---
title: WorkingPathResource.Paths
second_title: Aspose.PSD voor .NET API-referentie
description: WorkingPathResource eigendom. Haalt of stelt de padrecords in.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.resources/workingpathresource/paths/
---
## WorkingPathResource.Paths property

Haalt of stelt de padrecords in.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Eigendoms-waarde

De paden.

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

* class [VectorPathRecord](../../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/)
* class [WorkingPathResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../workingpathresource/)
* montage [Aspose.PSD](../../../)


