---
title: "LayerResourcesRegistry-klass"
type: docs
weight: 1010
url: /sv/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Hämtar de registrerade beskrivarna. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Hämtar den första stödjade öppnarebeskrivaren. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Hämtar den första stödjade beskrivaren efter dess typnamn. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Laddar [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) med den först hittade öppnaren som är lämplig för den angivna <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registrerar öppnaren. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Avregistrerar öppnaren. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Hämtar den första stödjade öppnarebeskrivaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen. |
| psd_version | int | PSD-versionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Layerresursens laddningsbeskrivare eller null om ingen laddningsbeskrivare stöds för sådan ström. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Hämtar den första stödjade beskrivaren efter dess typnamn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| descriptor_type_name | string | Beskrivartypens namn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Den först hittade öppnarebeskrivaren eller null om en sådan beskrivare inte hittas. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Laddar [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) med den först hittade öppnaren som är lämplig för den angivna <paramref name="stream" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen. |
| psd_version | int | PSD-versionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Den laddade [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) eller null om ingen öppnare hittas. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registrerar öppnaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Öppnarebeskrivaren att registrera. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Avregistrerar öppnaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Öppnarebeskrivaren att avregistrera. |

