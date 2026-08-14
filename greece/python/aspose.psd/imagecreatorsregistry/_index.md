---
title: "Κλάση ImageCreatorsRegistry"
type: docs
weight: 2210
url: /el/python-net/aspose.psd/imagecreatorsregistry/
---

**Summary:** Represents the image creators registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageCreatorsRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageCreatorDescriptor[]](/psd/python-net/aspose.psd/iimagecreatordescriptor) | r | Λαμβάνει τους καταχωρημένους περιγραφείς. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει τις καταχωρημένες μορφές δημιουργίας εικόνας. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [create_first_supported_creator(image_options)](#create_first_supported_creator_image_options_1) | Δημιουργεί τον πρώτο βρεθέντα δημιουργό που είναι κατάλληλος για το καθορισμένο. |
| [get_first_supported_descriptor(image_options)](#get_first_supported_descriptor_image_options_2) | Λαμβάνει τον πρώτο ευρεθέν υποστηριζόμενο περιγραφέα κατάλληλο για το καθορισμένο. |
| [register(image_creator_descriptor)](#register_image_creator_descriptor_3) | Καταχωρεί τον καθορισμένο περιγραφέα δημιουργού εικόνας. |
| [register_creator(creator_descriptor)](#register_creator_creator_descriptor_4) | Καταχωρεί τον δημιουργό. |
| [unregister_creator(creator_descriptor)](#unregister_creator_creator_descriptor_5) | Καταργεί την καταχώρηση του δημιουργού. |


### Method: create_first_supported_creator(image_options)  [static] {#create_first_supported_creator_image_options_1}


```
 create_first_supported_creator(image_options) 
```

Δημιουργεί τον πρώτο βρεθέντα δημιουργό που είναι κατάλληλος για το καθορισμένο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageCreator](/psd/python-net/aspose.psd/iimagecreator) | Ο δημιουργός που υποστηρίζει το καθορισμένο ή null εάν δεν βρεθεί τέτοιος δημιουργός. |


### Method: get_first_supported_descriptor(image_options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image_options) 
```

Λαμβάνει τον πρώτο ευρεθέν υποστηριζόμενο περιγραφέα κατάλληλο για το καθορισμένο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Ο περιγραφέας δημιουργού που υποστηρίζει το καθορισμένο ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: register(image_creator_descriptor)  [static] {#register_image_creator_descriptor_3}


```
 register(image_creator_descriptor) 
```

Καταχωρεί τον καθορισμένο περιγραφέα δημιουργού εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Ο περιγραφέας δημιουργού εικόνας. |

### Method: register_creator(creator_descriptor)  [static] {#register_creator_creator_descriptor_4}


```
 register_creator(creator_descriptor) 
```

Καταχωρεί τον δημιουργό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Ο περιγραφέας δημιουργού προς καταχώρηση. |

### Method: unregister_creator(creator_descriptor)  [static] {#unregister_creator_creator_descriptor_5}


```
 unregister_creator(creator_descriptor) 
```

Καταργεί την καταχώρηση του δημιουργού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| creator_descriptor | [IImageCreatorDescriptor](/psd/python-net/aspose.psd/iimagecreatordescriptor) | Ο περιγραφέας δημιουργού. |

