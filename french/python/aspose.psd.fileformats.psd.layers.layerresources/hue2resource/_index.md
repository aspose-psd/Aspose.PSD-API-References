---
title: "Classe Hue2Resource"
type: docs
weight: 350
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Initialise une nouvelle instance de la classe [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) . |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Initialise une nouvelle instance de la classe [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| colorize | bool | r/w | Obtient ou définit une valeur indiquant si ce [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) est colorisé. |
| hue | short | r/w | Obtient ou définit la teinte principale. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| lightness | short | r/w | Obtient ou définit la luminosité principale. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Obtient les plages du calque de réglage Teinte/Saturation.<br/>            Les plages dans PS peuvent changer de nom si la plage est modifiée, il faut donc travailler par indice |
| saturation | short | r/w | Obtient ou définit la saturation principale. |
| signature | int | r | Obtient la signature. |
| version | short | r | Obtient la version. La valeur par défaut est 2 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Initialise une nouvelle instance de la classe [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) .

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Initialise une nouvelle instance de la classe [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) .

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

