---
title: "Κλάση Hue2Resource"
type: docs
weight: 350
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/
---

**Summary:** Class Hue2Resource. Resource of Exposure Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Hue2Resource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Hue2Resource()](#Hue2Resource__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class. |
| [Hue2Resource(data)](#Hue2Resource_data_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| colorize | bool | r/w | Επιστρέφει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) είναι χρωματισμένο. |
| hue | short | r/w | Επιστρέφει ή ορίζει την κύρια απόχρωση. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| lightness | short | r/w | Επιστρέφει ή ορίζει τη κύρια φωτεινότητα. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| ranges | [ColorRangeHsl[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) | r | Επιστρέφει τις περιοχές του στρώματος προσαρμογής Απόχρωσης/Κορεσμού.<br/>            Οι περιοχές στο PS μπορούν να αλλάξουν ονόματα εάν η περιοχή αλλάξει, επομένως πρέπει να δουλεύουμε με βάση το ευρετήριο |
| κορεσμός | short | r/w | Επιστρέφει ή ορίζει τον κύριο κορεσμό. |
| signature | int | r | Αποκτά την υπογραφή. |
| version | short | r | Επιστρέφει την έκδοση. Η προεπιλογή είναι 2. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: Hue2Resource() {#Hue2Resource__1}


```
 Hue2Resource() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class.

### Constructor: Hue2Resource(data) {#Hue2Resource_data_2}


```
 Hue2Resource(data) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) class.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| psd_version | int | Η έκδοση PSD. |

