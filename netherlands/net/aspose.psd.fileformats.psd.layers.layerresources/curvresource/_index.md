---
title: Class CurvResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource klas. Klasse CurvResource. Bron van aanpassing van curven Layer 1 byte  0 als curven worden gebruikt 1 als pixels op kaart worden gebruikt als 0 dan 2 bytes  kort. Standaard is 1 4 bytes  int. Alleen laatste byte voor bit gebruikt. Eerste bit is voor 1 kanaal het vierde bit voor 4 kanalen bijvoorbeeld 2 bytes  korte punten count 4 bytes  aantal punten  punten van curve 2 kort eerste positie tweede hoogte 4 bytes  woord Crv  2 bytes  korte standaard is 4 voor Curves 4 bytes  int. Standaard is 1 4 bytes  aantal punten 4 bytes  aantal punten  punten van curve 2 kort eerste positie tweede hoogte 04 bytes  leidend tot vouw voor vier als 1 dan 2 bytes  kort. Standaard is 1 4 bytes  int. Alleen de laatste byte gebruikt. Eén kanaal is in één bit. Eerste bit is voor 1 kanaal het vierde bit voor 4 kanalen bijvoorbeeld 256  aantal gewijzigde kanalen  geordende waarden van kanaal in bereik 0  255 4 bytes  woord Crv  2 bytes  kort. Standaard is 3 voor pixels op map 4 bytes  int Channel count 2  256 bytes  kort 2 voor kanaalindex 256 is geordende waarden van kanaal in bereik 0  255
type: docs
weight: 2400
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Klasse CurvResource. Bron van aanpassing van curven Layer 1 byte - 0 als curven worden gebruikt, 1 als pixels op kaart worden gebruikt als 0 dan: 2 bytes - kort. Standaard is 1 4 bytes - int. Alleen laatste byte voor bit gebruikt. Eerste bit is voor 1 kanaal, het vierde bit voor 4 kanalen bijvoorbeeld 2 bytes - korte punten count 4 bytes * aantal punten - punten van curve 2 kort: eerste positie, tweede hoogte 4 bytes - woord "Crv " 2 bytes - korte standaard is 4 voor Curves 4 bytes - int. Standaard is 1 4 bytes - aantal punten 4 bytes * aantal punten - punten van curve 2 kort: eerste positie, tweede hoogte 0-4 bytes - leidend tot vouw voor vier als 1 dan: 2 bytes - kort. Standaard is 1 4 bytes - int. Alleen de laatste byte gebruikt. Eén kanaal is in één bit. Eerste bit is voor 1 kanaal, het vierde bit voor 4 kanalen bijvoorbeeld 256 * aantal gewijzigde kanalen - geordende waarden van kanaal in bereik 0 - 255 4 bytes - woord "Crv " 2 bytes - kort. Standaard is 3 voor pixels op map 4 bytes - int Channel count (2 + 256) bytes - kort 2 voor kanaalindex, 256 is geordende waarden van kanaal in bereik 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initialiseert een nieuw exemplaar van het`CurvResource` klasse. |
| [CurvResource](curvresource/#constructor_1)(int) | Initialiseert een nieuw exemplaar van het`CurvResource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Haalt een waarde op of stelt een waarde in die aangeeft of deze instantie discrete gegevens bevat. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion/) { get; } | Krijgt de psd-versie. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Krijgt de handtekening. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Haalt de actieve manager op. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Haalt de kanaalgegevens op. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Haalt de curvemanager op. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Slaat de bron op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

### Zie ook

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


