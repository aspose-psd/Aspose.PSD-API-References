---
title: "Clase LayerResourcesRegistry"
type: docs
weight: 1010
url: /es/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Obtiene los descriptores registrados. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Obtiene el primer descriptor de apertura compatible. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Carga [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) usando el primer abridor encontrado adecuado para el <paramref name="stream" /> especificado. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registra el abridor. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Desregistra el abridor. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Obtiene el primer descriptor de apertura compatible.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| psd_version | int | La versión PSD. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | El descriptor del cargador de recursos de capa o null si no se admite ningún descriptor de cargador para dicho flujo. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Obtiene el primer descriptor compatible por su nombre de tipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| descriptor_type_name | string | El nombre del tipo de descriptor. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | El primer descriptor de abridor encontrado o null si no se encuentra tal descriptor. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Carga [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) usando el primer abridor encontrado adecuado para el <paramref name="stream" /> especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |
| psd_version | int | La versión PSD. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | El [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) cargado o null si no se encuentra ningún abridor. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registra el abridor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | El descriptor de abridor a registrar. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Desregistra el abridor.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | El descriptor de abridor a desregistrar. |

