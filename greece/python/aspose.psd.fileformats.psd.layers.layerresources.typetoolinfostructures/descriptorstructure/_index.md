---
title: "DescriptorStructure Κλάση"
type: docs
weight: 40
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/
---

**Summary:** The descriptor structure

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [DescriptorStructure(key_name, class_id, class_name, structures)](#DescriptorStructure_key_name_class_id_class_name_structures_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Αναγνωρίζει το κλειδί δομής. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| class_name | string | r/w | Λαμβάνει ή ορίζει το όνομα κλάσης. |
| key | int | r | Λαμβάνει το κλειδί δομής. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| length | int | r | Λαμβάνει το μήκος της [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Λαμβάνει ή ορίζει ένα αντίγραφο ενός πίνακα δομών. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Λαμβάνει το μήκος της κεφαλίδας. |
| [save(stream_container)](#save_stream_container_2) | Αποθηκεύει τα δεδομένα. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |


### Constructor: DescriptorStructure(key_name, class_id, class_name, structures) {#DescriptorStructure_key_name_class_id_class_name_structures_1}


```
 DescriptorStructure(key_name, class_id, class_name, structures) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το όνομα του κλειδιού. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό κλάσης. |
| class_name | string | Όνομα της κλάσης. |
| structures | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Οι δομές. |

### Method: get_header_length() {#get_header_length__1}


```
 get_header_length() 
```

Λαμβάνει το μήκος της κεφαλίδας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το μήκος της κεφαλίδας |


### Method: save(stream_container) {#save_stream_container_2}


```
 save(stream_container) 
```

Αποθηκεύει τα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |

### Method: save_without_key_name(stream_container) {#save_without_key_name_stream_container_3}


```
 save_without_key_name(stream_container) 
```

Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |

