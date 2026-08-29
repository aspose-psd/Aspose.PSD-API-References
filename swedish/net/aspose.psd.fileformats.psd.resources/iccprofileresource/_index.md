---
title: "Klass IccProfileResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Resources.IccProfileResource-klass. Representerar ICC-profilresursen"
type: docs
weight: 4230
url: /sv/net/aspose.psd.fileformats.psd.resources/iccprofileresource/
---
{{< psd/tize >}}
## IccProfileResource class

Representerar ICC‑profilresursen.

```csharp
public sealed class IccProfileResource : ResourceBlock
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [IccProfileResource](iccprofileresource/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/iccprofileresource/datasize/) { get; } | Hämtar resursens datastorlek i byte. |
| [IccProfile](../../aspose.psd.fileformats.psd.resources/iccprofileresource/iccprofile/) { get; set; } | Hämtar eller anger ICC-profilen. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Hämtar eller anger den unika identifieraren för resursen. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/iccprofileresource/minimalversion/) { get; } | Hämtar den minsta erforderliga PSD-versionen. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Hämtar eller anger resursnamnet. Pascal-sträng, utfylld för att göra storleken jämn (ett nullnamn består av två nollbyte). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Hämtar resursens signatur. Ska alltid vara '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Hämtar resursblockets storlek i byte inklusive dess data. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Sparar resursblocket till den angivna strömmen. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validerar resursvärdena. |

### Se även

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


