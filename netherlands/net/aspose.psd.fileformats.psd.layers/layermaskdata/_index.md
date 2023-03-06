---
title: Class LayerMaskData
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData klas. Definieert de LayerMaskDatabasisklasse die informatie bevat over de laagmaskergegevens in het PSDbestand. Het kan helpen om Adobe Photoshopbestanden programmatisch te wijzigen en het bewerken van PSDindeling te automatiseren. Als de laag alleen een rastermasker heeft bevat ImageData het raster mask data bytes. Als de laag alleen een vectormasker heeft bevat de ImageData de vectormasker gerasterde cached databytes. Als de laag zowel laag als vectormaskers heeft bevat ImageData het gecombineerde rastermasker en het gerasterde vectormasker. DeImageDatabytes lengte moet gelijk zijn Breedte  Hoogte vanMaskRectangle properties. Merk op dat alleen het verwijderen / toevoegen / bijwerken van de LayerMaskData niet voldoende is voor correct opslaan omdat kanalen niet worden bijgewerkt hoewel het een correcte weergave kan opleveren. DeAddLayerMask methode moet daarvoor worden gebruikt.
type: docs
weight: 2240
url: /nl/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Definieert de LayerMaskData-basisklasse die informatie bevat over de laagmaskergegevens in het PSD-bestand. Het kan helpen om Adobe® Photoshop®-bestanden programmatisch te wijzigen en het bewerken van PSD-indeling te automatiseren. Als de laag alleen een rastermasker heeft, bevat ImageData het raster mask data bytes. Als de laag alleen een vectormasker heeft, bevat de ImageData de vectormasker gerasterde (cached) databytes. Als de laag zowel laag- als vectormaskers heeft, bevat ImageData het gecombineerde rastermasker en het gerasterde vectormasker. De[`ImageData`](./imagedata/)bytes lengte moet gelijk zijn Breedte * Hoogte van[`MaskRectangle`](./maskrectangle/) properties. Merk op dat alleen het verwijderen / toevoegen / bijwerken van de LayerMaskData niet voldoende is voor correct opslaan omdat kanalen niet worden bijgewerkt; hoewel het een correcte weergave kan opleveren. De[`AddLayerMask`](../layer/addlayermask/) methode moet daarvoor worden gebruikt.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Haalt of stelt de juiste laagmaskerpositie in. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Haalt of stelt de maskerpositie van de bovenste laag in. |

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* montage [Aspose.PSD](../../)


