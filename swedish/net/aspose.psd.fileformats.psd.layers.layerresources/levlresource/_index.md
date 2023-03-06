---
title: Class LevlResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource klass. KlassnivåResurs. Resurs för exponeringsjustering Layer
type: docs
weight: 2640
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

KlassnivåResurs. Resurs för exponeringsjustering Layer

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initierar en ny instans av`LevlResource` class. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initierar en ny instans av`LevlResource` class. Stöds i GrayScale, Duotone, RGB, CMYK, Lab color modes 2 bytes - Version (=2) 29 * 10 byte - Uppsättningar nivåposter med 5 korta heltal 4 byte (9 byte - 2ts_0x header 2ts_0) 2 byte - Version (=3) 2 byte - Antal total nivå record 10 * (Totalt antal - 29) Nollslut av Lvls-resurs bör vara fold för fyra för |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Får signaturen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Hämtar versionen. Standard är 2 |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Får kanalen. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Typverktygets infonyckel. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


