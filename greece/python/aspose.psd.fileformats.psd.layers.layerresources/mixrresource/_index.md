---
title: "MixrResource Κλάση"
type: docs
weight: 680
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---

**Summary:** Class MixrResource. Resource of Channel Mixer Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.MixrResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [MixrResource()](#MixrResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 χρώματα RGB ή CMYK συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 bytes of color with 2 bytes of constant. |
| [MixrResource(data)](#MixrResource_data_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 χρώματα RGB ή CMYK συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 bytes of color with 2 bytes of constant. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| monochrome | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) είναι μονόχρωμο. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
| version | short | r/w | Λαμβάνει ή ορίζει την έκδοση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_channel_info(channel_index)](#get_channel_info_channel_index_1) | Λαμβάνει τα ακατέργαστα δεδομένα πληροφοριών καναλιού. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| [set_channel_info(channel_index, value)](#set_channel_info_channel_index_value_3) | Ορίζει τις πληροφορίες καναλιού. |


### Constructor: MixrResource() {#MixrResource__1}


```
 MixrResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 χρώματα RGB ή CMYK συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 bytes of color with 2 bytes of constant.

### Constructor: MixrResource(data) {#MixrResource_data_2}


```
 MixrResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) .<br/>            Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή:<br/>            2 Version ( = 1)<br/>            2 Monochrome<br/>            20 χρώματα RGB ή CMYK συν σταθερά για τις ρυθμίσεις του μίκτη. 4 * 2 bytes of color with 2 bytes of constant.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Method: get_channel_info(channel_index) {#get_channel_info_channel_index_1}


```
 get_channel_info(channel_index) 
```

Λαμβάνει τα ακατέργαστα δεδομένα πληροφοριών καναλιού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Ακατέργαστος πίνακας byte των πληροφοριών καναλιού. |


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

### Method: set_channel_info(channel_index, value) {#set_channel_info_channel_index_value_3}


```
 set_channel_info(channel_index, value) 
```

Ορίζει τις πληροφορίες καναλιού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |
| value | byte | Η value. |

