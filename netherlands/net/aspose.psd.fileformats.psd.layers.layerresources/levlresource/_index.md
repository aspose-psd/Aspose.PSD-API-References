---
title: Class LevlResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource klas. Klasse LevlResource. Hulpbron voor belichtingsaanpassing Layer
type: docs
weight: 2640
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

Klasse LevlResource. Hulpbron voor belichtingsaanpassing Layer

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initialiseert een nieuw exemplaar van het`LevlResource` klasse. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initialiseert een nieuw exemplaar van het`LevlResource` class. Ondersteund in GrayScale, Duotone, RGB, CMYK, Lab-kleurmodi 2 bytes - Versie (=2) 29 * 10 bytes - Sets van niveaurecords met 5 korte gehele getallen 4 bytes - Lvls-header (begint bij 292 index) 2 bytes - Versie (=3) 2 bytes - Telling van totaal niveau record 10 * (Totaal aantal - 29) Nul einde van Lvls-resource moet ook voor vier worden gevouwen |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | Krijgt de psd-versie. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Krijgt de handtekening. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Haalt de versie op. Standaard is 2 |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Haalt het kanaal op. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Slaat de bron op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

### Zie ook

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


