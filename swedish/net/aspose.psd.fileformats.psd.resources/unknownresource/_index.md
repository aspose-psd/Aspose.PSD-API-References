---
title: Class UnknownResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Resources.UnknownResource klass. Den okända resursen. När ett resursblock inte känns igen skapas detta resursblock.
type: docs
weight: 3940
url: /sv/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
## UnknownResource class

Den okända resursen. När ett resursblock inte känns igen skapas detta resursblock.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Hämtar resursdata. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Hämtar resursdatastorleken i byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Hämtar eller ställer in den unika identifieraren för resursen. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Får den minsta nödvändiga psd-versionen. |
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


