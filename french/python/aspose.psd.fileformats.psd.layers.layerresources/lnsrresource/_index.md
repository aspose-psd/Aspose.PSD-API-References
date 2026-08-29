---
title: "LnsrResource Classe"
type: docs
weight: 600
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/
---

**Summary:** Class lnsrResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LnsrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LnsrResource(bytes)](#LnsrResource_bytes_1) | Initialise une nouvelle instance de la classe [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).<br/>            Avec une valeur personnalisée ou inconnue |
| [LnsrResource(lnsr_resource_type)](#LnsrResource_lnsr_resource_type_2) | Initialise une nouvelle instance de la classe [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| data | byte | r | Obtient les données brutes. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| value | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | r | Obtient la valeur en tant que LnsrResourceType si l'énumération correspondante est décrite.<br/>            Sinon retourne Unknown |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre le conteneur de flux spécifié. |


### Constructor: LnsrResource(bytes) {#LnsrResource_bytes_1}


```
 LnsrResource(bytes) 
```

Initialise une nouvelle instance de la classe [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).<br/>            Avec une valeur personnalisée ou inconnue

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets. |

### Constructor: LnsrResource(lnsr_resource_type) {#LnsrResource_lnsr_resource_type_2}


```
 LnsrResource(lnsr_resource_type) 
```

Initialise une nouvelle instance de la classe [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| lnsr_resource_type | [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype) | Type du LNSR. |

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

