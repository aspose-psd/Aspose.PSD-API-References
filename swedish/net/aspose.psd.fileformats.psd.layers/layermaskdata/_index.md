---
title: "Klass LayerMaskData"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData-klass. Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSD-filen. Den kan hjälpa till att programatiskt ändra Adobe Photoshop-filer och automatisera redigering av PSD-formatet. Om lagret bara har en rastermask innehåller ImageData rastermaskens data‑byte. Om lagret bara har en vektormask innehåller ImageData vektormaskens rasteriserade cachade data‑byte. Om lagret har både lager- och vektormasker innehåller ImageData rastermasken och den rasteriserade vektormasken kombinerade. ImageData‑bytarnas längd bör vara lika med Width Height för MaskRectangle‑egenskaperna. Observera att enbart ta bort / lägga till / uppdatera LayerMaskData inte är tillräckligt för korrekt sparande eftersom kanalerna inte uppdateras, även om det kan ge korrekt rendering. Metoden AddLayerMask bör användas för detta."
type: docs
weight: 2440
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSD-filen. Den kan hjälpa till att programatiskt ändra Adobe® Photoshop®‑filer och automatisera redigering av PSD-formatet. Om lagret bara har en rastermask innehåller ImageData rastermaskens data‑byte. Om lagret bara har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) data‑byte. Om lagret har både lager- och vektormasker innehåller ImageData rastermasken och den rasteriserade vektormasken kombinerade. [`ImageData`](./imagedata/)‑bytarnas längd bör vara lika med Width * Height för [`MaskRectangle`](./maskrectangle/)‑egenskaperna. Observera att enbart ta bort / lägga till / uppdatera LayerMaskData inte är tillräckligt för korrekt sparande eftersom kanalerna inte uppdateras; även om det kan ge korrekt rendering. [`AddLayerMask`](../layer/addlayermask/)‑metoden bör användas för detta.

```csharp
public abstract class LayerMaskData
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Hämtar eller anger den nedre lagermaskens position. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Hämtar storleken på lagermaskens maskdata. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Hämtar eller anger standardfärgen. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Hämtar eller anger lagermaskens flaggor. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD-filen. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Hämtar eller anger den vänstra lagermaskens position. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Hämtar eller anger maskens [`Rectangle`](../../aspose.psd/rectangle/) för lagermasken i PSD-filen. Den tar vänster-, höger-, topp- och botten‑egenskaper och skapar ett [`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Hämtar eller anger den högra lagermaskens position. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Hämtar eller anger den övre lagermaskens position. |

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


