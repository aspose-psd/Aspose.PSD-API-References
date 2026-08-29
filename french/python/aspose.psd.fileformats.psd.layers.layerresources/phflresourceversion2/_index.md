---
title: "PhflResourceVersion2 Classe"
type: docs
weight: 800
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Initialise une nouvelle instance de la classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Initialise une nouvelle instance de la classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| color_space | short | r | Obtient l'espace couleur. |
| component_a | short | r/w | Obtient ou définit le composant A de la couleur |
| component_b | short | r/w | Obtient ou définit le composant B |
| component_l | short | r/w | Obtient ou définit le composant L de la couleur |
| density | int | r/w | Obtient ou définit la densité. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| preserve_luminosity | bool | r/w | Obtient ou définit une valeur indiquant si [preserve luminosity]. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| version | short | r | Obtient la version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Obtient la couleur. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Définit la couleur RVB. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Initialise une nouvelle instance de la classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Initialise une nouvelle instance de la classe [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Obtient la couleur.

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | La couleur RVB |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Définit la couleur RVB.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | La couleur. |

