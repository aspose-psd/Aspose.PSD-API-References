---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /sv/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Klass** | **Beskrivning** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Artboard-lagerklassen. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | Blandningsintervallet. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Kanalinformationen. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | Den globala lagermasksektionen. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Basgränssnitt för fyllningsinställningar |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Lagerresursläsaren. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Beskriver egenskaperna för Shape layer. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | psd-lagret. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Data för lagerblandningsintervall. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Grupplagerklass |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Hash-kalkylator för PSD-lager. Den kan användas för att hitta lika eller olika lager i olika PSD-filer. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Definierar basklassen LayerMaskData som innehåller information om lagermaskdata i PSD-filen.<br/>            Den kan hjälpa till att programatiskt modifiera Adobe® Photoshop®-filer och automatisera redigering av PSD-format.<br/>            Om lagret endast har en rastermask innehåller ImageData rastermaskens data‑byte.<br/>            Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) data‑byte.<br/>            Om lagret har både lager‑ och vektormasker innehåller ImageData både rastermasken och den rasteriserade vektormasken kombinerade.<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) byte‑längden bör vara lika med Width * Height för [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) egenskaper.<br/>            Observera att enbart borttagning / tillägg / uppdatering av LayerMaskData inte är tillräckligt för korrekt sparning<br/>            eftersom kanalerna inte uppdateras; även om det kan ge korrekt rendering.<br/>            Metoden [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) bör användas för detta. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Definierar klassen LayerMaskDataFull som innehåller information om maskdata i PSD-filens lager<br/>            när lagret har både lager‑ och vektormasker. Annars används en [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/).<br/>            ImageData innehåller rastermasken och den rasteriserade vektormasken kombinerade.<br/>            ImageData‑byte‑längden bör vara lika med MaskRectangle.Width * MaskRectangle.Height‑egenskaperna. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Definierar klassen LayerMaskDataShort som innehåller information om maskdata i PSD-filens lager<br/>            när lagret endast har raster‑ eller vektormask men inte båda. Annars används en [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/).<br/>            Om lagret endast har en rastermask innehåller ImageData rastermaskens data‑byte.<br/>            Om lagret endast har en vektormask innehåller ImageData vektormaskens rasteriserade (cachade) data‑byte.<br/>            [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) byte‑längden bör vara lika med Width * Height för [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) egenskaperna. |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Representerar lagerinformation. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Definiera lagrets resurserregister för inläsning av PSD-filer. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Klass för hantering av länkade lager. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Avsnittsdelningslagret för att markera gränserna för mappen (lagergrupp). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape layer. Inkapslar logiken för arbete med Shape layer och relaterade resurser. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Textlagerklassen |
## **Enumerations**
| **Enumeration** | **Beskrivning** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Lagrets flaggor |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Lagermaskens flaggor |
