---
title: Interface IVectorPathData
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData gränssnitt. Gränssnittet för åtkomst till vektorsökvägsdata.
type: docs
weight: 1350
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

Gränssnittet för åtkomst till vektorsökvägsdata.

```csharp
public interface IVectorPathData
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är inaktiverad. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är inverterad. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans inte är länkad. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Hämtar eller sätter sökvägsposterna. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Hämtar eller ställer in versionen. |

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

* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* hopsättning [Aspose.PSD](../../)


