---
title: "Klass LayerMaskDataFull"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull-klass. Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD-fils lagret när lagret har både lager- och vektormasker. Annars används en LayerMaskDataShort. ImageData innehåller rastermasken och den rasteriserade vektormasken kombinerade. ImageData‑bytarnas längd bör vara lika med MaskRectangle.Width MaskRectangle.Height‑egenskaperna."
type: docs
weight: 2450
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD-fils lagret när lagret har både lager- och vektormasker. Annars används en [`LayerMaskDataShort`](../layermaskdatashort/). ImageData innehåller rastermasken och den rasteriserade vektormasken kombinerade. ImageData‑bytarnas längd bör vara lika med MaskRectangle.Width * MaskRectangle.Height‑egenskaperna.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Hämtar eller anger bakgrundsfärgen. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Hämtar eller anger den nedre lagermaskens position. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Hämtar storleken på lagermaskens maskdata. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Hämtar eller anger standardfärgen. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Hämtar eller anger den omgivande nedre rastermaskens position i PSD‑bildlagret. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Hämtar eller anger den omgivande vänstra rastermaskens position i PSD‑fillagret. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Hämtar eller anger den omgivande högra rastermaskens position i PSD‑fillagret. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Hämtar eller anger den omgivande övre positionen för rastermasken i PSD‑bildlagret. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Hämtar eller anger lagermaskens flaggor. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Hämtar eller anger lagermaskens data (eller kombinerad / slutgiltig mask om det finns en vektormask) i PSD-filen. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Hämtar eller anger den vänstra lagermaskens position. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Hämtar eller anger maskens [`Rectangle`](../../aspose.psd/rectangle/) för lagermasken i PSD-filen. Den tar vänster-, höger-, topp- och botten‑egenskaper och skapar ett [`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Hämtar eller anger lagermaskens flaggor som används för användar‑/rastermask. För vektormask används egenskapen Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Hämtar eller anger den högra lagermaskens position. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Hämtar eller anger den övre lagermaskens position. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Hämtar eller anger användar‑(raster) maskdata för ett lager i PSD‑filen. (Det finns en rasteriserad vektormask i egenskapen MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Hämtar eller anger användarmaskens (omslutande) rektangel i PSD‑bildlagret. |

### Se även

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


