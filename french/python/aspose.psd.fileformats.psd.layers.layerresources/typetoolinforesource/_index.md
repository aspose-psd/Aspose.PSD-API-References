---
title: "Classe TypeToolInfoResource"
type: docs
weight: 1000
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Initialise une nouvelle instance de la classe TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| a_component | short | r/w | Obtient ou définit un composant. |
| b_component | short | r/w | Obtient ou définit le composant b. |
| character_count | int | r/w | Obtient ou définit le nombre de caractères. |
| color_space_value | short | r/w | Obtient ou définit la valeur de l'espace couleur. |
| font_version | short | r/w | Obtient ou définit la version de la police. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Obtient ou définit les polices. |
| fonts_count | short | r | Obtient le nombre de polices. |
| g_component | short | r/w | Obtient ou définit le composant g. |
| horizontal_placement | int | r/w | Obtient ou définit le placement horizontal. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| line_count | short | r | Obtient le nombre de lignes. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Obtient ou définit les lignes. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| r_component | short | r/w | Obtient ou définit le composant r. |
| scale_factor | int | r/w | Obtient ou définit le facteur d'échelle. |
| selection_end | int | r/w | Obtient ou définit la fin de la sélection. |
| selection_start | int | r/w | Obtient ou définit le début de la sélection. |
| signature | int | r | Obtient la signature. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Obtient ou définit les styles de police. |
| styles_count | short | r | Obtient le nombre de styles. |
| transform_matrix | double | r/w | Obtient ou définit la matrice de transformation. |
| type_value | short | r/w | Obtient ou définit la valeur du type. |
| version | short | r/w | Obtient ou définit la version. |
| vertical_placement | int | r/w | Obtient ou définit le placement vertical. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre le conteneur de flux spécifié. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Initialise une nouvelle instance de la classe TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| psd_version | int | La version PSD. |

