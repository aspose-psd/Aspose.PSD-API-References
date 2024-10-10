---
title: LayerResourcesRegistry Class
type: docs
weight: 960
url: /python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.8.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Gets the registered descriptors. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Gets the first supported opener descriptor. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Gets the first supported descriptor by its type name. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Loads [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) using first found opener suitable for the specified <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registers the opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Unregisters the opener. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Gets the first supported opener descriptor.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| psd_version | int | The PSD version. |

**Returns**

| Type | Description |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | The layer resource loader descriptor or null if no loader descriptor supported for such stream. |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | The first found opener descriptor or null if not such descriptor is found. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Loads [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) using first found opener suitable for the specified <paramref name="stream" />.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |
| psd_version | int | The PSD version. |

**Returns**

| Type | Description |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | The loaded [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) or null if no opener is found. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registers the opener.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | The opener descriptor to register. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Unregisters the opener.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | The opener descriptor to unregister. |

