---
title: Class MixrResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource klas. Klasse MixrResource. Bron van Channel Mixer Adjustment Layer
type: docs
weight: 2820
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Klasse MixrResource. Bron van Channel Mixer Adjustment Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initialiseert een nieuw exemplaar van het`MixrResource` class. De specificatie van het PSD-formaat bevat de volgende beschrijving: 2 versie (= 1) 2 Monochroom 20 RGB- of CMYK-kleur plus constante voor de mixerinstellingen. 4 * 2 bytes kleur met 2 bytes constant. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initialiseert een nieuw exemplaar van het`MixrResource` class. De specificatie van het PSD-formaat bevat de volgende beschrijving: 2 versie (= 1) 2 Monochroom 20 RGB- of CMYK-kleur plus constante voor de mixerinstellingen. 4 * 2 bytes kleur met 2 bytes constant. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Haalt of stelt een waarde in die aangeeft of dit`MixrResource` is monochroom. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Krijgt de psd-versie. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Krijgt de handtekening. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Haalt of stelt de versie in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Haalt de kanaalinformatie op ruwe data |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Slaat de bron op in de opgegeven streamcontainer. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Stelt de kanaalinformatie in. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


