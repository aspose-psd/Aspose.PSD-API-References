---
title: "IopaResource Κλάση"
type: docs
weight: 440
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/
---

**Summary:** Class IopaResource.<br/>            This resource contains information about the fill opacity property from the layer style form

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IopaResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [IopaResource()](#IopaResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
| [IopaResource(data)](#IopaResource_data_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| διαφάνεια_γέμισης | byte | r/w | Λαμβάνει ή ορίζει τη διαφάνεια γεμίσματος. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: IopaResource() {#IopaResource__1}


```
 IopaResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

### Constructor: IopaResource(data) {#IopaResource_data_2}


```
 IopaResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα ακατέργαστα δεδομένα byte. |

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

