---
title: "Klass PhflResourceVersion2"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResourceVersion2 klass. Klass PhflResource. Resurs för Exponeringsjusteringslager 2 Version 3 eller 2 12 4 byte vardera för XYZ-färg. Endast i Version 3 10 2 byte färgrymd följt av 4 2 byte färgkomponent. Endast i Version 2 4 densitet 1 bevara luminans."
type: docs
weight: 3250
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---
{{< psd/tize >}}
## PhflResourceVersion2 class

Klassen PhflResource. Resurs för justeringslagret Exposure Version 2 ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ‑färg (endast i version 3) 10 2 byte färgrymd följt av 4 × 2 byte färgkomponent (endast i version 2) 4 Densitet 1 Bevara luminans.

```csharp
public class PhflResourceVersion2 : PhflResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PhflResourceVersion2](phflresourceversion2/#constructor)() | Initierar en ny instans av klassen `PhflResourceVersion2`. |
| [PhflResourceVersion2](phflresourceversion2/#constructor_1)(byte[]) | Initierar en ny instans av klassen `PhflResourceVersion2`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/colorspace/) { get; } | Hämtar färgrymden. |
| [ComponentA](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componenta/) { get; set; } | Hämtar eller anger A-komponenten för färg |
| [ComponentB](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentb/) { get; set; } | Hämtar eller anger B-komponenten |
| [ComponentL](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/componentl/) { get; set; } | Hämtar eller anger L-komponenten för färg |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Hämtar eller anger densiteten. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Hämtar eller anger ett värde som indikerar om [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |
| override [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/version/) { get; } | Hämtar versionen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/getrgbcolor/)() | Hämtar färgen. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/setrgbcolor/)(Color) | Ställer in RGB-färgen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [PhflResource](../phflresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


