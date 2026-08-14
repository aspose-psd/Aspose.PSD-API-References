---
title: "Lnk2Resource Κλάση"
type: docs
weight: 570
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/
---

**Summary:** Defines the class which contains information about embedded files in the PSD format image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by the indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk2Resource

**Inheritance:** LinkResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Lnk2Resource()](#Lnk2Resource__1) | Δημιουργεί μια νέα παρουσία της κλάσης [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| data_source_count | int | r | Λαμβάνει τον αριθμό των πηγών δεδομένων συνδέσμου που μπορούν να προσπελαστούν μέσω του δεικτοδότη. |
| is_empty | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία πόρου συνδέσμου είναι κενή. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Λαμβάνει το συνολικό μήκος του πόρου συνδέσμου PSD σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τα δεδομένα του μπλοκ πόρων. |


### Constructor: Lnk2Resource() {#Lnk2Resource__1}


```
 Lnk2Resource() 
```

Δημιουργεί μια νέα παρουσία της κλάσης [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/).

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει τα δεδομένα του μπλοκ πόρων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| psd_version | int | Η έκδοση PSD. |

