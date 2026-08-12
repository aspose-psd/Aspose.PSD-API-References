---
title: "Klass MixrResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource klass. Klass MixrResource. Resurs för kanalblandningsjusteringslager"
type: docs
weight: 3160
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
{{< psd/tize >}}
## MixrResource class

Klassen MixrResource. Resurs för justeringslagret Channel Mixer.

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initierar en ny instans av klassen `MixrResource`. PSD-formatsspecifikationen innehåller följande beskrivning: 2 Version (= 1) 2 Monokrom 20 RGB- eller CMYK-färg plus konstant för blandarinställningarna. 4 * 2 byte färg med 2 byte konstant. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initierar en ny instans av klassen `MixrResource`. PSD-formatsspecifikationen innehåller följande beskrivning: 2 Version (= 1) 2 Monokrom 20 RGB- eller CMYK-färg plus konstant för blandarinställningarna. 4 * 2 byte färg med 2 byte konstant. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Hämtar eller anger ett värde som indikerar om denna `MixrResource` är monokrom. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Hämtar eller anger versionen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Hämtar kanalinformationens rådata |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Anger kanalinformationen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


