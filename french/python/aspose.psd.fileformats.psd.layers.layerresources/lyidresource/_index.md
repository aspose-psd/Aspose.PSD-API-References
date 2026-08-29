---
title: "Classe LyidResource"
type: docs
weight: 660
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/
---

**Summary:** Class LyidResource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LyidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LyidResource(bytes)](#LyidResource_bytes_1) | Initialise une nouvelle instance de la classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) .<br/>            Avec une valeur personnalisée ou inconnue |
| [LyidResource(id)](#LyidResource_id_2) | Initialise une nouvelle instance de la classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/). |
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
| valeur | int | r | Obtient la valeur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre dans le conteneur de flux spécifié. |


### Constructor: LyidResource(bytes) {#LyidResource_bytes_1}


```
 LyidResource(bytes) 
```

Initialise une nouvelle instance de la classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) .<br/>            Avec une valeur personnalisée ou inconnue

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| octets | byte | Les octets. |

### Constructor: LyidResource(id) {#LyidResource_id_2}


```
 LyidResource(id) 
```

Initialise une nouvelle instance de la classe [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| id | int | L'identifiant du calque. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |
| psd_version | int | La version PSD. |

