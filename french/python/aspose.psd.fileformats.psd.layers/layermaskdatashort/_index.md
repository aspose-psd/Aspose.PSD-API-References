---
title: "Classe LayerMaskDataShort"
type: docs
weight: 990
url: /fr/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Initialise une nouvelle instance de la classe LayerMaskDataShort |
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
| remplissage | short | r/w | Obtient ou définit le remplissage du masque de calque. |
| droite | int | r/w | Obtient ou définit la position du masque de calque droit. |
| haut | int | r/w | Obtient ou définit la position du masque de calque supérieur. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Initialise une nouvelle instance de la classe LayerMaskDataShort

