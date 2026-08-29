---
title: "ExpaResource Classe"
type: docs
weight: 280
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/
---

**Summary:** Class ExpaResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ExpaResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ExpaResource()](#ExpaResource__1) | Initialise une nouvelle instance de la classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(bytes)](#ExpaResource_bytes_2) | Initialise une nouvelle instance de la classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
| [ExpaResource(exposure, offset, gamma)](#ExpaResource_exposure_offset_gamma_3) | Initialise une nouvelle instance de la classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| exposition | float | r/w | Obtient ou définit l'exposition. |
| gamma_correction | float | r/w | Obtient ou définit le gamma. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| offset | float | r/w | Obtient ou définit le décalage. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| version | short | r | Obtient la version. La valeur par défaut est 1. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: ExpaResource() {#ExpaResource__1}


```
 ExpaResource() 
```

Initialise une nouvelle instance de la classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

### Constructor: ExpaResource(bytes) {#ExpaResource_bytes_2}


```
 ExpaResource(bytes) 
```

Initialise une nouvelle instance de la classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets. |

### Constructor: ExpaResource(exposure, offset, gamma) {#ExpaResource_exposure_offset_gamma_3}


```
 ExpaResource(exposure, offset, gamma) 
```

Initialise une nouvelle instance de la classe [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| exposition | float | L'exposition. |
| offset | float | Le décalage. |
| gamma | float | Le gamma. |

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

