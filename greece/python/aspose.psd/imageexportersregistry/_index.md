---
title: "Κλάση ImageExportersRegistry"
type: docs
weight: 2230
url: /el/python-net/aspose.psd/imageexportersregistry/
---

**Summary:** Represents the image exporters registry.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageExportersRegistry

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| registered_exporter_descriptors [static] | [IImageExporterDescriptor[]](/psd/python-net/aspose.psd/iimageexporterdescriptor) | r | Λαμβάνει τους καταχωρημένους περιγραφείς εξαγωγέα. |
| registered_formats [static] | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει τις καταχωρημένες μορφές εξαγωγής. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [create_first_supported_exporter(image, options)](#create_first_supported_exporter_image_options_1) | Δημιουργεί τον πρώτο βρεθέντα εξαγωγέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα. |
| [get_first_supported_descriptor(image, options)](#get_first_supported_descriptor_image_options_2) | Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα. |
| [register(image_exporter_descriptor)](#register_image_exporter_descriptor_3) | Καταχωρεί τον καθορισμένο περιγραφέα εξαγωγέα εικόνας. |
| [register_exporter(exporter_descriptor)](#register_exporter_exporter_descriptor_4) | Καταχωρεί τον εξαγωγέα. |
| [unregister_exporter(exporter_descriptor)](#unregister_exporter_exporter_descriptor_5) | Αποεγγράφει τον εξαγωγέα. |


### Method: create_first_supported_exporter(image, options)  [static] {#create_first_supported_exporter_image_options_1}


```
 create_first_supported_exporter(image, options) 
```

Δημιουργεί τον πρώτο βρεθέντα εξαγωγέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα προς εξαγωγή. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης που θα χρησιμοποιηθούν για την εξαγωγή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Ο εξαγωγέας που υποστηρίζει την καθορισμένη εικόνα και τις επιλογές αποθήκευσης ή null εάν δεν βρεθεί τέτοιος εξαγωγέας. |


### Method: get_first_supported_descriptor(image, options)  [static] {#get_first_supported_descriptor_image_options_2}


```
 get_first_supported_descriptor(image, options) 
```

Λαμβάνει τον πρώτο βρεθέντα υποστηριζόμενο περιγραφέα που είναι κατάλληλος για τις καθορισμένες επιλογές αποθήκευσης και την εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Η εικόνα προς εξαγωγή. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Ο περιγραφέας εξαγωγέα που υποστηρίζει την καθορισμένη εικόνα και τις επιλογές αποθήκευσης ή null εάν δεν βρεθεί τέτοιος περιγραφέας. |


### Method: register(image_exporter_descriptor)  [static] {#register_image_exporter_descriptor_3}


```
 register(image_exporter_descriptor) 
```

Καταχωρεί τον καθορισμένο περιγραφέα εξαγωγέα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Ο περιγραφέας εξαγωγέα εικόνας. |

### Method: register_exporter(exporter_descriptor)  [static] {#register_exporter_exporter_descriptor_4}


```
 register_exporter(exporter_descriptor) 
```

Καταχωρεί τον εξαγωγέα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Ο περιγραφέας εξαγωγέα για καταχώρηση. |

### Method: unregister_exporter(exporter_descriptor)  [static] {#unregister_exporter_exporter_descriptor_5}


```
 unregister_exporter(exporter_descriptor) 
```

Αποεγγράφει τον εξαγωγέα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| exporter_descriptor | [IImageExporterDescriptor](/psd/python-net/aspose.psd/iimageexporterdescriptor) | Ο περιγραφέας εξαγωγέα για αποεγγραφή. |

