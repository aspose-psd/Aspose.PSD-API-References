---
title: "Classe ObjectArrayStructure"
type: docs
weight: 100
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/
---

**Summary:** Defines the ObjectArrayStructure class that usually holds [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/) array.<br/>            It is used in the PSD file resources, such as PlLd Resource and SoLd Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ObjectArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ObjectArrayStructure(key, key_name, class_id, class_name, structures)](#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1) | Initialise une nouvelle instance de la classe [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
| [ObjectArrayStructure(key_name, class_id_name, structures)](#ObjectArrayStructure_key_name_class_id_name_structures_2) | Initialise une nouvelle instance de la classe [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [statique] | int | r | Identifie la clé de structure 'ObAr'. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit l'ID de classe du tableau d'objets. |
| class_name | chaîne | r/w | Obtient ou définit le nom de classe du tableau d'objets. |
| clé | int | r | Obtient la clé de structure du tableau d'objets. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit le nom de la clé. |
| length | int | r | Obtient la longueur en octets de la [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| structure_count | int | r | Obtient le nombre de sous-structures du tableau d'objets. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Obtient ou définit une copie d'un tableau de structures. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtient la longueur de l'en-tête. |
| [save(stream_container)](#save_stream_container_2) | Enregistre la structure dans le conteneur de flux spécifié. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Enregistre la structure dans le conteneur de flux spécifié. |


### Constructor: ObjectArrayStructure(key, key_name, class_id, class_name, structures) {#ObjectArrayStructure_key_key_name_class_id_class_name_structures_1}


```
 ObjectArrayStructure(key, key_name, class_id, class_name, structures) 
```

Initialise une nouvelle instance de la classe [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| clé | int | La clé entière. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Le nom de la clé. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | L'identifiant de classe. |
| class_name | chaîne | Nom de la classe. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Les structures. |

### Constructor: ObjectArrayStructure(key_name, class_id_name, structures) {#ObjectArrayStructure_key_name_class_id_name_structures_2}


```
 ObjectArrayStructure(key_name, class_id_name, structures) 
```

Initialise une nouvelle instance de la classe [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key_name | chaîne | Nom de la clé. |
| class_id_name | chaîne | Nom de l'identifiant de classe. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Les structures. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Obtient la longueur de l'en-tête.

**Returns**

| Type | Description |
| :- | :- |
| int | La longueur de l'en-tête |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Enregistre la structure dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Enregistre la structure dans le conteneur de flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Le conteneur de flux. |

