---
title: "Classe CustResource"
type: docs
weight: 230
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustResource()](#CustResource__1) | Initialise une nouvelle instance de la classe [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
| [CustResource(data)](#CustResource_data_2) | Initialise une nouvelle instance de la classe [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| layer_created_date_time | datetime | r/w | Obtient ou définit la date de création du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Initialise une nouvelle instance de la classe [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Initialise une nouvelle instance de la classe [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/).

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

