---
title: "LevlResource Κλάση"
type: docs
weight: 490
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---

**Summary:** Class LevlResource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LevlResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LevlResource()](#LevlResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/). |
| [LevlResource(bytes)](#LevlResource_bytes_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Υποστηρίζεται σε λειτουργίες GrayScale, Duotone, RGB, CMYK, Lab color<br/>            2 bytes - Έκδοση (=2)<br/>            29 * 10 bytes - Σύνολα εγγραφών επιπέδων με 5 μικρούς ακέραιους<br/>            4 bytes - Κεφαλίδα Lvls (Ξεκινά στο δείκτη 292)<br/>            2 bytes - Έκδοση (=3)<br/>            2 bytes - Αριθμός συνολικών εγγραφών επιπέδου<br/>            10 * (Συνολικός Αριθμός - 29)<br/>            Η μηδενική λήξη του πόρου Lvls πρέπει επίσης να είναι διπλή |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
| version | short | r | Επιστρέφει την έκδοση. Η προεπιλογή είναι 2. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [get_channel(channel_index)](#get_channel_channel_index_1) | Λαμβάνει το κανάλι. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_2) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: LevlResource() {#LevlResource__1}


```
 LevlResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).

### Constructor: LevlResource(bytes) {#LevlResource_bytes_2}


```
 LevlResource(bytes) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/).<br/>            Υποστηρίζεται σε λειτουργίες GrayScale, Duotone, RGB, CMYK, Lab color<br/>            2 bytes - Έκδοση (=2)<br/>            29 * 10 bytes - Σύνολα εγγραφών επιπέδων με 5 μικρούς ακέραιους<br/>            4 bytes - Κεφαλίδα Lvls (Ξεκινά στο δείκτη 292)<br/>            2 bytes - Έκδοση (=3)<br/>            2 bytes - Αριθμός συνολικών εγγραφών επιπέδου<br/>            10 * (Συνολικός Αριθμός - 29)<br/>            Η μηδενική λήξη του πόρου Lvls πρέπει επίσης να είναι διπλή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bytes | byte | Τα bytes. |

### Method: get_channel(channel_index) {#get_channel_channel_index_1}


```
 get_channel(channel_index) 
```

Λαμβάνει το κανάλι.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| channel_index | int | Δείκτης του καναλιού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel) | Δεδομένα Επιπέδου Καναλιού |


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

