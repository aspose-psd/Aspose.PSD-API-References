---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Der Namespace enthält PSD-Datei-Format-Ebenen"
type: docs
weight: 230
url: /de/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
Der Namespace enthält PSD-Dateiformat-Ebenen.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | Die Artboard-Ebenenklasse. |
| [BlendRange](./blendrange/) | Der Mischbereich. |
| [ChannelInformation](./channelinformation/) | Die Kanalinformationen. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Der globale Ebenenmaskenabschnitt. |
| [Layer](./layer/) | Die PSD-Ebene. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Die Daten der Ebenen‑Blending‑Bereiche. |
| [LayerGroup](./layergroup/) | Klasse für Gruppenebene |
| [LayerHashCalculator](./layerhashcalculator/) | Hash‑Rechner für PSD‑Ebenen. Er kann verwendet werden, um gleiche oder unterschiedliche Ebenen in verschiedenen PSD‑Dateien zu finden. |
| [LayerMaskData](./layermaskdata/) | Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD‑Datei enthält. Sie kann dabei helfen, Adobe® Photoshop®‑Dateien programmgesteuert zu ändern und die Bearbeitung des PSD‑Formats zu automatisieren. Wenn die Ebene nur eine Rastermaske hat, enthält ImageData die Bytes der Rastermaskendaten. Wenn die Ebene nur eine Vektormaske hat, enthält ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske. Wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat, enthält ImageData die kombinierte Rastermaske und die gerasterte Vektormaske. Die Länge der [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) Bytes sollte gleich Width * Height der Eigenschaften von [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) sein. Beachten Sie, dass das bloße Entfernen/Hinzufügen/Aktualisieren von LayerMaskData nicht ausreicht, um korrekt zu speichern, da Kanäle nicht aktualisiert werden; es kann jedoch eine korrekte Darstellung ermöglichen. Die Methode [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) sollte dafür verwendet werden. |
| [LayerMaskDataFull](./layermaskdatafull/) | Definiert die Klasse LayerMaskDataFull, die Informationen über die Maskendaten in der PSD‑Dateiebene enthält, wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat. Andernfalls wird [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) verwendet. ImageData enthält die kombinierte Rastermaske und die gerasterte Vektormaske. Die Länge der ImageData‑Bytes sollte gleich den Eigenschaften MaskRectangle.Width * MaskRectangle.Height sein. |
| [LayerMaskDataShort](./layermaskdatashort/) | Definiert die Klasse LayerMaskDataShort, die Informationen über die Maskendaten in der PSD‑Dateiebene enthält, wenn die Ebene nur eine Raster‑ oder Vektormaske, jedoch nicht beide, hat. Andernfalls wird [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) verwendet. Wenn die Ebene nur eine Rastermaske hat, enthält ImageData die Bytes der Rastermaskendaten. Wenn die Ebene nur eine Vektormaske hat, enthält ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske. Die Länge der [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) Bytes sollte gleich Width * Height der Eigenschaften von [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) sein. |
| [LayerResource](./layerresource/) | Stellt Ebeneninformationen dar. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definiert das Ressourcenregister für Ebenen beim Laden von PSD‑Dateien. |
| [LinkedLayersManager](./linkedlayersmanager/) | Klasse für die Verwaltung verknüpfter Ebenen. |
| [SectionDividerLayer](./sectiondividerlayer/) | Die Abschnittstrenn‑Ebene, um die Grenzen des Ordners (Ebenengruppe) zu markieren. |
| [ShapeLayer](./shapelayer/) | Formebene. Kapselt die Logik der Arbeit mit Formebenen und zugehörigen Ressourcen. |
| [TextLayer](./textlayer/) | Die Text‑Ebenenklasse |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Basisschnittstelle für Füllungseinstellungen |
| [ILayerResourceLoader](./ilayerresourceloader/) | Der Ebenen‑Ressourcen‑Lader. |
| [IShapeLayer](./ishapelayer/) | Beschreibt die Eigenschaften der Formebene. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [LayerFlags](./layerflags/) | Die Ebenen‑Flags |
| [LayerMaskFlags](./layermaskflags/) | Die Ebenenmasken‑Flags |


