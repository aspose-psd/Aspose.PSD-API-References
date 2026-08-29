---
title: "LuniResource Classe"
type: docs
weight: 650
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/
---

**Summary:** Layer name resource

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LuniResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LuniResource()](#LuniResource__1) | Initialise une nouvelle instance de la classe [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| name | chaîne | r/w | Obtient ou définit le nom. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre le conteneur de flux spécifié. |


### Constructor: LuniResource() {#LuniResource__1}


```
 LuniResource() 
```

Initialise une nouvelle instance de la classe [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/).

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

