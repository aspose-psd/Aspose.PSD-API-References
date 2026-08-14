---
title: "TypeToolInfo6Resource Κλάση"
type: docs
weight: 990
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| bottom | int | r/w | Λαμβάνει ή ορίζει τη θέση του κάτω. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| class_name | string | r/w | Λαμβάνει ή ορίζει το όνομα κλάσης. |
| descriptor_version | int | r/w | Λαμβάνει ή ορίζει την έκδοση του descriptor version. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Λαμβάνει ή ορίζει τα στοιχεία. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| αριστερά | int | r/w | Λαμβάνει ή ορίζει τη θέση αριστερά. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| δεξιά | int | r/w | Λαμβάνει ή ορίζει τη θέση δεξιά. |
| signature | int | r | Αποκτά την υπογραφή. |
| text_version | short | r/w | Λαμβάνει ή ορίζει την έκδοση κειμένου. |
| επάνω | int | r/w | Λαμβάνει ή ορίζει τη θέση του πάνω  μέρους. |
| transform_matrix | double | r/w | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| version | short | r/w | Λαμβάνει ή ορίζει την έκδοση του εργαλείου τύπου. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό κλάσης. |
| warp_class_name | string | r/w | Λαμβάνει ή ορίζει το όνομα της κλάσης warp. |
| warp_descriptor_version | int | r/w | Λαμβάνει ή ορίζει την έκδοση του περιγραφέα warp. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| warp_version | short | r/w | Λαμβάνει ή ορίζει την έκδοση του warp. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το αναγνωριστικό της κλάσης. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Το ID της κλάσης warp. |

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

