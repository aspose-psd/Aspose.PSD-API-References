---
title: Interface IVectorPathData
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Core.VectorPaths.IVectorPathData koppel. De interface voor toegang tot de vectorpadgegevens.
type: docs
weight: 1350
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/
---
## IVectorPathData interface

De interface voor toegang tot de vectorpadgegevens.

```csharp
public interface IVectorPathData
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isdisabled/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie is uitgeschakeld. |
| [IsInverted](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isinverted/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie geïnverteerd is. |
| [IsNotLinked](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/isnotlinked/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie niet is gekoppeld. |
| [Paths](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/paths/) { get; set; } | Haalt of stelt de padrecords in. |
| [Version](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/version/) { get; set; } | Haalt of stelt de versie in. |

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

* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* montage [Aspose.PSD](../../)


