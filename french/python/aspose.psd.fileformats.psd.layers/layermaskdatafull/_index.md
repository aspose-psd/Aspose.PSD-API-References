---
title: "Classe LayerMaskDataFull"
type: docs
weight: 980
url: /fr/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Initialise une nouvelle instance de la classe LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Obtient ou définit la couleur d'arrière-plan. |
| bottom | int | r/w | Obtient ou définit la position du masque de calque inférieur. |
| data_size | int | r | Obtient la taille des données du masque de calque. |
| default_color | byte | r/w | Obtient ou définit la couleur par défaut. |
| enclosing_bottom | int | r/w | Obtient ou définit la position du masque raster inférieur englobant dans le calque d'image PSD. |
| enclosing_left | int | r/w | Obtient ou définit la position du masque raster gauche englobant dans le calque du fichier PSD. |
| enclosing_right | int | r/w | Obtient ou définit la position du masque raster droit englobant dans le calque du fichier PSD. |
| enclosing_top | int | r/w | Obtient ou définit la position supérieure englobante du masque raster dans le calque d'image PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Obtient ou définit les indicateurs du masque de calque. |
| image_data | byte | r/w | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il existe un masque vectoriel) dans le fichier PSD. |
| gauche | int | r/w | Obtient ou définit la position du masque de calque gauche. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtient ou définit le masque [Rectangle](/psd/python-net/aspose.psd/rectangle/) du masque de calque dans le fichier PSD.<br/>            Il prend les propriétés left, right, top et bottom et crée un [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Obtient ou définit les indicateurs du masque de calque utilisés pour le masque utilisateur / raster. Pour le masque vectoriel, la propriété Flags est utilisée. |
| droite | int | r/w | Obtient ou définit la position du masque de calque droit. |
| haut | int | r/w | Obtient ou définit la position du masque de calque supérieur. |
| user_mask_data | byte | r/w | Obtient ou définit les données du masque utilisateur (raster) d'un calque dans le fichier PSD. (Il existe un masque vectoriel rasterisé dans la propriété MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtient ou définit le rectangle du masque utilisateur (englobant) dans le calque d'image PSD. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Initialise une nouvelle instance de la classe LayerMaskDataFull

