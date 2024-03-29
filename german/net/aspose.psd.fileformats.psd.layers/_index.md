---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD für .NET-API-Referenz
description: Der Namensraum enthält Ebenen im PSDDateiformat.
type: docs
weight: 210
url: /de/net/aspose.psd.fileformats.psd.layers/
---
Der Namensraum enthält Ebenen im PSD-Dateiformat.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BlendRange](./blendrange/) | Der Mischungsbereich. |
| [ChannelInformation](./channelinformation/) | Die Kanalinformationen. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Der globale Ebenenmaskenabschnitt. |
| [Layer](./layer/) | Die PSD-Ebene. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Die Layer-Mischbereichsdaten. |
| [LayerGroup](./layergroup/) | Gruppenebenenklasse |
| [LayerHashCalculator](./layerhashcalculator/) | Hash-Rechner für PSD-Layer. Es kann verwendet werden, um gleiche oder unterschiedliche Ebenen in verschiedenen PSD-Dateien zu finden |
| [LayerMaskData](./layermaskdata/) | Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD-Datei enthält. Sie kann dabei helfen, Adobe® Photoshop®-Dateien programmgesteuert zu ändern und die Bearbeitung des PSD-Formats zu automatisieren. Wenn die Ebene nur eine Rastermaske hat, enthalten die ImageData das Raster Maskendatenbytes. Wenn die Ebene nur eine Vektormaske hat, enthalten die ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske. Wenn die Ebene sowohl Ebenen- als auch Vektormasken hat, enthalten die ImageData die Rastermaske und die gerasterte Vektormaske kombiniert. Der[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)Bytes Länge sollte gleich Breite * Höhe sein[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Beachten Sie, dass das Entfernen / Hinzufügen / Aktualisieren der LayerMaskData nicht ausreicht, um korrekt zu speichern , da Kanäle nicht aktualisiert werden; obwohl es möglicherweise eine korrekte Wiedergabe liefert. Die[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) Methode sollte dafür verwendet werden. |
| [LayerMaskDataFull](./layermaskdatafull/) | Definiert die LayerMaskDataFull-Klasse, die Informationen zu den Maskendaten in der PSD-Datei layer enthält, wenn die Ebene sowohl Ebenen- als auch Vektormasken enthält. Ansonsten A[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) wird verwendet. Die ImageData enthält die Rastermaske und die gerasterte Vektormaske kombiniert. Die ImageData-Bytelänge sollte gleich MaskRectangle.Width * MaskRectangle.Height-Eigenschaften sein. |
| [LayerMaskDataShort](./layermaskdatashort/) | Definiert die LayerMaskDataShort-Klasse, die Informationen über die Maskendaten in der PSD-Datei layer enthält, wenn die Ebene nur eine Raster- oder Vektormaske, aber nicht beides hat. Ansonsten A[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) verwendet wird. Wenn der Layer nur eine Rastermaske hat, enthält ImageData die Datenbytes der Rastermaske. Wenn der Layer nur eine Vektormaske hat, enthält ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske. Die[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)Bytes Länge sollte gleich Breite * Höhe sein[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) Eigenschaften. |
| [LayerResource](./layerresource/) | Repräsentiert Schichtinformationen. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Definieren Sie die Layer-Ressourcen-Registrierung für das Laden von PSD-Dateien. |
| [LinkedLayersManager](./linkedlayersmanager/) | Managerklasse für verknüpfte Ebenen. |
| [SectionDividerLayer](./sectiondividerlayer/) | Die Schnittteilerebene zur Markierung der Grenzen des Ordners (Ebenengruppe). |
| [TextLayer](./textlayer/) | Die Textebenenklasse |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Basisschnittstelle für Fülleinstellungen |
| [ILayerResourceLoader](./ilayerresourceloader/) | Der Layer-Ressourcenlader. |
## Aufzählung

| Aufzählung | Beschreibung |
| --- | --- |
| [LayerFlags](./layerflags/) | Die Layer-Flags |
| [LayerMaskFlags](./layermaskflags/) | Die Ebenenmaske flags |


