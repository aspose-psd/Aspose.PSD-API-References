---
title: "VibAResource Κλάση"
type: docs
weight: 1090
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/
---

**Summary:** VibA Resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.VibAResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [VibAResource()](#VibAResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| κορεσμός | int | r/w | Λαμβάνει ή ορίζει την τιμή κορεσμού |
| signature | int | r | Αποκτά την υπογραφή. |
| ζωντάνια | int | r/w | Λαμβάνει ή ορίζει την τιμή ζωντάνιας |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: VibAResource() {#VibAResource__1}


```
 VibAResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/).

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

