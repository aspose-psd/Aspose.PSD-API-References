---
title: "Klass PhflResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource klass. Klass PhflResource. Resurs för exponeringsjusteringslager 2 Version   3  eller   2  12 4 byte vardera för XYZ-färgEndast i Version 3 10 2 byte färgrymd följt av 4  2 byte färgkomponentEndast i Version 2 4 Densitet 1 Bevara luminans"
type: docs
weight: 3240
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
{{< psd/tize >}}
## PhflResource class

Klassen PhflResource. Resurs för justeringslagret Exposure Version 2 ( = 3 ) eller ( = 2 ) 12 4 byte vardera för XYZ‑färg (endast i version 3) 10 2 byte färgrymd följt av 4 × 2 byte färgkomponent (endast i version 2) 4 Densitet 1 Bevara luminans.

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Hämtar eller anger densiteten. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Hämtar eller anger ett värde som indikerar om [preserve luminosity]. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Hämtar versionen. Standard är 2 eller 3 |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Hämtar färgen för RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Ställer in RGB-färgen. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


