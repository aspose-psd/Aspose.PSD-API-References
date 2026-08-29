---
title: "Classe MixrResource"
type: docs
weight: 680
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Initialise une nouvelle instance de la classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            La spécification du format PSD contient la description suivante :<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 couleur RVB ou CMJN plus constante pour les réglages du mixeur. 4 * 2 octets de couleur avec 2 octets de constante. |
| [MixrResource(data)](#MixrResource_data_2) | Initialise une nouvelle instance de la classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            La spécification du format PSD contient la description suivante :<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 couleur RVB ou CMJN plus constante pour les réglages du mixeur. 4 * 2 octets de couleur avec 2 octets de constante. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| monochrome | bool | r/w | Obtient ou définit une valeur indiquant si ce [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) est monochrome. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| version | short | r/w | Obtient ou définit la version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Obtient les données brutes des informations du canal. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Enregistre la ressource dans le conteneur de flux spécifié. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Définit les informations du canal. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Initialise une nouvelle instance de la classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            La spécification du format PSD contient la description suivante :<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 couleur RVB ou CMJN plus constante pour les réglages du mixeur. 4 * 2 octets de couleur avec 2 octets de constante.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Initialise une nouvelle instance de la classe [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/).<br/>            La spécification du format PSD contient la description suivante :<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 couleur RVB ou CMJN plus constante pour les réglages du mixeur. 4 * 2 octets de couleur avec 2 octets de constante.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Obtient les données brutes des informations du canal.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Tableau d'octets brut des informations du canal. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Définit les informations du canal.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |
| valeur | byte | La valeur. |

