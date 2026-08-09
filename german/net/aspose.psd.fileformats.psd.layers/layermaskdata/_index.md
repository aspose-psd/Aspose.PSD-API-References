---
title: "Klasse LayerMaskData"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData Klasse. Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD-Datei enthält. Sie kann dabei helfen, Adobe Photoshop‑Dateien programmgesteuert zu ändern und die PSD‑Formatbearbeitung zu automatisieren. Wenn die Ebene nur eine Rastermaske hat, enthält ImageData die Rastermaskendaten‑Bytes. Wenn die Ebene nur eine Vektormaske hat, enthält ImageData die gerasterten, zwischengespeicherten Vektormasken‑Bytes. Wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat, enthält ImageData die Rastermaske und die gerasterte Vektormaske kombiniert. Die Länge der ImageData‑Bytes sollte gleich Width * Height der MaskRectangle‑Eigenschaften sein. Beachten Sie, dass das bloße Entfernen/Hinzufügen/Aktualisieren von LayerMaskData nicht ausreicht, um korrekt zu speichern, da die Kanäle nicht aktualisiert werden, obwohl dies eine korrekte Darstellung ermöglichen kann. Die Methode AddLayerMask sollte dafür verwendet werden."
type: docs
weight: 2440
url: /de/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Definiert die Basisklasse LayerMaskData, die Informationen über die Ebenenmaskendaten in der PSD‑Datei enthält. Sie kann dabei helfen, Adobe® Photoshop®‑Dateien programmgesteuert zu ändern und die PSD‑Formatbearbeitung zu automatisieren. Wenn die Ebene nur eine Rastermaske hat, enthält ImageData die Rastermaskendaten‑Bytes. Wenn die Ebene nur eine Vektormaske hat, enthält ImageData die gerasterten (zwischengespeicherten) Vektormasken‑Bytes. Wenn die Ebene sowohl Ebenen‑ als auch Vektormasken hat, enthält ImageData die Rastermaske und die gerasterte Vektormaske kombiniert. Die [`ImageData`](./imagedata/)‑Bytes‑Länge sollte gleich Width * Height der [`MaskRectangle`](./maskrectangle/)‑Eigenschaften sein. Beachten Sie, dass das bloße Entfernen/Hinzufügen/Aktualisieren von LayerMaskData nicht ausreicht, um korrekt zu speichern, weil die Kanäle nicht aktualisiert werden; obwohl dies eine korrekte Darstellung ermöglichen kann. Die [`AddLayerMask`](../layer/addlayermask/)‑Methode sollte dafür verwendet werden.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Liest oder setzt die rechte Position der Ebenenmaske. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Liest oder setzt die obere Position der Ebenenmaske. |

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


