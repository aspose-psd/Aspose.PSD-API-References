---
title: "OSTypeStructuresRegistry Klasse"
type: docs
weight: 720
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Haalt de geregistreerde descriptors op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Haalt de eerste ondersteunde opener-descriptor op. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Haalt de eerste ondersteunde descriptor op basis van de type-naam. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Laadt [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) met de eerst gevonden opener die geschikt is voor de opgegeven <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registreert de opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistreert de opener. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Haalt de eerste ondersteunde opener-descriptor op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | De layer resource loader descriptor of null als er geen loader descriptor wordt ondersteund voor die stream. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Haalt de eerste ondersteunde descriptor op basis van de type-naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| descriptor_type_name | string | De descriptor type naam. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | De eerst gevonden opener descriptor of null als zo'n descriptor niet wordt gevonden. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Laadt [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) met de eerst gevonden opener die geschikt is voor de opgegeven <paramref name="stream" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | De geladen [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) of null als er geen opener wordt gevonden. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registreert de opener.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | De te registreren opener descriptor. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistreert de opener.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | De te deregistreren opener descriptor. |

