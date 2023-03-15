---
title: Class UnknownResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Resources.UnknownResource klas. De onbekende bron. Wanneer een bronblok niet wordt herkend wordt dit bronblok gemaakt.
type: docs
weight: 3940
url: /nl/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
## UnknownResource class

De onbekende bron. Wanneer een bronblok niet wordt herkend, wordt dit bronblok gemaakt.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Haalt de brongegevens op. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Haalt de gegevensgrootte van de bron op in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Haalt de unieke identificatie voor de resource op of stelt deze in. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Krijgt de minimaal vereiste psd-versie. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Haalt de resourcenaam op of stelt deze in. Pascal-tekenreeks, opgevuld om de grootte gelijk te maken (een null-naam bestaat uit twee bytes van 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Haalt de bronhandtekening op. Moet altijd '8BIM' zijn. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Haalt de grootte van het bronblok op in bytes inclusief de gegevens. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Slaat het bronblok op in de opgegeven stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valideert de bronwaarden. |

### Zie ook

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* montage [Aspose.PSD](../../)


