---
title: Class LayerMaskDataFull
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull klas. Definieert de klasse LayerMaskDataFull die informatie bevat over de maskergegevens in het PSDbestand layer wanneer de laag zowel laag als vectormaskers heeft. Anders eenLayerMaskDataShort wordt gebruikt. De ImageData bevat het gecombineerde rastermasker en het gerasterde vectormasker. De lengte van de ImageDatabytes moet gelijk zijn MaskRectangle.Width  MaskRectangle.Heighteigenschappen.
type: docs
weight: 2250
url: /nl/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Definieert de klasse LayerMaskDataFull die informatie bevat over de maskergegevens in het PSD-bestand layer wanneer de laag zowel laag- als vectormaskers heeft. Anders, een[`LayerMaskDataShort`](../layermaskdatashort/) wordt gebruikt. De ImageData bevat het gecombineerde rastermasker en het gerasterde vectormasker. De lengte van de ImageData-bytes moet gelijk zijn MaskRectangle.Width * MaskRectangle.Height-eigenschappen.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | De standaard constructeur. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Krijgt of stelt de achtergrondkleur in. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Haalt of stelt de maskerpositie van de onderste laag in. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Haalt de grootte van de maskergegevens van het laagmasker op. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Haalt of stelt de standaardkleur in. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Haalt of stelt de positie van het omsluitende onderste rastermasker in de PSD-afbeeldingslaag in. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Haalt of stelt de omsluitende linker rastermaskerpositie in de PSD-bestandslaag in. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Haalt of stelt de omsluitende rechter rastermaskerpositie in de PSD-bestandslaag in. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Haalt of stelt de omsluitende bovenste positie van het rastermasker in de PSD-afbeeldingslaag in. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Haalt of stelt de laagmaskervlaggen in. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Haalt de gegevens van het laagmasker op of stelt deze in (of gecombineerd/eindmasker als er een vectormasker is) in het PSD-bestand. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Haalt of stelt de maskerpositie van de linkerlaag in. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Krijgt of stelt het masker in[`Rectangle`](../../aspose.psd/rectangle/)van het laagmasker in het PSD-bestand. Het neemt de eigenschappen links, rechts, boven en onder en maakt[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Haalt of stelt de laagmaskervlaggen in die worden gebruikt voor gebruikers-/rastermaskers. Voor vectormasker wordt de eigenschap Flags gebruikt. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Haalt of stelt de juiste laagmaskerpositie in. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Haalt of stelt de maskerpositie van de bovenste laag in. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Haalt of stelt de gebruikers(raster)maskergegevens van een laag in het PSD-bestand op. (Er is een geclassificeerd vectormasker in de eigenschap MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Haalt of stelt de rechthoek van het gebruikersmasker (omsluitend) in de PSD-afbeeldingslaag in.. |

### Zie ook

* class [LayerMaskData](../layermaskdata/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* montage [Aspose.PSD](../../)


