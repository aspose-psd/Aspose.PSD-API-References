---
title: "Κλάση LayerResourcesRegistry"
type: docs
weight: 1010
url: /el/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/
---

**Summary:** Define the layer resources registry for PSD files loading.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerResourcesRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [ILayerResourceLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | r | Λαμβάνει τους καταχωρημένους περιγραφείς. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_first_supported_descriptor(stream, psd_version)](#get_first_supported_descriptor_stream_psd_version_1) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοίγματος. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του. |
| [load_resource_by_first_supported_descriptor(stream, psd_version)](#load_resource_by_first_supported_descriptor_stream_psd_version_3) | Φορτώνει το [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) χρησιμοποιώντας τον πρώτο βρεθέντα ανοίγων που είναι κατάλληλος για το καθορισμένο <paramref name=\"stream\" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Καταχωρίζει τον ανοίγοντα. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Αποεγγράφει τον ανοίγοντα. |


### Method: get_first_supported_descriptor(stream, psd_version)  [static] {#get_first_supported_descriptor_stream_psd_version_1}


```
 get_first_supported_descriptor(stream, psd_version) 
```

Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοίγματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |
| psd_version | int | Η έκδοση PSD. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Ο περιγραφέας φορτωτή πόρων στρώματος ή null εάν δεν υποστηρίζεται περιγραφέας φορτωτή για τέτοια ροή. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_2}


```
 get_first_supported_descriptor_by_type_name(descriptor_type_name) 
```

Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| descriptor_type_name | string | Το όνομα τύπου περιγραφέα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Ο πρώτος εντοπισμένος περιγραφέας ανοίγοντα ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: load_resource_by_first_supported_descriptor(stream, psd_version)  [static] {#load_resource_by_first_supported_descriptor_stream_psd_version_3}


```
 load_resource_by_first_supported_descriptor(stream, psd_version) 
```

Φορτώνει το [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) χρησιμοποιώντας τον πρώτο βρεθέντα ανοίγων που είναι κατάλληλος για το καθορισμένο <paramref name=\"stream\" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |
| psd_version | int | Η έκδοση PSD. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | Το φορτωμένο [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) ή null εάν δεν βρεθεί ανοίγων. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Καταχωρίζει τον ανοίγοντα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Ο περιγραφέας ανοίγοντα προς καταχώρηση. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Αποεγγράφει τον ανοίγοντα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| opener_descriptor | [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader) | Ο περιγραφέας ανοίγοντα προς αποεγγραφή. |

