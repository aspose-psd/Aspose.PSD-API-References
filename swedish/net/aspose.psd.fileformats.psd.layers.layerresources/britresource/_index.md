---
title: "Klass BritResource"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BritResource‑klass. Klass BritResource. Resurs för ljusstyrke-/kontrastjusteringslager"
type: docs
weight: 2600
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---
{{< psd/tize >}}
## BritResource class

Klassen BritResource. Resurs för ljusstyrka/kontrast‑justeringslager.

```csharp
public class BritResource : AdjustmentLayerResource
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [BritResource](britresource/#constructor)() | Initierar en ny instans av klassen `BritResource`. |
| [BritResource](britresource/#constructor_1)(byte[]) | Initierar en ny instans av klassen `BritResource`. PSD‑formatsspecifikationen innehåller följande beskrivning: 2 Ljusstyrka 2 Kontrast 2 Medelvärde för ljusstyrka och kontrast 1 Endast Lab‑färg. Den används inte i moderna PSD‑filer (CS5 och senare) där CgEd finns. CgEd lagrar informationsegenskaper. |
| [BritResource](britresource/#constructor_2)(short, short, short, bool) | Initierar en ny instans av klassen `BritResource`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Brightness](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/brightness/) { get; set; } | Hämtar eller anger ljusstyrkan. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/contrast/) { get; set; } | Hämtar eller anger kontrasten. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Hämtar lagerresursens nyckel. |
| [LabColor](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/labcolor/) { get; set; } | Hämtar eller anger ett värde som indikerar om [lab color]. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/length/) { get; } | Hämtar lagerresursens längd i byte. |
| [MeanValueForBrightnessAndContrast](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/meanvalueforbrightnessandcontrast/) { get; set; } | Hämtar eller anger medelvärdet för ljusstyrka och kontrast. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Hämtar den minsta PSD-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Hämtar signaturen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar en String som representerar detta objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/britresource/typetoolkey/) | Typverktygsinformationsnyckeln. |

### Se även

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


