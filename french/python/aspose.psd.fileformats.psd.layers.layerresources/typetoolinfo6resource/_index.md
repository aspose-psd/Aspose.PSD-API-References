---
title: "TypeToolInfo6Resource Classe"
type: docs
weight: 990
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Initialise une nouvelle instance de la classe [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | La signature de ressource spécifique au PSB. |
| RESOURCE_SIGNATURE [static] | int | r | La signature de ressource commune. |
| TYPE_TOOL_KEY [static] | int | r | La clé d'information de l'outil de type. |
| bottom | int | r/w | Obtient ou définit l'emplacement inférieur. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit l'ID de classe. |
| class_name | chaîne | r/w | Obtient ou définit le nom de classe. |
| descriptor_version | int | r/w | Obtient ou définit la version du descripteur. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtient ou définit les éléments. |
| clé | int | r | Obtient la clé de ressource du calque. |
| gauche | int | r/w | Obtient ou définit l'emplacement gauche. |
| longueur | int | r | Obtient la longueur de la ressource du calque en octets. |
| psd_version | int | r | Obtient la version minimale du PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| droite | int | r/w | Obtient ou définit l'emplacement droit. |
| signature | int | r | Obtient la signature. |
| text_version | short | r/w | Obtient ou définit la version du texte. |
| haut | int | r/w | Obtient ou définit l'emplacement supérieur. |
| transform_matrix | double | r/w | Obtient ou définit la matrice de transformation. |
| version | short | r/w | Obtient ou définit la version de l'outil de type. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit l'ID de classe. |
| warp_class_name | chaîne | r/w | Obtient ou définit le nom de la classe de distorsion. |
| warp_descriptor_version | int | r/w | Obtient ou définit la version du descripteur de distorsion. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtient ou définit les éléments de déformation. |
| warp_version | short | r/w | Obtient ou définit la version de la distorsion. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Enregistre la ressource dans le conteneur de flux spécifié. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Initialise une nouvelle instance de la classe [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID de la classe. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID de la classe de distorsion. |

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

