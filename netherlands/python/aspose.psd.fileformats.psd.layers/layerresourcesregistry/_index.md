---
title: "LayerResourcesRegistry Klasse"
type: docs
weight: 1010
url: /nl/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Haalt de geregistreerde descriptors op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Haalt de eerste ondersteunde opener-descriptor op. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Haalt de eerste ondersteunde descriptor op basis van de type-naam. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Laadt [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) met behulp van de eerst gevonden opener die geschikt is voor de opgegeven <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registreert de opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistreert de opener. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Haalt de eerste ondersteunde opener-descriptor op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |
| psd_version | int | De PSD‑versie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | De layer resource loader descriptor of null als er geen loader descriptor wordt ondersteund voor die stream. |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | De eerst gevonden opener descriptor of null als zo'n descriptor niet wordt gevonden. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Laadt [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) met behulp van de eerst gevonden opener die geschikt is voor de opgegeven <paramref name="stream" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |
| psd_version | int | De PSD‑versie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | De geladen [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) of null als er geen opener wordt gevonden. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registreert de opener.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | De te registreren opener descriptor. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistreert de opener.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | De te deregistreren opener descriptor. |

