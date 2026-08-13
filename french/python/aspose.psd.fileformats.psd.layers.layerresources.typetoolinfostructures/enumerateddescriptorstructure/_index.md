---
title: "Classe EnumeratedDescriptorStructure"
type: docs
weight: 60
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/
---

**Summary:** The enumerated descriptor structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.EnumeratedDescriptorStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EnumeratedDescriptorStructure(key_name, type_id, enum_name)](#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1) | Initialise une nouvelle instance de la classe [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [statique] | int | r | La clé du descripteur énuméré. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit le nom de l'enum. |
| clé | int | r | Obtient la clé. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit le nom de la clé. |
| length | int | r | Obtient la longueur en octets de la [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Obtient ou définit l'ID du type. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Obtient la longueur de l'en-tête. |
| [save(stream_container)](#save_stream_container_2) | Enregistre les données. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Enregistre la structure dans le conteneur de flux spécifié. |


### Constructor: EnumeratedDescriptorStructure(key_name, type_id, enum_name) {#EnumeratedDescriptorStructure_key_name_type_id_enum_name_1}


```
 EnumeratedDescriptorStructure(key_name, type_id, enum_name) 
```

Initialise une nouvelle instance de la classe [EnumeratedDescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/enumerateddescriptorstructure/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Le nom de la clé. |
| type_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | L'ID du type. |
| enum_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Le nom de l'enum. |

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

Enregistre les données.

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

