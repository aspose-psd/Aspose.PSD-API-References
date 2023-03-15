---
title: Class GridAndGuidesResouce
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Resources.GridAndGuidesResouce klass. Representerar rutnätet och vägleder resursen.
type: docs
weight: 3730
url: /sv/net/aspose.psd.fileformats.psd.resources/gridandguidesresouce/
---
## GridAndGuidesResouce class

Representerar rutnätet och vägleder resursen.

```csharp
public sealed class GridAndGuidesResouce : ResourceBlock
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GridAndGuidesResouce](gridandguidesresouce/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/datasize/) { get; } | Hämtar resursdatastorleken i byte. |
| [GridCycleX](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcyclex/) { get; set; } | Hämtar eller ställer in den horisontella rutnätscykeln. Standard är 576. |
| [GridCycleY](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/gridcycley/) { get; set; } | Hämtar eller ställer in den vertikala rutnätscykeln. Standard är 576. |
| [GuideCount](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guidecount/) { get; } | Får antalet guideresursblock. |
| [Guides](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/guides/) { get; set; } | Hämtar eller ställer in stödlinjerna. |
| [HeaderVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/headerversion/) { get; set; } | Hämtar eller ställer in rubrikversionen. Detta värde ska alltid vara 1. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Hämtar eller ställer in den unika identifieraren för resursen. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/gridandguidesresouce/minimalversion/) { get; } | Får den minsta nödvändiga psd-versionen. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Hämtar eller ställer in resursnamnet. Pascal-sträng, vadderad för att göra storleken jämn (ett nollnamn består av två byte på 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Hämtar resurssignaturen. Bör alltid vara '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Hämtar resursblockstorleken i byte inklusive dess data. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Sparar resursblocket till den angivna strömmen. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validerar resursvärdena. |

### Se även

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* hopsättning [Aspose.PSD](../../)


