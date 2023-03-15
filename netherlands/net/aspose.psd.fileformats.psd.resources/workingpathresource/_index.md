---
title: Class WorkingPathResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource klas. Hulpbron werkpad.
type: docs
weight: 3980
url: /nl/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
## WorkingPathResource class

Hulpbron werkpad.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Initialiseert een nieuw exemplaar van het`WorkingPathResource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Haalt de gegevensgrootte van de bron op in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Haalt de unieke identificatie voor de resource op of stelt deze in. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie is uitgeschakeld. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie geïnverteerd is. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Haalt of stelt een waarde in die aangeeft of deze instantie niet is gekoppeld. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Krijgt de minimaal vereiste PSD-versie. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Haalt de resourcenaam op of stelt deze in. Pascal-tekenreeks, opgevuld om de grootte gelijk te maken (een null-naam bestaat uit twee bytes van 0). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Haalt of stelt de padrecords in. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Haalt de bronhandtekening op. Moet altijd '8BIM' zijn. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Haalt de grootte van het bronblok op in bytes inclusief de gegevens. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Haalt of stelt de versie in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Slaat het bronblok op in de opgegeven stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valideert de bronwaarden. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* montage [Aspose.PSD](../../)


