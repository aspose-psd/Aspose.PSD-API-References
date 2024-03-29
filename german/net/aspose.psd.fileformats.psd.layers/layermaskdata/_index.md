---
title: Class LayerMaskData
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData klas. Definiert die Basisklasse LayerMaskData die Informationen über die Ebenenmaskendaten in der PSDDatei enthält. Sie kann dabei helfen Adobe PhotoshopDateien programmgesteuert zu ändern und die Bearbeitung des PSDFormats zu automatisieren. Wenn die Ebene nur eine Rastermaske hat enthalten die ImageData das Raster Maskendatenbytes. Wenn die Ebene nur eine Vektormaske hat enthalten die ImageData die gerasterten zwischengespeicherten Datenbytes der Vektormaske. Wenn die Ebene sowohl Ebenen als auch Vektormasken hat enthalten die ImageData die Rastermaske und die gerasterte Vektormaske kombiniert. DerImageDataBytes Länge sollte gleich Breite  Höhe seinMaskRectangle properties. Beachten Sie dass das Entfernen / Hinzufügen / Aktualisieren der LayerMaskData nicht ausreicht um korrekt zu speichern  da Kanäle nicht aktualisiert werden obwohl es möglicherweise eine korrekte Wiedergabe liefert. DieAddLayerMask Methode sollte dafür verwendet werden.
type: docs
weight: 2240
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD-Datei enthält. Sie kann dabei helfen, Adobe® Photoshop®-Dateien programmgesteuert zu ändern und die Bearbeitung des PSD-Formats zu automatisieren. Wenn die Ebene nur eine Rastermaske hat, enthalten die ImageData das Raster Maskendatenbytes. Wenn die Ebene nur eine Vektormaske hat, enthalten die ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske. Wenn die Ebene sowohl Ebenen- als auch Vektormasken hat, enthalten die ImageData die Rastermaske und die gerasterte Vektormaske kombiniert. Der[`ImageData`](./imagedata/)Bytes Länge sollte gleich Breite * Höhe sein[`MaskRectangle`](./maskrectangle/) properties. Beachten Sie, dass das Entfernen / Hinzufügen / Aktualisieren der LayerMaskData nicht ausreicht, um korrekt zu speichern , da Kanäle nicht aktualisiert werden; obwohl es möglicherweise eine korrekte Wiedergabe liefert. Die[`AddLayerMask`](../layer/addlayermask/) Methode sollte dafür verwendet werden.

```csharp
public abstract class LayerMaskData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Ruft die Maskenposition der unteren Ebene ab oder legt sie fest. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Ruft die Größe der Maskendaten der Ebenenmaske ab. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Ruft die Standardfarbe ab oder legt sie fest. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Ruft die Ebenenmasken-Flags ab oder setzt sie. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Ruft die Ebenenmaskendaten (oder die kombinierte / endgültige Maske, wenn eine Vektormaske vorhanden ist) in der PSD-Datei ab oder legt sie fest. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Ruft die Position der linken Ebenenmaske ab oder legt sie fest. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Holt oder setzt die Maske[`Rectangle`](../../aspose.psd/rectangle/)der Ebenenmaske in der PSD-Datei. Es nimmt linke, rechte, obere und untere Eigenschaften und erstellt[`Rectangle`](../../aspose.psd/rectangle/) |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Ruft die Position der richtigen Ebenenmaske ab oder legt sie fest. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Ruft die Maskenposition der obersten Ebene ab oder legt sie fest. |

### Siehe auch

* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Montage [Aspose.PSD](../../)


