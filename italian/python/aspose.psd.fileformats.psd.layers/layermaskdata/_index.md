---
title: "LayerMaskData Classe"
type: docs
weight: 970
url: /it/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Ottiene o imposta la posizione inferiore della maschera del livello. |
| data_size | int | r | Ottiene la dimensione dei dati della maschera del livello. |
| default_color | byte | r/w | Ottiene o imposta il colore predefinito. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Ottiene o imposta i flag della maschera del livello. |
| image_data | byte | r/w | Ottiene o imposta i dati della maschera del livello (o la maschera combinata / finale se è presente una maschera vettoriale) nel file PSD. |
| sinistra | int | r/w | Ottiene o imposta la posizione sinistra della maschera del livello. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Ottiene o imposta la [Rectangle](/psd/python-net/aspose.psd/rectangle/) della maschera del livello nel file PSD.<br/>            Prende le proprietà left, right, top e bottom e crea una [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| destra | int | r/w | Ottiene o imposta la posizione destra della maschera del livello. |
| superiore | int | r/w | Ottiene o imposta la posizione superiore della maschera del livello. |


