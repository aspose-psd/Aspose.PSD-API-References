---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Namnområdet innehåller lager för PSD-filformatet"
type: docs
weight: 230
url: /sv/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
Namnutrymmet innehåller PSD-filformatlager.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | Artboard-lagerklassen. |
| [BlendRange](./blendrange/) | Blandningsintervallet. |
| [ChannelInformation](./channelinformation/) | Kanalinformationen. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Det globala lagermaskavsnittet. |
| [Layer](./layer/) | PSD‑lagret. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Data för lagerblandningsintervall. |
| [LayerGroup](./layergroup/) | Klass för grupplager |
| [LayerHashCalculator](./layerhashcalculator/) | Hash‑kalkylator för PSD‑lager. Den kan användas för att hitta lika eller olika lager i olika PSD‑filer. |
| [LayerMaskData](./layermaskdata/) | Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSD‑filen. Den kan hjälpa till att programatiskt modifiera Adobe® Photoshop®‑filer och automatisera redigering av PSD‑formatet. Om lagret endast har en rastermask innehåller ImageData rastermaskens data‑byte. Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) data‑byte. Om lagret har både lager‑ och vektormasker innehåller ImageData både rastermasken och den rasteriserade vektormasken kombinerade. Längden på byte‑arrayen för [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) ska vara lika med Bredd * Höjd för egenskaperna i [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). Observera att enbart ta bort / lägga till / uppdatera LayerMaskData inte är tillräckligt för korrekt sparande eftersom kanalerna inte uppdateras; även om det kan ge korrekt rendering. Metoden [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) bör användas för detta. |
| [LayerMaskDataFull](./layermaskdatafull/) | Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD‑lager när lagret har både lager‑ och vektormasker. Annars används en [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/). ImageData innehåller rastermasken och den rasteriserade vektormasken kombinerade. Längden på ImageData‑byten ska vara lika med egenskaperna MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD‑lager när lagret endast har en raster‑ eller vektormask men inte båda. Annars används en [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/). Om lagret endast har en rastermask innehåller ImageData rastermaskens data‑byte. Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) data‑byte. Längden på byte‑arrayen för [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) ska vara lika med Bredd * Höjd för egenskaperna i [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | Representerar lagerinformation. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definiera lagrets resurserregister för inläsning av PSD‑filer. |
| [LinkedLayersManager](./linkedlayersmanager/) | Klass för hantering av länkade lager. |
| [SectionDividerLayer](./sectiondividerlayer/) | Avsnittsskiljelager för att markera gränserna för mappen (lagergupp). |
| [ShapeLayer](./shapelayer/) | Formlager. Inkapslar logiken för arbete med Formlager och relaterade resurser. |
| [TextLayer](./textlayer/) | Klassen för textlager. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Basgränssnitt för fyllningsinställningar |
| [ILayerResourceLoader](./ilayerresourceloader/) | Lagerresursläsaren. |
| [IShapeLayer](./ishapelayer/) | Beskriver egenskaperna för Formlager. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [LayerFlags](./layerflags/) | Lagerflaggor |
| [LayerMaskFlags](./layermaskflags/) | Lagermaskflaggor |


