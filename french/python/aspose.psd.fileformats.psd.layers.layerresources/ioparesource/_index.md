---
title: "Classe IopaResource"
type: docs
weight: 440
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Initialise une nouvelle instance de la classe [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
| [IopaResource(data)](#IopaResource_data_2) | Initialise une nouvelle instance de la classe [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| opacité_remplissage | byte | r/w | Obtient ou définit l'opacité du remplissage. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Initialise une nouvelle instance de la classe [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Initialise une nouvelle instance de la classe [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données brutes en octets. |

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

