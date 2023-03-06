---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD voor .NET API-referentie
description: De naamruimte bevat lagen in PSDbestandsindeling.
type: docs
weight: 210
url: /nl/net/aspose.psd.fileformats.psd.layers/
---
De naamruimte bevat lagen in PSD-bestandsindeling.

## Klassen

| Klas | Beschrijving |
| --- | --- |
| [BlendRange](./blendrange/) | Het overvloeibereik. |
| [ChannelInformation](./channelinformation/) | De kanaalinformatie. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | De globale laagmaskersectie. |
| [Layer](./layer/) | De psd-laag. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | De gegevens van het overvloeibereik van de laag. |
| [LayerGroup](./layergroup/) | Groepslaag klasse |
| [LayerHashCalculator](./layerhashcalculator/) | Hash Calculator voor PSD-lagen. Het kan worden gebruikt om gelijken of verschillende lagen in verschillende PSD-bestanden te vinden |
| [LayerMaskData](./layermaskdata/) | Definieert de LayerMaskData-basisklasse die informatie bevat over de laagmaskergegevens in het PSD-bestand. Het kan helpen om Adobe® Photoshop®-bestanden programmatisch te wijzigen en het bewerken van PSD-indeling te automatiseren. Als de laag alleen een rastermasker heeft, bevat ImageData het raster mask data bytes. Als de laag alleen een vectormasker heeft, bevat de ImageData de vectormasker gerasterde (cached) databytes. Als de laag zowel laag- als vectormaskers heeft, bevat ImageData het gecombineerde rastermasker en het gerasterde vectormasker. De[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)bytes lengte moet gelijk zijn Breedte * Hoogte van[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Merk op dat alleen het verwijderen / toevoegen / bijwerken van de LayerMaskData niet voldoende is voor correct opslaan omdat kanalen niet worden bijgewerkt; hoewel het een correcte weergave kan opleveren. De[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) methode moet daarvoor worden gebruikt. |
| [LayerMaskDataFull](./layermaskdatafull/) | Definieert de klasse LayerMaskDataFull die informatie bevat over de maskergegevens in het PSD-bestand layer wanneer de laag zowel laag- als vectormaskers heeft. Anders, een[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) wordt gebruikt. De ImageData bevat het gecombineerde rastermasker en het gerasterde vectormasker. De lengte van de ImageData-bytes moet gelijk zijn MaskRectangle.Width * MaskRectangle.Height-eigenschappen. |
| [LayerMaskDataShort](./layermaskdatashort/) | Definieert de klasse LayerMaskDataShort die informatie bevat over de maskergegevens in het PSD-bestand layer wanneer de laag alleen een raster- of vectormasker heeft, maar niet beide. Anders, een[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) wordt gebruikt. Als de laag alleen een rastermasker heeft, bevat de ImageData de gegevensbytes van het rastermasker. Als de laag alleen een vectormasker heeft, bevat de ImageData de gerasterde (cached) gegevensbytes van het vectormasker. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)bytes lengte moet gelijk zijn Breedte * Hoogte van[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) eigenschappen. |
| [LayerResource](./layerresource/) | Vertegenwoordigt laaginfo. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definieer het laagbronnenregister voor het laden van PSD-bestanden. |
| [LinkedLayersManager](./linkedlayersmanager/) | Beheerklasse gekoppelde lagen. |
| [SectionDividerLayer](./sectiondividerlayer/) | De sectiescheidingslaag om de grenzen van de map (laaggroep) te markeren. |
| [TextLayer](./textlayer/) | De tekstlaag class |
## Interfaces

| Koppel | Beschrijving |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Basisinterface voor vulinstellingen |
| [ILayerResourceLoader](./ilayerresourceloader/) | De laagbronlader. |
## Opsomming

| Opsomming | Beschrijving |
| --- | --- |
| [LayerFlags](./layerflags/) | De laagvlaggen |
| [LayerMaskFlags](./layermaskflags/) | De laagmaskervlaggen |


