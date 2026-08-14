---
title: "Klasse LayerMaskData"
type: docs
weight: 970
url: /de/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bottom | int | r/w | Liest oder setzt die Position der unteren Ebenenmaske. |
| data_size | int | r | Liest die Größe der Maskendaten der Ebenenmaske. |
| default_color | byte | r/w | Liest oder setzt die Standardfarbe. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Liest oder setzt die Flags der Ebenenmaske. |
| image_data | byte | r/w | Liest oder setzt die Maskendaten der Ebenenmaske (oder die kombinierte / endgültige Maske, falls ein Vektormaske vorhanden ist) in der PSD‑Datei. |
| left | int | r/w | Liest oder setzt die Position der linken Ebenenmaske. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt das Masken-[Rectangle](/psd/python-net/aspose.psd/rectangle/) der Ebenenmaske in der PSD‑Datei.<br/>            Es verwendet die Eigenschaften left, right, top und bottom und erstellt ein [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| rechts | int | r/w | Liest oder setzt die Position der rechten Ebenenmaske. |
| oben | int | r/w | Liest oder setzt die Position der oberen Ebenenmaske. |


