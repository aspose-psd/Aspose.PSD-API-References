---
title: "UnitArrayStructure Κλάση"
type: docs
weight: 170
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/
---

**Summary:** Defines the UnitArrayStructure class that holds float values array and their measure unit.<br/>            It is used in the PSD file resources, usually by [ObjectArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/objectarraystructure/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.UnitArrayStructure

**Inheritance:** OSTypeStructure

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [UnitArrayStructure(key_name, unit_type, values)](#UnitArrayStructure_key_name_unit_type_values_1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| STRUCTURE_KEY [static] | int | r | Ορίζει το κλειδί 'UnFl' της [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/). |
| key | int | r | Λαμβάνει αυτό το κλειδί της δομής πίνακα μονάδων. |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το όνομα κλειδιού. |
| length | int | r | Λαμβάνει το μήκος της [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) σε bytes. |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | r/w | Λαμβάνει ή ορίζει τον τύπο μονάδας μέτρησης των τιμών της [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/). |
| value_count | int | r | Λαμβάνει τον αριθμό τιμών. |
| values | double | r/w | Λαμβάνει ή ορίζει τις τιμές της δομής πίνακα μονάδων. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_header_length()](#get_header_length__1) | Λαμβάνει το μήκος της κεφαλίδας. |
| [save(stream_container)](#save_stream_container_2) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |
| [save_without_key_name(stream_container)](#save_without_key_name_stream_container_3) | Αποθηκεύει τη δομή στο καθορισμένο δοχείο ροής. |


### Constructor: UnitArrayStructure(key_name, unit_type, values) {#UnitArrayStructure_key_name_unit_type_values_1}


```
 UnitArrayStructure(key_name, unit_type, values) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [UnitArrayStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unitarraystructure/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| key_name | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Όνομα του κλειδιού. |
| unit_type | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes) | Τύπος της μονάδας. |
| values | double | Οι τιμές. |

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

