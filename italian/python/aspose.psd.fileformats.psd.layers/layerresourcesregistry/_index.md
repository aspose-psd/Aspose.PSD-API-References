---
title: "Classe LayerResourcesRegistry"
type: docs
weight: 1010
url: /it/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Ottiene i descrittori registrati. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Ottiene il primo descrittore di apertura supportato. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Ottiene il primo descrittore supportato per nome del tipo. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Carica [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) usando il primo apritore trovato adatto per lo <paramref name="stream" /> specificato. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registra l'opener. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistra l'opener. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Ottiene il primo descrittore di apertura supportato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso. |
| psd_version | int | La versione PSD. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Il descrittore del caricatore di risorse di livello o null se non è supportato alcun descrittore di caricatore per tale flusso. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Ottiene il primo descrittore supportato per nome del tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| descriptor_type_name | string | Il nome del tipo di descrittore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Il primo descrittore di opener trovato o null se non viene trovato alcun descrittore. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Carica [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) usando il primo apritore trovato adatto per lo <paramref name="stream" /> specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flusso | _io.BufferedRandom | Il flusso. |
| psd_version | int | La versione PSD. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Il [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) caricato o null se non viene trovato alcun opener. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registra l'opener.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Il descrittore di opener da registrare. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistra l'opener.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Il descrittore di opener da deregistrare. |

