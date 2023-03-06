---
title: IVectorPathData.Paths
second_title: Aspose.PSD för .NET API-referens
description: IVectorPathData fast egendom. Hämtar eller sätter sökvägsposterna.
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/
---
## IVectorPathData.Paths property

Hämtar eller sätter sökvägsposterna.

```csharp
public VectorPathRecord[] Paths { get; set; }
```

### Fastighetsvärde

Banorna.

### Exempel

Det här exemplet visar stödet för 'WorkingPathResource'-resursen i PsdImage.ImageResources för korrekt funktion av Crop-operationen.

```csharp
[C#]

// Beskär bilden och spara.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Sök efter WorkingPathResource-resurs.
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

    // Beskär och spara.
    psdImage.Crop(0, 500, 0, 200);
    psdImage.Save(outputFile);
}

// Ladda sparad bild och kontrollera ändringarna.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Sök efter WorkingPathResource-resurs.
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

### Se även

* class [VectorPathRecord](../../vectorpathrecord/)
* interface [IVectorPathData](../)
* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../ivectorpathdata/)
* hopsättning [Aspose.PSD](../../../)


