---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD för .NET API-referens
description: Namnutrymmet innehåller lager i PSDfilformat.
type: docs
weight: 210
url: /sv/net/aspose.psd.fileformats.psd.layers/
---
Namnutrymmet innehåller lager i PSD-filformat.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BlendRange](./blendrange/) | Blandningsintervallet. |
| [ChannelInformation](./channelinformation/) | Kanalinformationen. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Den globala lagermasksektionen. |
| [Layer](./layer/) | PSD-lagret. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Data för lagerblandningsintervall. |
| [LayerGroup](./layergroup/) | Grupplager klass |
| [LayerHashCalculator](./layerhashcalculator/) | Hash-kalkylator för PSD-lager. Den kan användas för att hitta lika eller olika lager i olika PSD-filer |
| [LayerMaskData](./layermaskdata/) | Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSD-filen. Det kan hjälpa till att modifiera Adobe® Photoshop®-filer programmatiskt och automatisera redigering av PSD-format. Om lagret endast har en rastermask innehåller ImageData rastret mask data bytes. Om lagret endast har en vektormask innehåller ImageData vektormasken rastrerade (cachelagrade) databytes. Om lagret har både lager- och vektormasker innehåller ImageData rastermasken och den rastrerade vektormasken kombinerat. De[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)bytes längd ska vara lika Bredd * Höjd på[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Observera att det inte räcker att bara ta bort / lägga till / uppdatera LayerMaskData för att spara korrekt eftersom kanaler inte uppdateras; även om det kan ge korrekt rendering. The[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) metod ska användas för det. |
| [LayerMaskDataFull](./layermaskdatafull/) | Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD-filen layer när lagret har både lager- och vektormasker. Annars, a[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) används. ImageData innehåller rastermasken och den rastrerade vektormasken kombinerat. ImageData-bytelängden ska vara lika med MaskRectangle.Width * MaskRectangle.Height properties. |
| [LayerMaskDataShort](./layermaskdatashort/) | Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD-filen layer när lagret bara har raster- eller vektormask men inte båda. Annars, a[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) används. Om lagret endast har en rastermask innehåller ImageData rastermaskdatabytes. Om lagret endast har en vektormask innehåller ImageData vektormasken rasteriserade (cachade) databytes. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)bytes längd ska vara lika Bredd * Höjd på[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) egenskaper. |
| [LayerResource](./layerresource/) | Representerar lagerinformation. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definiera lagerresursregistret för PSD-filer som laddas. |
| [LinkedLayersManager](./linkedlayersmanager/) | Manager class för länkade lager. |
| [SectionDividerLayer](./sectiondividerlayer/) | Sektionsavdelarlagret för att markera gränserna för mappen (lagergrupp). |
| [TextLayer](./textlayer/) | Textlagret class |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Basgränssnitt för fyllningsinställningar |
| [ILayerResourceLoader](./ilayerresourceloader/) | Lagerresursladdningen. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [LayerFlags](./layerflags/) | Lagret flaggor |
| [LayerMaskFlags](./layermaskflags/) | Lagermasken flaggor |


