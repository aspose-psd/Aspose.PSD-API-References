---
title: "Klass WorkingPathResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Resources.WorkingPathResource klass. Resurs för arbetsväg"
type: docs
weight: 4450
url: /sv/net/aspose.psd.fileformats.psd.resources/workingpathresource/
---
{{< psd/tize >}}
## WorkingPathResource class

Arbetsvägsresurs.

```csharp
public sealed class WorkingPathResource : ResourceBlock, IVectorPathData
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WorkingPathResource](workingpathresource/)(byte[]) | Initierar en ny instans av klassen `WorkingPathResource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/workingpathresource/datasize/) { get; } | Hämtar resursens datastorlek i byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Hämtar eller anger den unika identifieraren för resursen. |
| [IsDisabled](../../aspose.psd.fileformats.psd.resources/workingpathresource/isdisabled/) { get; set; } | Hämtar eller anger ett värde som indikerar om den här instansen är inaktiverad. |
| [IsInverted](../../aspose.psd.fileformats.psd.resources/workingpathresource/isinverted/) { get; set; } | Hämtar eller anger ett värde som indikerar om den här instansen är inverterad. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.resources/workingpathresource/isnotlinked/) { get; set; } | Hämtar eller anger ett värde som indikerar om den här instansen inte är länkad. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/workingpathresource/minimalversion/) { get; } | Hämtar den minsta erforderliga PSD-versionen. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två nollbyte). |
| [Paths](../../aspose.psd.fileformats.psd.resources/workingpathresource/paths/) { get; set; } | Hämtar eller anger sökvägsregistren. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Hämtar resursblockets storlek i byte inklusive dess data. |
| [Version](../../aspose.psd.fileformats.psd.resources/workingpathresource/version/) { get; set; } | Hämtar eller anger versionen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Sparar resursblocket till den angivna strömmen. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validerar resursvärdena. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


