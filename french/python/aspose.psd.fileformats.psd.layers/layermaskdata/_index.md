---
title: "Classe LayerMaskData"
type: docs
weight: 970
url: /fr/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bottom | int | r/w | Obtient ou définit la position du masque de calque inférieur. |
| data_size | int | r | Obtient la taille des données du masque de calque. |
| default_color | byte | r/w | Obtient ou définit la couleur par défaut. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Obtient ou définit les indicateurs du masque de calque. |
| image_data | byte | r/w | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD. |
| gauche | int | r/w | Obtient ou définit la position du masque de calque gauche. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtient ou définit le masque [Rectangle](/psd/python-net/aspose.psd/rectangle/) du masque de calque dans le fichier PSD.<br/>            Il prend les propriétés left, right, top et bottom et crée un [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| droite | int | r/w | Obtient ou définit la position du masque de calque droit. |
| haut | int | r/w | Obtient ou définit la position du masque de calque supérieur. |


