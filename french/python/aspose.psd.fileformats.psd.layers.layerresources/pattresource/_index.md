---
title: "Classe PattResource"
type: docs
weight: 770
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/
---

**Summary:** Class PattResource. Resource with pattern data

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PattResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PattResource()](#PattResource__1) | Initialise une nouvelle instance de la classe [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PattResource(key, patterns)](#PattResource_key_patterns_2) | Initialise une nouvelle instance de la classe [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information d'outil de type 'Patt' pour 8 bits. |
| TYPE_TOOL_KEY2 [static] | int | r | La clé d'information d'outil de type 'Pat2' pour 16 bits. |
| TYPE_TOOL_KEY3 [static] | int | r | La clé d'information d'outil de type 'Pat3' pour 32 bits. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | r/w | Obtient ou définit les données de motifs ; |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre les données du bloc de ressources. |


### Constructor: PattResource() {#PattResource__1}


```
 PattResource() 
```

Initialise une nouvelle instance de la classe [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

### Constructor: PattResource(key, patterns) {#PattResource_key_patterns_2}


```
 PattResource(key, patterns) 
```

Initialise une nouvelle instance de la classe [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | int | La clé du type de ressource. |
| patterns | [PattResourceData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Les données de motifs. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Enregistre les données du bloc de ressources.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux dans lequel enregistrer. |
| psd_version | int | La version PSD. |

