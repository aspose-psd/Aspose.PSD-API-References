---
title: "Κλάση VscgResource"
type: docs
weight: 30
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---

**Summary:** Vector Stroke Content Data resource.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VscgResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [VscgResource()](#VscgResource__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης VscgResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r | Αποκτά ή ορίζει τον πίνακα των στοιχείων δομής.<br/>            **Warning:** Οι τιμές του πίνακα `Items` πρέπει να ταιριάζουν με την ιδιότητα `KeyForData`, η οποία καθορίζει τον τύπο των ρυθμίσεων γεμίσματος που αποθηκεύονται στις δομές μέσα στο `Items`. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| key_for_data | int | r | Αποκτά ακέραιο κλειδί που ορίζει τι είδους ρυθμίσεις γεμίσματος αποθηκεύονται στον πόρο:<br/>            * Color - 0x536f436f - SoCoResource.TypeToolKey<br/>            * Gradient - 0x4764466c - GdFlResource.TypeToolKey<br/>            * Pattern - 0x5074466c - PtFlResource.TypeToolKey<br/>            Warning! Η τιμή της ιδιότητας KeyForData πρέπει να ταιριάζει με τον τύπο των ρυθμίσεων γεμίσματος που αποθηκεύονται στις δομές Items. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: VscgResource() {#VscgResource__1}


```
 VscgResource() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης VscgResource

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

