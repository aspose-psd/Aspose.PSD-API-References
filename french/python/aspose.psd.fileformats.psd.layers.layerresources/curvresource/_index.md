---
title: "Classe CurvResource"
type: docs
weight: 190
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---

**Summary:** Class CurvResource. Resource of Curves Adjustment Layer<br/>            1 byte - 0 if use curves, 1 if used pixels on map<br/>            if 0 then:<br/>            2 bytes - short.  Default is 1<br/>            4 bytes - int. Used only last byte by bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            2 bytes - short points count<br/>            4 bytes * count of point - points of curve 2 short: first position, second height<br/>            4 bytes - word "Crv "<br/>            2 bytes - short default is 4 for Curves<br/>            4 bytes - int. Default is 1<br/>            4 bytes - point count<br/>            4 bytes * point count - points of curve 2 short: first position, second height<br/>            0-4 bytes - Leading to be fold for four<br/>            if 1 then:<br/>            2 bytes - short. Default is 1<br/>            4 bytes - int. Used only last byte. One channel is in one bit. First bit is for 1 channel, the Fourth bit for 4 channel for example<br/>            256 * count of changed channels - ordered values of channel in range 0 - 255<br/>            4 bytes - word "Crv "<br/>            2 bytes - short. Default is 3 for pixels on map<br/>            4 bytes - int Channel count<br/>            (2 + 256) bytes - short 2 for channel index, 256 is ordered values of channel in range 0 - 255

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CurvResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurvResource(bytes)](#CurvResource_bytes_1) | Initialise une nouvelle instance de la classe [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
| [CurvResource(max_channel_count)](#CurvResource_max_channel_count_2) | Initialise une nouvelle instance de la classe [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| is_data_stored_discretely | bool | r/w | Obtient ou définit une valeur indiquant si cette instance stocke les données de façon discrète. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_active_manager()](#get_active_manager__1) | Obtient le gestionnaire actif. |
| [get_channel_data(channel_index)](#get_channel_data_channel_index_2) | Obtient les données du canal. |
| [get_curve_manager()](#get_curve_manager__3) | Obtient le gestionnaire de courbes. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_4) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: CurvResource(bytes) {#CurvResource_bytes_1}


```
 CurvResource(bytes) 
```

Initialise une nouvelle instance de la classe [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets. |

### Constructor: CurvResource(max_channel_count) {#CurvResource_max_channel_count_2}


```
 CurvResource(max_channel_count) 
```

Initialise une nouvelle instance de la classe [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| max_channel_count | int | Le nombre maximal de canaux. |

### Method: get_active_manager() {#get_active_manager__1}


```
 get_active_manager() 
```

Obtient le gestionnaire actif.

**Returns**

| Type | Description |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | Gestionnaire actif |


### Method: get_channel_data(channel_index) {#get_channel_data_channel_index_2}


```
 get_channel_data(channel_index) 
```

Obtient les données du canal.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| channel_index | int | Indice du canal. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Données du canal |


### Method: get_curve_manager() {#get_curve_manager__3}


```
 get_curve_manager() 
```

Obtient le gestionnaire de courbes.

**Returns**

| Type | Description |
| :- | :- |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager) | [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) ou [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_4}


```
 save(stream_container, psd_version) 
```

Enregistre la ressource dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

