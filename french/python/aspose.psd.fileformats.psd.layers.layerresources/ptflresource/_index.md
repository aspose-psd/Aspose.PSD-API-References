---
title: "PtFlResource Classe"
type: docs
weight: 860
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---

**Summary:** Class PtFlResource. Contains Pattern Fill Layer Data.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PtFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PtFlResource()](#PtFlResource__1) | Initialise une nouvelle instance de la classe [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
| [PtFlResource(pattern_name, pattern_id)](#PtFlResource_pattern_name_pattern_id_2) | Initialise une nouvelle instance de la classe [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| align_with_layer | bool | r/w | Obtient ou définit une valeur indiquant si [align with layer]. |
| angle | double | r/w | Obtient ou définit l'angle. |
| is_linked_with_layer | bool | r/w | Obtient ou définit une valeur indiquant si cette instance est liée à la couche. |
| clé | int | r | Obtient la clé de ressource du calque. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| offset | [Point](/psd/python-net/aspose.psd/point) | r/w | Obtient ou définit le décalage. |
| pattern_id | chaîne | r/w | Obtient ou définit l'identifiant du motif. |
| pattern_name | chaîne | r/w | Obtient ou définit le nom du motif. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| scale | double | r/w | Obtient ou définit l'échelle. |
| signature | int | r | Obtient la signature. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: PtFlResource() {#PtFlResource__1}


```
 PtFlResource() 
```

Initialise une nouvelle instance de la classe [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

### Constructor: PtFlResource(pattern_name, pattern_id) {#PtFlResource_pattern_name_pattern_id_2}


```
 PtFlResource(pattern_name, pattern_id) 
```

Initialise une nouvelle instance de la classe [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| pattern_name | chaîne | Nom du motif. |
| pattern_id | chaîne | L'identifiant du motif. |

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

