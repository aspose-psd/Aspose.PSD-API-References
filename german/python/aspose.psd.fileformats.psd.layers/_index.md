---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /de/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Class** | **Beschreibung** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Die Artboard-Layer-Klasse. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | Der Mischbereich. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Die Kanalinformationen. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | Der globale Layer-Maskenabschnitt. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Basis-Schnittstelle für Füllungseinstellungen |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Der Layer-Ressourcenlader. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Beschreibt die Eigenschaften des Shape-Layers. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Der PSD-Layer. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Die Daten der Layer-Blending-Ranges. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Group-Layer-Klasse |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Hash‑Rechner für PSD-Layer. Er kann verwendet werden, um gleiche oder unterschiedliche Layer in verschiedenen PSD-Dateien zu finden |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD-Datei enthält.<br/>            Sie kann helfen, Adobe® Photoshop®‑Dateien programmgesteuert zu ändern und die PSD‑Formatbearbeitung zu automatisieren.<br/>            Wenn die Ebene nur eine Rastermaske hat, enthält ImageData die Bytes der Rastermaskendaten.<br/>            Wenn die Ebene nur eine Vektormaske hat, enthält ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske.<br/>            Wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat, enthält ImageData die kombinierte Rastermaske und die gerasterte Vektormaske.<br/>            Die Bytes‑Länge von [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) sollte gleich Width * Height der Eigenschaften von [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) sein.<br/>            Beachten Sie, dass das bloße Entfernen/Hinzufügen/Aktualisieren von LayerMaskData nicht ausreicht, um korrekt zu speichern,<br/>            weil Kanäle nicht aktualisiert werden; es kann jedoch eine korrekte Darstellung liefern.<br/>            Die Methode [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) sollte dafür verwendet werden. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Definiert die Klasse LayerMaskDataFull, die Informationen über die Maskendaten im PSD-Dateilayer enthält<br/>            wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat. Andernfalls wird ein [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) verwendet.<br/>            ImageData enthält die kombinierte Rastermaske und die gerasterte Vektormaske.<br/>            Die Bytes‑Länge von ImageData sollte gleich den Eigenschaften MaskRectangle.Width * MaskRectangle.Height sein. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Definiert die Klasse LayerMaskDataShort, die Informationen über die Maskendaten im PSD-Dateilayer enthält<br/>            wenn die Ebene nur eine Raster‑ oder Vektormaske, aber nicht beide, hat. Andernfalls wird ein [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) verwendet.<br/>            Hat die Ebene nur eine Rastermaske, enthält ImageData die Bytes der Rastermaskendaten.<br/>            Hat die Ebene nur eine Vektormaske, enthält ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske.<br/>            Die Bytes‑Länge von [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) sollte gleich Width * Height der Eigenschaften von [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) sein. |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Stellt Ebeneninformationen dar. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Definiert das Registry für Layer-Ressourcen zum Laden von PSD-Dateien. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Verknüpfte-Layer-Manager‑Klasse. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Der Abschnittstrennungs-Layer, um die Grenzen des Ordners (Layer-Gruppe) zu markieren. |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape-Layer. Kapselt die Logik der Arbeit mit Shape-Layern und zugehörigen Ressourcen. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Die Text-Layer-Klasse |
## **Enumerations**
| **Enumeration** | **Beschreibung** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Die Ebenen-Flags |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Die Ebenenmasken-Flags |
