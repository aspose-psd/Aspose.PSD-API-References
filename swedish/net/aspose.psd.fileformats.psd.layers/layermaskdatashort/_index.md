---
title: "Klass LayerMaskDataShort"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort-klass. Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD‑fillagret när lagret endast har raster‑ eller vektormask men inte båda. Annars används en LayerMaskDataFull. Om lagret endast har en rastermask innehåller ImageData rastermaskens databytes. Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade cachade databytes. Längden på ImageData‑byten ska vara lika med Width  Height för MaskRectangle‑egenskaperna."
type: docs
weight: 2460
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD‑fillagret när lagret endast har raster‑ eller vektormask men inte båda. Annars används en [`LayerMaskDataFull`](../layermaskdatafull/). Om lagret endast har en rastermask innehåller ImageData rastermaskens databytes. Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) databytes. [`ImageData`](../layermaskdata/imagedata/)‑bytenas längd ska vara lika med Width * Height för [`MaskRectangle`](../layermaskdata/maskrectangle/)‑egenskaperna.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Initierar en ny instans av klassen `LayerMaskDataShort`. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Hämtar eller anger lagermaskens utfyllnad. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Hämtar eller anger den högra lagermaskens position. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Hämtar eller anger den övre lagermaskens position. |

### Se även

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


