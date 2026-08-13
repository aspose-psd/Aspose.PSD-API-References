---
title: "Classe VibAResource"
type: docs
weight: 1090
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---

**Summary:** VibA Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VibAResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VibAResource()](#VibAResource__1) | Initialise une nouvelle instance de la classe [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| saturation | int | r/w | Obtient ou définit la valeur de saturation |
| signature | int | r | Obtient la signature. |
| vibrance | int | r/w | Obtient ou définit la valeur de vibrance |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: VibAResource() {#VibAResource__1}


```
 VibAResource() 
```

Initialise une nouvelle instance de la classe [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/).

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

