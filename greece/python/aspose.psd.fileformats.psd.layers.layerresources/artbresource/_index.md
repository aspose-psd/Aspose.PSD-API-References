---
title: "ArtBResource Κλάση"
type: docs
weight: 50
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/
---

**Summary:** The Artboard info data for [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ArtBResource

**Inheritance:** BaseArtboardInfoResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ArtBResource()](#ArtBResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης ArtBResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| artboard_background_type | int | r/w | Λαμβάνει ή ορίζει το [ArtBResource.artboard_background_type](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το [ArtBResource.color](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Αποκτά ή ορίζει τα στοιχεία [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | <inheritdoc /> |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: ArtBResource() {#ArtBResource__1}


```
 ArtBResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης ArtBResource

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

