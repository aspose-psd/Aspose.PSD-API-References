---
title: OSTypeStructuresRegistry Class
type: docs
weight: 670
url: /python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 23.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Gets the registered descriptors. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Gets the first supported opener descriptor. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Gets the first supported descriptor by its type name. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Loads [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) using first found opener suitable for the specified <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registers the opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Unregisters the opener. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Gets the first supported opener descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | The layer resource loader descriptor or null if no loader descriptor supported for such stream. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Gets the first supported descriptor by its type name.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| descriptor_type_name | string | The descriptor type name. |

**Returns**

| Type | Description |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | The first found opener descriptor or null if not such descriptor is found. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Loads [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) using first found opener suitable for the specified <paramref name="stream" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | The loaded [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) or null if no opener is found. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registers the opener.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | The opener descriptor to register. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Unregisters the opener.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | The opener descriptor to unregister. |

