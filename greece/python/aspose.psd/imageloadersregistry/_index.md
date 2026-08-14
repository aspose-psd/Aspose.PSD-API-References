---
title: "ImageLoadersRegistry Κλάση"
type: docs
weight: 2260
url: /el/python-net/aspose.psd/imageloadersregistry/
---

**Summary:** Represents the image loaders registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageLoadersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| registered_descriptors [static] | [IImageLoaderDescriptor[]](/psd/python-net/aspose.psd/iimageloaderdescriptor) | r | Λαμβάνει τους καταχωρημένους περιγραφείς. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει τις καταχωρημένες μορφές φόρτωσης εικόνας. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [create_first_supported_loader(stream, load_options)](#create_first_supported_loader_stream_load_options_1) | Δημιουργεί τον πρώτο φορτωτή που βρέθηκε κατάλληλο για το καθορισμένο <paramref name=\"stream\" /> και προαιρετικά για το <paramref name=\"loadOptions\" />. |
| [get_first_supported_descriptor(stream, load_options)](#get_first_supported_descriptor_stream_load_options_2) | Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα κατάλληλο για το καθορισμένο <paramref name=\"stream\" /> και προαιρετικά για το <paramref name=\"loadOptions\" />. |
| [get_first_supported_descriptor_by_file_format(file_format)](#get_first_supported_descriptor_by_file_format_file_format_3) | Λαμβάνει την πρώτη υποστηριζόμενη μορφή αρχείου με βάση το όνομα τύπου της. |
| [get_first_supported_descriptor_by_type_name(descriptor_type_name)](#get_first_supported_descriptor_by_type_name_descriptor_type_name_4) | Λαμβάνει τον πρώτο υποστηριζόμενο περιγραφέα με βάση το όνομα τύπου του. |
| [register(image_loader_descriptor)](#register_image_loader_descriptor_5) | Καταχωρεί τον καθορισμένο περιγραφέα φορτωτή εικόνας. |
| [register_loader(loader_descriptor)](#register_loader_loader_descriptor_6) | Καταχωρεί τον φορτωτή. |
| [unregister_loader(loader_descriptor)](#unregister_loader_loader_descriptor_7) | Καταργεί την καταχώρηση του φορτωτή. |


### Method: create_first_supported_loader(stream, load_options)  [static] {#create_first_supported_loader_stream_load_options_1}


```
 create_first_supported_loader(stream, load_options) 
```

Δημιουργεί τον πρώτο φορτωτή που βρέθηκε κατάλληλο για το καθορισμένο <paramref name=\"stream\" /> και προαιρετικά για το <paramref name=\"loadOptions\" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageLoader](/psd/python-net/aspose.psd/iimageloader) | Ο φορτωτής που υποστηρίζει το καθορισμένο <paramref name=\"stream\" /> και <paramref name=\"loadOptions\" /> ή null εάν δεν βρεθεί τέτοιος φορτωτής. |


### Method: get_first_supported_descriptor(stream, load_options)  [static] {#get_first_supported_descriptor_stream_load_options_2}


```
 get_first_supported_descriptor(stream, load_options) 
```

Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα κατάλληλο για το καθορισμένο <paramref name=\"stream\" /> και προαιρετικά για το <paramref name=\"loadOptions\" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Ο περιγραφέας φορτωτή που υποστηρίζει το καθορισμένο <paramref name=\"stream\" /> και <paramref name=\"loadOptions\" /> ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: get_first_supported_descriptor_by_file_format(file_format)  [static] {#get_first_supported_descriptor_by_file_format_file_format_3}


```
 get_first_supported_descriptor_by_file_format(file_format) 
```

Λαμβάνει την πρώτη υποστηριζόμενη μορφή αρχείου με βάση το όνομα τύπου της.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | Η υποστηριζόμενη μορφή αρχείου περιγραφέα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Ο πρώτος βρεθέντος περιγραφέας φορτωτή ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: get_first_supported_descriptor_by_type_name(descriptor_type_name)  [static] {#get_first_supported_descriptor_by_type_name_descriptor_type_name_4}


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
| [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Ο πρώτος βρεθέντος περιγραφέας φορτωτή ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: register(image_loader_descriptor)  [static] {#register_image_loader_descriptor_5}


```
 register(image_loader_descriptor) 
```

Καταχωρεί τον καθορισμένο περιγραφέα φορτωτή εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Ο περιγραφέας φορτωτή εικόνας. |

### Method: register_loader(loader_descriptor)  [static] {#register_loader_loader_descriptor_6}


```
 register_loader(loader_descriptor) 
```

Καταχωρεί τον φορτωτή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Ο περιγραφέας φορτωτή προς καταχώρηση. |

### Method: unregister_loader(loader_descriptor)  [static] {#unregister_loader_loader_descriptor_7}


```
 unregister_loader(loader_descriptor) 
```

Καταργεί την καταχώρηση του φορτωτή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| loader_descriptor | [IImageLoaderDescriptor](/psd/python-net/aspose.psd/iimageloaderdescriptor) | Ο περιγραφέας φορτωτή προς κατάργηση της καταχώρησης. |

