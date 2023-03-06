---
title: Class LayerMaskDataShort
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort klas. Definieert de klasse LayerMaskDataShort die informatie bevat over de maskergegevens in het PSDbestand layer wanneer de laag alleen een raster of vectormasker heeft maar niet beide. Anders eenLayerMaskDataFull wordt gebruikt. Als de laag alleen een rastermasker heeft bevat de ImageData de gegevensbytes van het rastermasker. Als de laag alleen een vectormasker heeft bevat de ImageData de gerasterde cached gegevensbytes van het vectormasker. ImageDatabytes lengte moet gelijk zijn Breedte  Hoogte vanMaskRectangle eigenschappen.
type: docs
weight: 2260
url: /nl/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Definieert de klasse LayerMaskDataShort die informatie bevat over de maskergegevens in het PSD-bestand layer wanneer de laag alleen een raster- of vectormasker heeft, maar niet beide. Anders, een[`LayerMaskDataFull`](../layermaskdatafull/) wordt gebruikt. Als de laag alleen een rastermasker heeft, bevat de ImageData de gegevensbytes van het rastermasker. Als de laag alleen een vectormasker heeft, bevat de ImageData de gerasterde (cached) gegevensbytes van het vectormasker. [`ImageData`](../layermaskdata/imagedata/)bytes lengte moet gelijk zijn Breedte * Hoogte van[`MaskRectangle`](../layermaskdata/maskrectangle/) eigenschappen.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Haalt of stelt de maskerpositie van de onderste laag in. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Haalt de grootte van de maskergegevens van het laagmasker op. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Haalt of stelt de standaardkleur in. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Haalt of stelt de laagmaskervlaggen in. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Haalt de gegevens van het laagmasker op of stelt deze in (of gecombineerd/eindmasker als er een vectormasker is) in het PSD-bestand. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Haalt of stelt de maskerpositie van de linkerlaag in. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Krijgt of stelt het masker in[`Rectangle`](../../aspose.psd/rectangle/)van het laagmasker in het PSD-bestand. Het neemt de eigenschappen links, rechts, boven en onder en maakt[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Hiermee wordt de opvulling van het laagmasker opgehaald of ingesteld. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Haalt of stelt de juiste laagmaskerpositie in. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Haalt of stelt de maskerpositie van de bovenste laag in. |

### Zie ook

* class [LayerMaskData](../layermaskdata/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* montage [Aspose.PSD](../../)


