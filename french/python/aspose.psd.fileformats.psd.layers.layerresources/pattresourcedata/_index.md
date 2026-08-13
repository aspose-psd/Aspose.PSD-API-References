---
title: "Classe PattResourceData"
type: docs
weight: 780
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/
---

**Summary:** The class to store the pattern data for [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResourceData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResourceData()](#PattResourceData__1) | Initialise une nouvelle instance de la classe PattResourceData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| hauteur | short | r | Obtient la hauteur. |
| image_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r | Obtient le mode d'image. |
| longueur | int | r | Obtient la longueur du motif. |
| name | chaîne | r/w | Obtient ou définit le nom. |
| pattern_data | int | r | Obtient les données du motif. |
| pattern_id | chaîne | r/w | Obtient ou définit l'identifiant du motif. |
| version | int | r | Obtient la version. |
| width | short | r | Obtient la largeur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container)](#save_stream_container_1) | Enregistre les données du motif. |
| [set_pattern(pixels, bounds)](#set_pattern_pixels_bounds_2) | Définit le motif. |


### Constructor: PattResourceData() {#PattResourceData__1}


```
 PattResourceData() 
```

Initialise une nouvelle instance de la classe PattResourceData

### Method: save(stream_container) {#save_stream_container_1}


```
 save(stream_container) 
```

Enregistre les données du motif.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |

### Method: set_pattern(pixels, bounds) {#set_pattern_pixels_bounds_2}


```
 set_pattern(pixels, bounds) 
```

Définit le motif.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pixels | int | Les pixels. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Les limites. |

