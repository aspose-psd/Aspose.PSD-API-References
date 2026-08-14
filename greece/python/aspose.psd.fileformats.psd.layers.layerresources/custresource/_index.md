---
title: "CustResource Κλάση"
type: docs
weight: 230
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/
---

**Summary:** Class CustResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CustResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [CustResource()](#CustResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) . |
| [CustResource(data)](#CustResource_data_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| layer_created_date_time | datetime | r/w | Λαμβάνει ή ορίζει την ημερομηνία δημιουργίας του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: CustResource() {#CustResource__1}


```
 CustResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) .

### Constructor: CustResource(data) {#CustResource_data_2}


```
 CustResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) .

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

