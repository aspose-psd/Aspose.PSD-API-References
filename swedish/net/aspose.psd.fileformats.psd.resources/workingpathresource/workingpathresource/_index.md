---
title: "WorkingPathResource.WorkingPathResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "WorkingPathResource konstruktor. Initierar en ny instans av klassen WorkingPathResource"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.resources/workingpathresource/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource constructor

Initierar en ny instans av klassen [`WorkingPathResource`](../).

```csharp
public WorkingPathResource(byte[] dataBytes)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataBytes | Byte[] | Data för vektorsökvägen. |

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

* class [WorkingPathResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


