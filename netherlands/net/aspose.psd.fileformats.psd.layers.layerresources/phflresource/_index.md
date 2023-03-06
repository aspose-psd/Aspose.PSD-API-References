---
title: Class PhflResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource klas. Klasse PhflResource. Bron van belichtingsaanpassingslaag 2 versie  3 of  2 12 4 bytes elk voor XYZkleur alleen in versie 3 10 2 bytes kleurruimte gevolgd door 4  2 bytes kleurcomponent alleen in versie 2 4 Dichtheid 1 Helderheid behouden
type: docs
weight: 2890
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Klasse PhflResource. Bron van belichtingsaanpassingslaag 2 versie (= 3) of (= 2) 12 4 bytes elk voor XYZ-kleur (alleen in versie 3) 10 2 bytes kleurruimte gevolgd door 4 * 2 bytes kleurcomponent (alleen in versie 2) 4 Dichtheid 1 Helderheid behouden

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Krijgt of stelt de dichtheid in. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Haalt de laagbronsleutel op. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [helderheid behouden]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Krijgt de psd-versie. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Krijgt de handtekening. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Haalt de versie op. Standaard is 2 of 3 |

## methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Krijgt de kleur van de RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Slaat de bron op in de opgegeven streamcontainer. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Stelt de RGB-kleur in. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

### Zie ook

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


