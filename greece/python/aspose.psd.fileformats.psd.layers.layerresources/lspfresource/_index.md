---
title: "LspfResource Κλάση"
type: docs
weight: 640
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/
---

**Summary:** Layer protected settings

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.LspfResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LspfResource()](#LspfResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
| [LspfResource(data)](#LspfResource_data_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) .<br/>            Με προσαρμοσμένη ή άγνωστη τιμή |
| [LspfResource(is_transparency_protected, is_composite_protected, is_position_protected)](#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών του εργαλείου τύπου 1819504742 |
| is_composite_protected | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι προστατευμένη από σύνθεση. |
| is_position_protected | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι προστατευμένη ως προς τη θέση. |
| is_transparency_protected | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι προστατευμένη ως προς τη διαφάνεια. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| lock_type | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype) | r/w | Λαμβάνει ή ορίζει τον τύπο του κλειδώματος. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: LspfResource() {#LspfResource__1}


```
 LspfResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

### Constructor: LspfResource(data) {#LspfResource_data_2}


```
 LspfResource(data) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) .<br/>            Με προσαρμοσμένη ή άγνωστη τιμή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα δεδομένα του πόρου. |

### Constructor: LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) {#LspfResource_is_transparency_protected_is_composite_protected_is_position_protected_3}


```
 LspfResource(is_transparency_protected, is_composite_protected, is_position_protected) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| is_transparency_protected | bool | αν οριστεί σε <c>true</c> [είναι προστατευμένο από διαφάνεια]. |
| is_composite_protected | bool | αν οριστεί σε <c>true</c> [είναι προστατευμένο από σύνθεση]. |
| is_position_protected | bool | αν οριστεί σε <c>true</c> [είναι προστατευμένο από θέση]. |

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

