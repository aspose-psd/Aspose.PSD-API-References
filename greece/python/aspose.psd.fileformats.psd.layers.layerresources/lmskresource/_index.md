---
title: "Κλάση LmskResource"
type: docs
weight: 560
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---

**Summary:** The LMsk resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LmskResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LmskResource()](#LmskResource__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| color_component1 | ushort | r/w | Λαμβάνει το στοιχείο χρώματος 1. |
| color_component2 | ushort | r/w | Λαμβάνει το στοιχείο χρώματος 2. |
| color_component3 | ushort | r/w | Λαμβάνει το στοιχείο χρώματος 3. |
| color_component4 | ushort | r/w | Λαμβάνει το στοιχείο χρώματος 4. |
| color_space | [ColorSpace](/psd/python-net/aspose.psd.fileformats.psd.resources.enums/colorspace/) | r/w | Λαμβάνει το χώρο χρώματος. |
| flag | byte | r | Λαμβάνει τη σημαία. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| opacity | short | r/w | Λαμβάνει τη διαφάνεια. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: LmskResource() {#LmskResource__1}


```
 LmskResource() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/).

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

