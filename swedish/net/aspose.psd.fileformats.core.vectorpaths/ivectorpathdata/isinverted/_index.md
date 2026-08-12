---
title: "IVectorPathData.IsInverted"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IVectorPathData egenskap. Hämtar eller anger ett värde som indikerar om detta objekt är inverterat"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/
---
{{< psd/tize >}}
## IVectorPathData.IsInverted property

Hämtar eller anger ett värde som indikerar om den här instansen är inverterad.

```csharp
public bool IsInverted { get; set; }
```

### Property Value

`true` om detta objekt är inverterat; annars `false`.

## Exempel

Detta exempel demonstrerar stöd för resursen 'WorkingPathResource' i PsdImage.ImageResources för korrekt funktion av beskärningsoperationen.

```csharp
[C#]

// Beskär bilden och spara.
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{
    // Sök WorkingPathResource-resursen.
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

// Läs in sparad bild och kontrollera förändringarna.
using (var psdImage = (PsdImage)Image.Load(outputFile))
{
    // Sök WorkingPathResource-resursen.
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

* interface [IVectorPathData](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


