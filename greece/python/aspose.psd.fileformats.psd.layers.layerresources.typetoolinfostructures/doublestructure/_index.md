---
title: "DoubleStructure Κλάση"
type: docs
weight: 50
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/doublestructure/
---

**Summary:** The double structure.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DoubleStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [DoubleStructure(key_name)](#DoubleStructure_key_name_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [DoubleStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/doublestructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Αναγνωρίζει το κλειδί δομής. |
| key | int | r | Λαμβάνει το κλειδί δομής. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| length | int | r | Λαμβάνει το μήκος της [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
| value | double | r/w | Λαμβάνει ή ορίζει τη τιμή double. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Λαμβάνει το μήκος της κεφαλίδας. |
| [save(stream_container)](#save_stream_container_2) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |


### Constructor: DoubleStructure(key_name) {#DoubleStructure_key_name_1}


```
 DoubleStructure(key_name) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [DoubleStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/doublestructure/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το όνομα του κλειδιού. |

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

