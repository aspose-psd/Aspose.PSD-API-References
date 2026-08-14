---
title: "NvrtResource Κλάση"
type: docs
weight: 700
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---

**Summary:** Class NvrtResource. Resource of Invert Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.NvrtResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [NvrtResource()](#NvrtResource__1) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/). |
| [NvrtResource(data)](#NvrtResource_data_2) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/). |
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
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: NvrtResource() {#NvrtResource__1}


```
 NvrtResource() 
```

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/).

### Constructor: NvrtResource(data) {#NvrtResource_data_2}


```
 NvrtResource(data) 
```

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/).

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

