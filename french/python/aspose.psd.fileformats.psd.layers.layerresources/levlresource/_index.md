---
title: "Classe LevlResource"
type: docs
weight: 490
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Initialise une nouvelle instance de la classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Initialise une nouvelle instance de la classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Pris en charge dans les modes GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 octets - Version (=2)<br/>            29 * 10 octets - Jeux d’enregistrements de niveau avec 5 entiers courts<br/>            4 octets - En-tête Lvls (Commence à l’index 292)<br/>            2 octets - Version (=3)<br/>            2 octets - Nombre total d’enregistrements de niveau<br/>            10 * (Nombre total - 29)<br/>            La terminaison zéro de la ressource Lvls doit également être repliée pour quatre |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| version | short | r | Obtient la version. La valeur par défaut est 2 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Obtient le canal. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Initialise une nouvelle instance de la classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Initialise une nouvelle instance de la classe [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Pris en charge dans les modes GrayScale, Duotone, RGB, CMYK, Lab<br/>            2 octets - Version (=2)<br/>            29 * 10 octets - Jeux d’enregistrements de niveau avec 5 entiers courts<br/>            4 octets - En-tête Lvls (Commence à l’index 292)<br/>            2 octets - Version (=3)<br/>            2 octets - Nombre total d’enregistrements de niveau<br/>            10 * (Nombre total - 29)<br/>            La terminaison zéro de la ressource Lvls doit également être repliée pour quatre

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Obtient le canal.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |

**Returns**

| Type | Description |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Données de niveau du canal |


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

