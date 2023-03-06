---
title: Class LayerMaskData
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData klass. Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSDfilen. Det kan hjälpa till att modifiera Adobe Photoshopfiler programmatiskt och automatisera redigering av PSDformat. Om lagret endast har en rastermask innehåller ImageData rastret mask data bytes. Om lagret endast har en vektormask innehåller ImageData vektormasken rastrerade cachelagrade databytes. Om lagret har både lager och vektormasker innehåller ImageData rastermasken och den rastrerade vektormasken kombinerat. DeImageDatabytes längd ska vara lika Bredd  Höjd påMaskRectangle properties. Observera att det inte räcker att bara ta bort / lägga till / uppdatera LayerMaskData för att spara korrekt eftersom kanaler inte uppdateras även om det kan ge korrekt rendering. TheAddLayerMask metod ska användas för det.
type: docs
weight: 2240
url: /sv/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSD-filen. Det kan hjälpa till att modifiera Adobe® Photoshop®-filer programmatiskt och automatisera redigering av PSD-format. Om lagret endast har en rastermask innehåller ImageData rastret mask data bytes. Om lagret endast har en vektormask innehåller ImageData vektormasken rastrerade (cachelagrade) databytes. Om lagret har både lager- och vektormasker innehåller ImageData rastermasken och den rastrerade vektormasken kombinerat. De[`ImageData`](./imagedata/)bytes längd ska vara lika Bredd * Höjd på[`MaskRectangle`](./maskrectangle/) properties. Observera att det inte räcker att bara ta bort / lägga till / uppdatera LayerMaskData för att spara korrekt eftersom kanaler inte uppdateras; även om det kan ge korrekt rendering. The[`AddLayerMask`](../layer/addlayermask/) metod ska användas för det.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Får eller ställer in rätt lagermaskposition. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Hämtar eller ställer in toppskiktets maskposition. |

### Se även

* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* hopsättning [Aspose.PSD](../../)


