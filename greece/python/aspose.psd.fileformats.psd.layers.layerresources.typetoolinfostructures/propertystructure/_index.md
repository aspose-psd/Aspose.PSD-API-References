---
title: "PropertyStructure Κλάση"
type: docs
weight: 130
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/
---

**Summary:** The property structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.PropertyStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PropertyStructure(key_name, class_id, key_id)](#PropertyStructure_key_name_class_id_key_id_1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Αναγνωρίζει το κλειδί δομής. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| class_name | string | r/w | Λαμβάνει ή ορίζει το όνομα κλάσης. |
| key | int | r | Λαμβάνει το κλειδί δομής. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό κλειδιού. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| length | int | r | Λαμβάνει το μήκος της [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Λαμβάνει το μήκος της κεφαλίδας. |
| [save(stream_container)](#save_stream_container_2) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |


### Constructor: PropertyStructure(key_name, class_id, key_id) {#PropertyStructure_key_name_class_id_key_id_1}


```
 PropertyStructure(key_name, class_id, key_id) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PropertyStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/propertystructure/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Όνομα του κλειδιού. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό της κλάσης. |
| key_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό του κλειδιού. |

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

Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής.

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

