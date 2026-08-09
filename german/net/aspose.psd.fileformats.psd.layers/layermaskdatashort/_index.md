---
title: "Klasse LayerMaskDataShort"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort‑Klasse. Definiert die Klasse LayerMaskDataShort, die Informationen über die Maskendaten in der PSD‑Dateiebene enthält, wenn die Ebene nur eine Raster‑ oder Vektormaske, aber nicht beide, hat. Andernfalls wird ein LayerMaskDataFull verwendet. Hat die Ebene nur eine Rastermaske, enthält die ImageData die Rastermaskendaten‑Bytes. Hat die Ebene nur eine Vektormaske, enthält die ImageData die gerasterten, zwischengespeicherten Daten‑Bytes der Vektormaske. Die Länge der ImageData‑Bytes sollte den Eigenschaften Width  Height von MaskRectangle entsprechen."
type: docs
weight: 2460
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Definiert die Klasse LayerMaskDataShort, die Informationen über die Maskendaten in der PSD‑Dateiebene enthält, wenn die Ebene nur eine Raster‑ oder Vektormaske, aber nicht beide, hat. Andernfalls wird ein [`LayerMaskDataFull`](../layermaskdatafull/) verwendet. Hat die Ebene nur eine Rastermaske, enthält die ImageData die Rastermaskendaten‑Bytes. Hat die Ebene nur eine Vektormaske, enthält die ImageData die gerasterten (zwischengespeicherten) Daten‑Bytes der Vektormaske. Die [`ImageData`](../layermaskdata/imagedata/)‑Bytes‑Länge sollte gleich Width * Height von [`MaskRectangle`](../layermaskdata/maskrectangle/)‑Eigenschaften sein.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Initialisiert eine neue Instanz der `LayerMaskDataShort`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Liest oder setzt die Position der unteren Ebenenmaske. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Liest die Größe der Maskendaten der Ebenenmaske. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Liest oder setzt die Standardfarbe. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Liest oder setzt die Flags der Ebenenmaske. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Liest oder setzt die Ebenenmaskendaten (oder kombinierte / finale Maske, falls eine Vektormaske vorhanden ist) in der PSD‑Datei. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Liest oder setzt die linke Position der Ebenenmaske. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Liest oder setzt das Masken-[`Rectangle`](../../aspose.psd/rectangle/) der Ebenenmaske in der PSD‑Datei. Es verwendet die Eigenschaften links, rechts, oben und unten und erzeugt ein [`Rectangle`](../../aspose.psd/rectangle/). |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Liest oder setzt das Ebenenmasken‑Padding. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Liest oder setzt die rechte Position der Ebenenmaske. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Liest oder setzt die obere Position der Ebenenmaske. |

### Siehe auch

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


