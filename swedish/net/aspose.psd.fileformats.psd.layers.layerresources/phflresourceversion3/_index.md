---
title: "Klass PhflResourceVersion3"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion3-klass. Klass PhflResource. Resurs för Exponeringsjusteringslager 2 Version 3 eller 2 12 4 byte vardera för XYZ‑färg. Endast i Version 3 10 2 byte färgrymd följt av 4 2 byte färgkomponent. Endast i Version 2 4 Densitet 1 Bevara luminans"
type: docs
weight: 3260
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/
---
{{< psd/tize >}}
## PhflResourceVersion3 class

Klassen PhflResource. Resurs för justeringslagret Exposure Version 2 ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ‑färg (endast i version 3) 10 2 byte färgrymd följt av 4 × 2 byte färgkomponent (endast i version 2) 4 Densitet 1 Bevara luminans.

```csharp
public class PhflResourceVersion3 : PhflResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PhflResourceVersion3](phflresourceversion3/#constructor)() | Initierar en ny instans av `PhflResourceVersion3`-klassen. |
| [PhflResourceVersion3](phflresourceversion3/#constructor_1)(byte[]) | Initierar en ny instans av `PhflResourceVersion3`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorspace/) { get; } | Hämtar färgrymden. |
| [ColorX](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorx/) { get; set; } | Hämtar eller anger X‑färgen. |
| [ColorY](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colory/) { get; set; } | Hämtar eller anger Y‑färgen. |
| [ColorZ](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/colorz/) { get; set; } | Hämtar eller anger Z‑färgen. |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Hämtar eller anger densiteten. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Hämtar eller anger ett värde som indikerar om [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/version/) { get; } | Hämtar versionen. Standard är 2 eller 3 |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/getrgbcolor/)() | Hämtar färgen. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/setrgbcolor/)(Color) | Ställer in RGB-färgen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


