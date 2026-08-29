---
title: "Classe ClblResource"
type: docs
weight: 160
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/
---

**Summary:** Class ClblResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ClblResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClblResource()](#ClblResource__1) | Initialise une nouvelle instance de la classe [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(blend_clipped_elements)](#ClblResource_blend_clipped_elements_2) | Initialise une nouvelle instance de la classe [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/). |
| [ClblResource(data)](#ClblResource_data_3) | Initialise une nouvelle instance de la classe [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .<br/>            Avec une valeur personnalisée ou inconnue |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| blend_clipped_elements | bool | r/w | Obtient ou définit une valeur indiquant si [blend clipped elements]. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre le conteneur de flux spécifié. |


### Constructor: ClblResource() {#ClblResource__1}


```
 ClblResource() 
```

Initialise une nouvelle instance de la classe [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

### Constructor: ClblResource(blend_clipped_elements) {#ClblResource_blend_clipped_elements_2}


```
 ClblResource(blend_clipped_elements) 
```

Initialise une nouvelle instance de la classe [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| blend_clipped_elements | bool | si défini sur <c>true</c> [blend clipped elements]. |

### Constructor: ClblResource(data) {#ClblResource_data_3}


```
 ClblResource(data) 
```

Initialise une nouvelle instance de la classe [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) .<br/>            Avec une valeur personnalisée ou inconnue

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

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

