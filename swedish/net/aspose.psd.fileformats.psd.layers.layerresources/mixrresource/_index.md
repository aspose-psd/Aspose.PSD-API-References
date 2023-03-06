---
title: Class MixrResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource klass. Klass MixrResource. Resurs för Channel Mixer Adjustment Layer
type: docs
weight: 2820
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Klass MixrResource. Resurs för Channel Mixer Adjustment Layer

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Initierar en ny instans av`MixrResource` class. PSD-formatspecifikationen innehåller följande beskrivning: 2 Version ( = 1) 2 Monokrom 20 RGB- eller CMYK-färg plus konstant för mixerinställningarna. 4 * 2 byte färg med 2 byte konstant. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Initierar en ny instans av`MixrResource` class. PSD-formatspecifikationen innehåller följande beskrivning: 2 Version ( = 1) 2 Monokrom 20 RGB- eller CMYK-färg plus konstant för mixerinställningarna. 4 * 2 byte färg med 2 byte konstant. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta`MixrResource` är monokrom. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Får signaturen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Hämtar eller ställer in versionen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Hämtar kanalinformationen rådata |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Ställer in kanalinformationen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Typverktygets infonyckel. |

### Se även

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


