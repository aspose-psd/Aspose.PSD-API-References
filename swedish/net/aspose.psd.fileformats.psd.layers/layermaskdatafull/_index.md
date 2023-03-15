---
title: Class LayerMaskDataFull
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull klass. Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSDfilen layer när lagret har både lager och vektormasker. Annars aLayerMaskDataShort används. ImageData innehåller rastermasken och den rastrerade vektormasken kombinerat. ImageDatabytelängden ska vara lika med MaskRectangle.Width  MaskRectangle.Height properties.
type: docs
weight: 2250
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD-filen layer när lagret har både lager- och vektormasker. Annars, a[`LayerMaskDataShort`](../layermaskdatashort/) används. ImageData innehåller rastermasken och den rastrerade vektormasken kombinerat. ImageData-bytelängden ska vara lika med MaskRectangle.Width * MaskRectangle.Height properties.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Hämtar eller ställer in bakgrundsfärgen. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Hämtar eller ställer in bottenskiktets maskposition. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Hämtar storleken på data för lagermaskmasken. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Hämtar eller ställer in standardfärgen. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Hämtar eller ställer in den omgivande nedre rastermaskpositionen i PSD-bildlagret. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Hämtar eller ställer in den omslutande vänstra rastermaskpositionen i PSD-fillagret. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Hämtar eller ställer in den omslutande högra rastermaskpositionen i PSD-fillagret. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Hämtar eller ställer in den omgivande topppositionen för rastermasken i PSD-bildlagret. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Hämtar eller ställer in lagermaskflaggor. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Hämtar eller ställer in lagermaskdata (eller kombinerad/slutlig mask om det finns en vektormask) i PSD-filen. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Hämtar eller ställer in den vänstra lagermaskpositionen. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Hämtar eller ställer in masken[`Rectangle`](../../aspose.psd/rectangle/)av lagermasken i PSD-filen. Den tar egenskaper för vänster, höger, topp och botten och skapar[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Hämtar eller ställer in lagermaskflaggor som används för användar-/rastermask. För vektormask används egenskapen Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Får eller ställer in rätt lagermaskposition. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Hämtar eller ställer in toppskiktets maskposition. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Hämtar eller ställer in användarens (raster) maskdata för ett lager i PSD-filen. (Det finns en klassificerad vektormask i egenskapen MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Hämtar eller ställer in användarmaskens (omslutande) rektangel i PSD-bildlagret.. |

### Se även

* class [LayerMaskData](../layermaskdata/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* hopsättning [Aspose.PSD](../../)


