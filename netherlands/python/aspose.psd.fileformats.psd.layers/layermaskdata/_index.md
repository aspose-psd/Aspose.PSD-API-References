---
title: "LayerMaskData Klasse"
type: docs
weight: 970
url: /nl/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bottom | int | r/w | Haalt of stelt de positie van het onderste laagmasker in. |
| data_size | int | r | Haalt de grootte van de laagmaskergegevens op. |
| default_color | byte | r/w | Haalt of stelt de standaardkleur in. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Haalt of stelt de vlaggen van het laagmasker in. |
| image_data | byte | r/w | Haalt of stelt de laagmaskergegevens (of gecombineerde/eindmasker als er een vectormasker is) in het PSD‑bestand in. |
| left | int | r/w | Haalt of stelt de positie van het linker laagmasker in. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Haalt of stelt het masker [Rectangle](/psd/python-net/aspose.psd/rectangle/) van het laagmasker in het PSD‑bestand.<br/>            Het neemt de eigenschappen left, right, top en bottom en maakt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| right | int | r/w | Haalt of stelt de positie van het rechter laagmasker in. |
| boven | int | r/w | Haalt of stelt de positie van het bovenste laagmasker in. |


