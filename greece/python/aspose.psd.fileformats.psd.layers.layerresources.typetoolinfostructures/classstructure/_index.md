---
title: "ClassStructure Κλάση"
type: docs
weight: 30
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/
---

**Summary:** The class structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.ClassStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ClassStructure(key_name, class_id, structure_key)](#ClassStructure_key_name_class_id_structure_key_1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| STRUCTURE_KEY_CLSS [static] | int | r | Αναγνωρίζει το κλειδί δομής. |
| STRUCTURE_KEY_GLBC [static] | int | r | Αναγνωρίζει το κλειδί δομής. |
| STRUCTURE_KEY_TYPE [static] | int | r | Αναγνωρίζει το κλειδί δομής. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| class_name | string | r/w | Λαμβάνει ή ορίζει το όνομα κλάσης. |
| key | int | r | Λαμβάνει το κλειδί δομής. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| length | int | r | Λαμβάνει το μήκος της [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Λαμβάνει το μήκος της κεφαλίδας. |
| [save(stream_container)](#save_stream_container_2) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |


### Constructor: ClassStructure(key_name, class_id, structure_key) {#ClassStructure_key_name_class_id_structure_key_1}


```
 ClassStructure(key_name, class_id, structure_key) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [ClassStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/classstructure/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Όνομα του κλειδιού. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό της κλάσης. |
| structure_key | int | Το κλειδί της δομής. |

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

