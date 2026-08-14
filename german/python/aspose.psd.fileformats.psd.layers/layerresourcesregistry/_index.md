---
title: "LayerResourcesRegistry Klasse"
type: docs
weight: 1010
url: /de/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Liest die registrierten Deskriptoren. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Ermittelt den ersten unterstützten Öffner-Deskriptor. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Ermittelt den ersten unterstützten Deskriptor anhand seines Typnamens. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Lädt [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) mit dem zuerst gefundenen Öffner, der für den angegebenen <paramref name="stream" /> geeignet ist. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registriert den Öffner. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistriert den Öffner. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Ermittelt den ersten unterstützten Öffner-Deskriptor.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream. |
| psd_version | int | Die PSD-Version. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Der Layer-Resource-Loader-Deskriptor oder null, falls kein Loader-Deskriptor für einen solchen Stream unterstützt wird. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Ermittelt den ersten unterstützten Deskriptor anhand seines Typnamens.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| descriptor_type_name | string | Der Deskriptor-Typname. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Der zuerst gefundene Öffner-Deskriptor oder null, falls ein solcher Deskriptor nicht gefunden wird. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Lädt [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) mit dem zuerst gefundenen Öffner, der für den angegebenen <paramref name="stream" /> geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream. |
| psd_version | int | Die PSD-Version. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Das geladene [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) oder null, falls kein Öffner gefunden wird. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registriert den Öffner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Der zu registrierende Öffner-Deskriptor. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistriert den Öffner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Der zu deregistrierende Öffner-Deskriptor. |

