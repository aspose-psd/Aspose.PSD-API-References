---
title: Class LayerMaskDataShort
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort klass. Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSDfilen layer när lagret bara har raster eller vektormask men inte båda. Annars aLayerMaskDataFull används. Om lagret endast har en rastermask innehåller ImageData rastermaskdatabytes. Om lagret endast har en vektormask innehåller ImageData vektormasken rasteriserade cachade databytes. ImageDatabytes längd ska vara lika Bredd  Höjd påMaskRectangle egenskaper.
type: docs
weight: 2260
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD-filen layer när lagret bara har raster- eller vektormask men inte båda. Annars, a[`LayerMaskDataFull`](../layermaskdatafull/) används. Om lagret endast har en rastermask innehåller ImageData rastermaskdatabytes. Om lagret endast har en vektormask innehåller ImageData vektormasken rasteriserade (cachade) databytes. [`ImageData`](../layermaskdata/imagedata/)bytes längd ska vara lika Bredd * Höjd på[`MaskRectangle`](../layermaskdata/maskrectangle/) egenskaper.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Hämtar eller ställer in bottenskiktets maskposition. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Hämtar storleken på data för lagermaskmasken. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Hämtar eller ställer in standardfärgen. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Hämtar eller ställer in lagermaskflaggor. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Hämtar eller ställer in lagermaskdata (eller kombinerad/slutlig mask om det finns en vektormask) i PSD-filen. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Hämtar eller ställer in den vänstra lagermaskpositionen. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Hämtar eller ställer in masken[`Rectangle`](../../aspose.psd/rectangle/)av lagermasken i PSD-filen. Den tar egenskaper för vänster, höger, topp och botten och skapar[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Hämtar eller ställer in lagermaskens utfyllnad. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Får eller ställer in rätt lagermaskposition. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Hämtar eller ställer in toppskiktets maskposition. |

### Se även

* class [LayerMaskData](../layermaskdata/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* hopsättning [Aspose.PSD](../../)


