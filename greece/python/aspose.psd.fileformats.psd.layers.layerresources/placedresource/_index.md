---
title: "Κλάση PlacedResource"
type: docs
weight: 830
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| anti_alias_policy | int | r/w | Λαμβάνει ή ορίζει την πολιτική anti alias του τοποθετημένου στρώματος στην εικόνα PSD. |
| bottom | double | r/w | Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος. |
| horizontal_mesh_points | double | r/w | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| is_custom | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτού του αντικειμένου είναι προσαρμοσμένο.<br/>            Εάν είναι true, περιέχει σημεία πλέγματος. Εάν οριστεί σε false, διαγράφει τα σημεία πλέγματος. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Λαμβάνει ή ορίζει τα στοιχεία παραμόρφωσης. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| αριστερά | double | r/w | Λαμβάνει ή ορίζει την αριστερή θέση του τοποθετημένου στρώματος στο αρχείο PSD. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| page_number | int | r/w | Λαμβάνει ή ορίζει τον αριθμό σελίδας του τοποθετημένου στρώματος στο αρχείο PSD. |
| perspective | double | r/w | Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| perspective_other | double | r/w | Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Λαμβάνει ή ορίζει τον τύπο του τοποθετημένου στρώματος στο αρχείο PSD. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| δεξιά | double | r/w | Λαμβάνει ή ορίζει τη δεξιά θέση του τοποθετημένου στρώματος στο αρχείο PSD. |
| signature | int | r | Αποκτά την υπογραφή. |
| επάνω | double | r/w | Λαμβάνει ή ορίζει την άνω θέση του τοποθετημένου στρώματος στην εικόνα PSD. |
| total_pages | int | r/w | Λαμβάνει ή ορίζει τις συνολικές σελίδες του τοποθετημένου στρώματος στο αρχείο PSD. |
| transform_matrix | double | r/w | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού του τοποθετημένου στρώματος στο αρχείο PSD. |
| u_order | int | r/w | Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD. |
| unique_id | Guid | r/w | Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό του τοποθετημένου στρώματος στην εικόνα PSD. |
| v_order | int | r/w | Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD. |
| value | double | r/w | Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD. |
| version | int | r | Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κάθετων σημείων πλέγματος. |
| vertical_mesh_points | double | r/w | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


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

