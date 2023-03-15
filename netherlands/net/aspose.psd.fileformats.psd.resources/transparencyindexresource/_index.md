---
title: Class TransparencyIndexResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Resources.TransparencyIndexResource klas. Het bronblok voor de transparantieindex.
type: docs
weight: 3920
url: /nl/net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---
## TransparencyIndexResource class

Het bronblok voor de transparantie-index.

```csharp
public sealed class TransparencyIndexResource : ResourceBlock
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [TransparencyIndexResource](transparencyindexresource/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/datasize/) { get; } | Haalt de gegevensgrootte van de bron op in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Haalt de unieke identificatie voor de resource op of stelt deze in. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/minimalversion/) { get; } | Krijgt de minimaal vereiste psd-versie. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Haalt de resourcenaam op of stelt deze in. Pascal-tekenreeks, opgevuld om de grootte gelijk te maken (een null-naam bestaat uit twee bytes van 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Haalt de bronhandtekening op. Moet altijd '8BIM' zijn. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Haalt de grootte van het bronblok op in bytes inclusief de gegevens. |
| [TransparencyIndex](../../aspose.psd.fileformats.psd.resources/transparencyindexresource/transparencyindex/) { get; set; } | Haalt de transparantiekleurindex op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Slaat het bronblok op in de opgegeven stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valideert de bronwaarden. |

### Zie ook

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* montage [Aspose.PSD](../../)


