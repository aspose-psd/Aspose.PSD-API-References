---
title: Class LayerMaskDataShort
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort klas. Definiert die LayerMaskDataShortKlasse die Informationen über die Maskendaten in der PSDDatei layer enthält wenn die Ebene nur eine Raster oder Vektormaske aber nicht beides hat. Ansonsten ALayerMaskDataFull verwendet wird. Wenn der Layer nur eine Rastermaske hat enthält ImageData die Datenbytes der Rastermaske. Wenn der Layer nur eine Vektormaske hat enthält ImageData die gerasterten zwischengespeicherten Datenbytes der Vektormaske. DieImageDataBytes Länge sollte gleich Breite  Höhe seinMaskRectangle Eigenschaften.
type: docs
weight: 2260
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Definiert die LayerMaskDataShort-Klasse, die Informationen über die Maskendaten in der PSD-Datei layer enthält, wenn die Ebene nur eine Raster- oder Vektormaske, aber nicht beides hat. Ansonsten A[`LayerMaskDataFull`](../layermaskdatafull/) verwendet wird. Wenn der Layer nur eine Rastermaske hat, enthält ImageData die Datenbytes der Rastermaske. Wenn der Layer nur eine Vektormaske hat, enthält ImageData die gerasterten (zwischengespeicherten) Datenbytes der Vektormaske. Die[`ImageData`](../layermaskdata/imagedata/)Bytes Länge sollte gleich Breite * Höhe sein[`MaskRectangle`](../layermaskdata/maskrectangle/) Eigenschaften.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Default_Constructor |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Ruft die Ebenenmaskenfüllung ab oder legt sie fest. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Ruft die Position der richtigen Ebenenmaske ab oder legt sie fest. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Ruft die Maskenposition der obersten Ebene ab oder legt sie fest. |

### Siehe auch

* class [LayerMaskData](../layermaskdata/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Montage [Aspose.PSD](../../)


