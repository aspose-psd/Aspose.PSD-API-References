---
title: "Klass LevlResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource‑klass. Klass LevlResource. Resurs för exponeringjusteringslager"
type: docs
weight: 2950
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
{{< psd/tize >}}
## LevlResource class

Klass LevlResource. Resurs för exponeringjusteringslager

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Initierar en ny instans av klassen `LevlResource`. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Initierar en ny instans av klassen `LevlResource`. Stöds i färglägena GrayScale, Duotone, RGB, CMYK, Lab. 2 byte – Version (=2) 29 * 10 byte – Uppsättningar av nivåposter med 5 korta heltal 4 byte – Lvls‑huvud (börjar vid index 292) 2 byte – Version (=3) 2 byte – Antal totala nivåposter 10 * (Totalantal - 29) Nollavslutning av Lvls‑resursen bör också vikas för fyra. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Hämtar versionen. Standard är 2. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Hämtar kanalen. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


