---
title: "OSTypeStructuresRegistry Κλάση"
type: docs
weight: 720
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---

**Summary:** Represents the [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) resources registry.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructuresRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IOSTypeStructureLoader[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | r | Λαμβάνει τους καταχωρημένους περιγραφείς. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_first_supported_descriptor(stream)](#get_first_supported_descriptor_stream_1) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοίγματος. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_2) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του. |
| [load_resource_by_first_supported_descriptor(stream)](#load_resource_by_first_supported_descriptor_stream_3) | Φορτώνει [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) χρησιμοποιώντας τον πρώτο βρεθέντα ανοικτήρα που είναι κατάλληλος για το καθορισμένο <paramref name="stream" />. |
| [register_opener(opener_descriptor)](#register_opener_opener_descriptor_4) | Καταχωρίζει τον ανοίγοντα. |
| [unregister_opener(opener_descriptor)](#unregister_opener_opener_descriptor_5) | Αποεγγράφει τον ανοίγοντα. |


### Method: get_first_supported_descriptor(stream)  [static] {#get_first_supported_descriptor_stream_1}


```
 get_first_supported_descriptor(stream) 
```

Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα ανοίγματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Ο περιγραφέας φορτωτή πόρων στρώματος ή null εάν δεν υποστηρίζεται περιγραφέας φορτωτή για τέτοια ροή. |


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
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Ο πρώτος εντοπισμένος περιγραφέας ανοίγοντα ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: load_resource_by_first_supported_descriptor(stream)  [static] {#load_resource_by_first_supported_descriptor_stream_3}


```
 load_resource_by_first_supported_descriptor(stream) 
```

Φορτώνει [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) χρησιμοποιώντας τον πρώτο βρεθέντα ανοικτήρα που είναι κατάλληλος για το καθορισμένο <paramref name="stream" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Το φορτωμένο [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) ή null εάν δεν βρεθεί ανοίγων. |


### Method: register_opener(opener_descriptor)  [static] {#register_opener_opener_descriptor_4}


```
 register_opener(opener_descriptor) 
```

Καταχωρίζει τον ανοίγοντα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Ο περιγραφέας ανοίγοντα προς καταχώρηση. |

### Method: unregister_opener(opener_descriptor)  [static] {#unregister_opener_opener_descriptor_5}


```
 unregister_opener(opener_descriptor) 
```

Αποεγγράφει τον ανοίγοντα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| opener_descriptor | [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader) | Ο περιγραφέας ανοίγοντα προς αποεγγραφή. |

