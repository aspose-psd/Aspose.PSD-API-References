---
title: Class ResourceBlock
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.ResourceBlock klas. Het bronblok.
type: docs
weight: 3610
url: /nl/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

Het bronblok.

```csharp
public abstract class ResourceBlock
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Haalt de gegevensgrootte van de bron op in bytes. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Haalt de unieke identificatie voor de resource op of stelt deze in. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Krijgt de minimaal vereiste PSD-versie. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Haalt de resourcenaam op of stelt deze in. Pascal-tekenreeks, opgevuld om de grootte gelijk te maken (een null-naam bestaat uit twee bytes van 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Haalt de bronhandtekening op. Moet altijd '8BIM' zijn. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Haalt de grootte van het bronblok op in bytes inclusief de gegevens. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Slaat het bronblok op in de opgegeven stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Valideert de bronwaarden. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | De bronhandtekening van ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | De reguliere Photoshop-resourcehandtekening. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | Vertegenwoordigt de staat van het bronblok. |

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)


