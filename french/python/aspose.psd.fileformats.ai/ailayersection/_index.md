---
title: "AiLayerSection Classe"
type: docs
weight: 50
url: /fr/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bleu | int | r/w | Obtient ou définit le composant couleur bleu. |
| color_index | int | r/w | Obtient ou définit l'index de la couleur.<br/>            Cet argument peut prendre des valeurs entre –1 et 26. Chaque entier<br/>            représente une couleur qui peut être assignée au calque à des fins<br/>            d'identification par l'utilisateur. |
| color_number | int | r/w | Obtient ou définit le numéro de couleur. -1 est la valeur de couleur personnalisée provenant des propriétés Rouge, Vert, Bleu.<br/>            Spécifie le paramètre de couleur du calque. |
| dim_value | int | r/w | Obtient ou définit la valeur d'assombrissement en pourcentage.<br/>            Réduit l'intensité des images liées et des images bitmap contenues dans le calque au pourcentage spécifié. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| vert | int | r/w | Obtient ou définit le composant vert de la couleur. |
| has_multi_layer_masks | bool | r/w | Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches. |
| is_images_dimmed | bool | r/w | Obtient ou définit une valeur indiquant si ce calque est atténué.<br/>            Réduit l'intensité des images liées et des images bitmap contenues dans le calque. |
| is_locked | bool | r/w | Obtient ou définit une valeur indiquant si ce calque est verrouillé.<br/>            Empêche les modifications de l'élément. |
| is_preview | bool | r/w | Obtient ou définit une valeur indiquant si ce calque est en aperçu.<br/>            Affiche le dessin contenu dans le calque en couleur au lieu de le présenter sous forme de contours. |
| is_printed | bool | r/w | Obtient ou définit une valeur indiquant si ce calque est imprimé.<br/>            Rend le dessin contenu dans le calque imprimable si vrai. |
| is_shown | bool | r/w | Obtient ou définit une valeur indiquant si ce calque est affiché.<br/>            Affiche tout le dessin contenu dans le calque sur le plan de travail si vrai. |
| is_template | bool | r/w | Obtient ou définit une valeur indiquant si ce calque est un calque modèle. |
| name | chaîne | r/w | Obtient ou définit le nom du calque.<br/>            Spécifie le nom de l'élément tel qu'il apparaît dans le panneau Calques. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Obtient les images raster. |
| rouge | int | r/w | Obtient ou définit le composant rouge de la couleur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Ajoute l'image raster. |
| [get_data()](#get_data__2) | Obtient les données de chaîne. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Ajoute l'image raster.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | L'image raster. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Obtient les données de chaîne.

**Returns**

| Type | Description |
| :- | :- |
| chaîne | Les données de chaîne de la section |


