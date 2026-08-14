---
title: "PhflResourceVersion2 Κλάση"
type: docs
weight: 800
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/
---

**Summary:** Class PhflResource. Resource of Exposure Adjustment Layer<br/>            2 Version ( = 3 ) or ( = 2 )<br/>            12 4 bytes each for XYZ color(Only in Version 3)<br/>            10 2 bytes color space followed by 4 * 2 bytes color component(Only in Version 2)<br/>            4 Density<br/>            1 Preserve Luminosity

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PhflResourceVersion2

**Inheritance:** PhflResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PhflResourceVersion2()](#PhflResourceVersion2__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
| [PhflResourceVersion2(data)](#PhflResourceVersion2_data_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| color_space | short | r | Λαμβάνει το χώρο χρώματος. |
| component_a | short | r/w | Λαμβάνει ή ορίζει το στοιχείο A του χρώματος |
| component_b | short | r/w | Λαμβάνει ή ορίζει το στοιχείο B |
| component_l | short | r/w | Λαμβάνει ή ορίζει το στοιχείο L του χρώματος |
| density | int | r/w | Λαμβάνει ή ορίζει την πυκνότητα. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| preserve_luminosity | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν [preserve luminosity]. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
| version | short | r | Λαμβάνει την έκδοση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_rgb_color()](#get_rgb_color__1) | Λαμβάνει το χρώμα. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [set_rgb_color(color)](#set_rgb_color_color_3) | Ορίζει το χρώμα RGB. |


### Constructor: PhflResourceVersion2() {#PhflResourceVersion2__1}


```
 PhflResourceVersion2() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

### Constructor: PhflResourceVersion2(data) {#PhflResourceVersion2_data_2}


```
 PhflResourceVersion2(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Method: get_rgb_color() {#get_rgb_color__1}


```
 get_rgb_color() 
```

Λαμβάνει το χρώμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Το χρώμα RGB |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_2}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| psd_version | int | Η έκδοση PSD. |

### Method: set_rgb_color(color) {#set_rgb_color_color_3}


```
 set_rgb_color(color) 
```

Ορίζει το χρώμα RGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Το χρώμα. |

