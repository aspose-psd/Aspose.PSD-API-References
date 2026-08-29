---
title: "Classe KnkoResource"
type: docs
weight: 450
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/
---

**Summary:** Class KnkoResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.KnkoResource

**Inheritance:** BooleanResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [KnkoResource()](#KnkoResource__1) | Initialise une nouvelle instance de la classe [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
| [KnkoResource(data)](#KnkoResource_data_2) | Initialise une nouvelle instance de la classe [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).<br/>            Avec une valeur personnalisée ou inconnue |
| [KnkoResource(knockout)](#KnkoResource_knockout_3) | Initialise une nouvelle instance de la classe [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| clé | int | r | Obtient la clé de ressource du calque. |
| knockout | bool | r/w | Obtient ou définit une valeur indiquant si [blend interior elements]. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre le conteneur de flux spécifié. |


### Constructor: KnkoResource() {#KnkoResource__1}


```
 KnkoResource() 
```

Initialise une nouvelle instance de la classe [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

### Constructor: KnkoResource(data) {#KnkoResource_data_2}


```
 KnkoResource(data) 
```

Initialise une nouvelle instance de la classe [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).<br/>            Avec une valeur personnalisée ou inconnue

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données de la ressource. |

### Constructor: KnkoResource(knockout) {#KnkoResource_knockout_3}


```
 KnkoResource(knockout) 
```

Initialise une nouvelle instance de la classe [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| knockout | bool | si défini sur <c>true</c> [blend interior elements]. |

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

