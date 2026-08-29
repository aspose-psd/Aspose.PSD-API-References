---
title: "Classe LayerResourcesRegistry"
type: docs
weight: 1010
url: /fr/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Obtient les descripteurs enregistrés. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Obtient le premier descripteur d'ouverture pris en charge. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Obtient le premier descripteur pris en charge par son nom de type. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Charge [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) en utilisant le premier ouvreur trouvé adapté au <paramref name="stream" /> spécifié. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Enregistre l'ouvreur. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Désenregistre l'ouvreur. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Obtient le premier descripteur d'ouverture pris en charge.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| psd_version | int | La version PSD. |

**Returns**

| Type | Description |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Le descripteur du chargeur de ressources de calque ou null si aucun descripteur de chargeur n'est pris en charge pour ce flux. |


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
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Le premier descripteur d'ouvreur trouvé ou null si aucun tel descripteur n'est trouvé. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Charge [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) en utilisant le premier ouvreur trouvé adapté au <paramref name="stream" /> spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |
| psd_version | int | La version PSD. |

**Returns**

| Type | Description |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | La [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) chargée ou null si aucun ouvreur n'est trouvé. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Enregistre l'ouvreur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Le descripteur d'ouvreur à enregistrer. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Désenregistre l'ouvreur.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Le descripteur d'ouvreur à désenregistrer. |

