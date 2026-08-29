---
title: "Klass CurvResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.CurvResource klass. Klass CurvResource. Resurs för Kurvjusteringslager 1 byte 0 om kurvor används 1 om pixlar på karta används om 0 då 2 bytes short. Standard är 1 4 bytes int. Används endast sista byte per bit. Första biten är för 1 kanal den fjärde biten för 4 kanaler till exempel 2 bytes short antal punkter 4 bytes antal punkter av kurva 2 short första position andra höjd 4 bytes word Crv 2 bytes short standard är 4 för Kurvor 4 bytes int. Standard är 1 4 bytes punktantal 4 bytes punktantal punkter av kurva 2 short första position andra höjd 04 bytes Ledande att vara vik för fyra om 1 då 2 bytes short. Standard är 1 4 bytes int. Används endast sista byte. En kanal är i en bit. Första biten är för 1 kanal den fjärde biten för 4 kanaler till exempel 256 antal ändrade kanaler ordnade värden för kanal i intervallet 0-255 4 bytes word Crv 2 bytes short. Standard är 3 för pixlar på karta 4 bytes int Kanalantal 2 256 bytes short 2 för kanalindex 256 är ordnade värden för kanal i intervallet 0-255"
type: docs
weight: 2660
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
{{< psd/tize >}}
## CurvResource class

Klass CurvResource. Resurs för Curves Adjustment Layer 1 byte – 0 om kurvor används, 1 om pixlar på karta används; om 0: 2 byte – short. Standardvärde är 1. 4 byte – int. Används endast sista byte per bit. Första biten är för 1 kanal, fjärde biten för 4 kanaler, till exempel 2 byte – short antal punkter. 4 byte * antal punkter – kurvpunkter. 2 short: första positionen, andra höjden. 4 byte – ordet "Crv ". 2 byte – short, standard är 4 för Curves. 4 byte – int. Standard är 1. 4 byte – punktantal. 4 byte * punktantal – kurvpunkter. 2 short: första positionen, andra höjden. 0‑4 byte – ledande för att vika för fyra; om 1: 2 byte – short. Standard är 1. 4 byte – int. Används endast sista byte. En kanal är i en bit. Första biten är för 1 kanal, fjärde biten för 4 kanaler, till exempel 256 * antal ändrade kanaler – ordnade värden för kanal i intervallet 0‑255. 4 byte – ordet "Crv ". 2 byte – short. Standard är 3 för pixlar på karta. 4 byte – int. Kanalantal (2 + 256) byte – short 2 för kanalindex, 256 är ordnade värden för kanal i intervallet 0‑255.

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CurvResource](curvresource/#constructor)(byte[]) | Initierar en ny instans av klassen `CurvResource`. |
| [CurvResource](curvresource/#constructor_1)(int) | Initierar en ny instans av klassen `CurvResource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely/) { get; set; } | Hämtar eller anger ett värde som indikerar om denna instans lagrar data diskret. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager/)() | Hämtar den aktiva hanteraren. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata/)(int) | Hämtar kanaldata. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager/)() | Hämtar kurvhanteraren. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


