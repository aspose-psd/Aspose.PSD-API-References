---
title: "Classe VmskResource"
type: docs
weight: 1100
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---

**Summary:** Class VmskResource.<br/>            This resource contains information about vector layer mask

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VmskResource

**Inheritance:** IVectorPathData, VectorPathDataResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VmskResource()](#VmskResource__1) | Initialise une nouvelle instance de la classe [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
| [VmskResource(data)](#VmskResource_data_2) | Initialise une nouvelle instance de la classe [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| is_disabled | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| is_inverted | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| is_not_linked | bool | r/w | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| paths | [VectorPathRecord[]](/psd/python-net/aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) | r/w | Obtient ou définit les enregistrements de chemin. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| signature | int | r | Obtient la signature. |
| version | int | r/w | Obtient ou définit la version. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: VmskResource() {#VmskResource__1}


```
 VmskResource() 
```

Initialise une nouvelle instance de la classe [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

### Constructor: VmskResource(data) {#VmskResource_data_2}


```
 VmskResource(data) 
```

Initialise une nouvelle instance de la classe [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/).

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

