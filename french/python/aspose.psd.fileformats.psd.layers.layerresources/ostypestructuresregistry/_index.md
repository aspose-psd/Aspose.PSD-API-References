---
title: "Classe OSTypeStructuresRegistry"
type: docs
weight: 720
url: /fr/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Obtient les descripteurs enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Obtient le premier descripteur d'ouverture pris en charge. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Obtient le premier descripteur pris en charge par son nom de type. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Charge [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) en utilisant le premier ouvreur trouvé adapté au <paramref name="stream" /> spécifié. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Enregistre l'ouvreur. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Désenregistre l'ouvreur. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Obtient le premier descripteur d'ouverture pris en charge.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Le descripteur du chargeur de ressources de calque ou null si aucun descripteur de chargeur n'est pris en charge pour ce flux. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Obtient le premier descripteur pris en charge par son nom de type.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| descriptor_type_name | chaîne | Le nom du type de descripteur. |

**Returns**

| Type | Description |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Le premier descripteur d'ouvreur trouvé ou null si aucun tel descripteur n'est trouvé. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Charge [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) en utilisant le premier ouvreur trouvé adapté au <paramref name="stream" /> spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | La [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) chargée ou null si aucun ouvreur n'est trouvé. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Enregistre l'ouvreur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Le descripteur d'ouvreur à enregistrer. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Désenregistre l'ouvreur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Le descripteur d'ouvreur à désenregistrer. |

