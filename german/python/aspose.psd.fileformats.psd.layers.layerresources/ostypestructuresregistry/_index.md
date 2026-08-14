---
title: "OSTypeStructuresRegistry Klasse"
type: docs
weight: 720
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Liest die registrierten Deskriptoren. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Ermittelt den ersten unterstützten Öffner-Deskriptor. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Ermittelt den ersten unterstützten Deskriptor anhand seines Typnamens. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Lädt [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) mit dem zuerst gefundenen Öffner, der für den angegebenen <paramref name="stream" /> geeignet ist. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Registriert den Öffner. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Deregistriert den Öffner. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Ermittelt den ersten unterstützten Öffner-Deskriptor.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Der Layer-Resource-Loader-Deskriptor oder null, falls kein Loader-Deskriptor für einen solchen Stream unterstützt wird. |


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
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Der zuerst gefundene Öffner-Deskriptor oder null, falls ein solcher Deskriptor nicht gefunden wird. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Lädt [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) mit dem zuerst gefundenen Öffner, der für den angegebenen <paramref name="stream" /> geeignet ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Das geladene [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) oder null, falls kein Öffner gefunden wird. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Registriert den Öffner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Der zu registrierende Öffner-Deskriptor. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Deregistriert den Öffner.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Der zu deregistrierende Öffner-Deskriptor. |

