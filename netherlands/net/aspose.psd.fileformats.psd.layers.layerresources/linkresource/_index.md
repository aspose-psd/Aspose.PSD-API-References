---
title: Class LinkResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LinkResource klas. Definieert de klasse LinkResource die informatie bevat over gekoppelde of ingesloten bestanden in de afbeelding in PSDindeling. De linkbron kan meerdereLinkDataSource instanties die toegankelijk zijn voor indexeerders in elke afgeleide klasse.
type: docs
weight: 2710
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/
---
## LinkResource class

Definieert de klasse LinkResource die informatie bevat over gekoppelde of ingesloten bestanden in de afbeelding in PSD-indeling. De linkbron kan meerdere[`LinkDataSource`](../linkdatasource/) instanties die toegankelijk zijn voor indexeerders in elke afgeleide klasse.

```csharp
public abstract class LinkResource : LayerResource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DataSourceCount](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/datasourcecount/) { get; } | Haalt het aantal linkgegevensbronnen op waartoe de indexer toegang heeft. |
| [IsEmpty](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/isempty/) { get; } | Krijgt een waarde die aangeeft of deze linkresource-instantie leeg is. |
| [Item](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/item/) { get; } | Krijgt de[`LinkDataSource`](../linkdatasource/) bij de gespecificeerde index die de unieke identifier van de linkgegevensbron is.. |
| abstract [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/length/) { get; } | Haalt de lengte van de PSD global link resource in bytes op. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/psdversion/) { get; } | Haalt de versie in PSD-formaat op. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/signature/) { get; } | Haalt de PSD global link resource signature op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/linkresource/save/)(StreamContainer, int) | Slaat de bronblokgegevens op. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


