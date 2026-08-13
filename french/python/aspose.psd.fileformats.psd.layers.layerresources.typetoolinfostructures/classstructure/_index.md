---
title: "Classe ClassStructure"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | Initialise une nouvelle instance de la classe [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | Identifie la clé de structure. |
| STRUCTURE_KEY_GLBC [static] | int | r | Identifie la clé de structure. |
| STRUCTURE_KEY_TYPE [static] | int | r | Identifie la clé de structure. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit l'ID de classe. |
| class_name | chaîne | r/w | Obtient ou définit le nom de classe. |
| clé | int | r | Obtient la clé de structure. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit le nom de la clé. |
| length | int | r | Obtient la longueur en octets de la [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtient la longueur de l'en-tête. |
| [save(stream_container)](#save_stream_container_2) | Enregistre la structure dans le conteneur de flux spécifié. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Enregistre la structure dans le conteneur de flux spécifié. |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

Initialise une nouvelle instance de la classe [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Nom de la clé. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID de la classe. |
| structure_key | int | La clé de structure. |

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

