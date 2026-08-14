---
title: "LclrResource Κλάση"
type: docs
weight: 470
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---

**Summary:** Class LclrResource.<br/>            This resource contains information about color of layer in layers' list is PS. It's only

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LclrResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LclrResource()](#LclrResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(color)](#LclrResource_color_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
| [LclrResource(data)](#LclrResource_data_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | r/w | Λαμβάνει ή ορίζει το χρώμα της στρώσης. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: LclrResource() {#LclrResource__1}


```
 LclrResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

### Constructor: LclrResource(color) {#LclrResource_color_2}


```
 LclrResource(color) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum) | Το χρώμα. |

### Constructor: LclrResource(data) {#LclrResource_data_3}


```
 LclrResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/).

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

