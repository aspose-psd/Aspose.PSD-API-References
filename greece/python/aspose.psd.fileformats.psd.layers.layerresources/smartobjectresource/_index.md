---
title: "SmartObjectResource Κλάση"
type: docs
weight: 900
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| anti_alias_policy | int | r/w | Λαμβάνει ή ορίζει την πολιτική anti alias των δεδομένων στρώσης smart object στην εικόνα PSD. |
| bottom | double | r/w | Λαμβάνει ή ορίζει τη θέση κάτω του τοποθετημένου στρώματος στην εικόνα PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Λαμβάνει ή ορίζει τα όρια του τοποθετημένου στρώματος στο αρχείο PSD. |
| comp | int | r/w | Λαμβάνει ή ορίζει την τιμή comp των δεδομένων στρώσης smart object στο αρχείο PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| comp_id | int | r/w | Λαμβάνει ή ορίζει το ID του τρέχοντος επιλεγμένου comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν έχει επιλεγεί κανένα.<br/>            Τα comps είναι συνθέσεις μιας διάταξης σελίδας που μπορούν να δημιουργήσουν οι σχεδιαστές. Χρησιμοποιώντας layer comps, μπορείτε να δημιουργήσετε, διαχειριστείτε και προβάλετε πολλαπλές εκδόσεις<br/>            μιας διάταξης σε ένα ενιαίο αρχείο Adobe� Photoshop�. Ένα layer comp είναι ένα στιγμιότυπο μιας κατάστασης του πίνακα Layers. Τα layer comps αποθηκεύουν τρεις τύπους επιλογών στρώσης αλλά<br/>            αυτή η ιδιότητα λαμβάνει το αναγνωριστικό επιλογής Layer Comp για τη στρώση smart object στο αρχείο PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| crop | int | r/w | Λαμβάνει ή ορίζει το crop των δεδομένων στρώσης smart object στην εικόνα PSD. |
| duration_denominator | int | r/w | Λαμβάνει ή ορίζει τον παρονομαστή της διάρκειας. |
| duration_numerator | int | r/w | Λαμβάνει ή ορίζει τον αριθμητή της διάρκειας. |
| frame_count | int | r/w | Λαμβάνει ή ορίζει τον αριθμό πλαισίων των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| frame_step_denominator | int | r/w | Λαμβάνει ή ορίζει τον παρονομαστή του βήματος πλαισίου. |
| frame_step_numerator | int | r/w | Λαμβάνει ή ορίζει τον αριθμητή του βήματος πλαισίου. |
| height | double | r/w | Λαμβάνει ή ορίζει το ύψος. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των οριζόντιων σημείων πλέγματος. |
| horizontal_mesh_points | double | r/w | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| is_custom | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στυλ παραμόρφωσης αυτού του αντικειμένου είναι προσαρμοσμένο.<br/>            Εάν είναι true, περιέχει σημεία πλέγματος. Εάν οριστεί σε false, διαγράφει τα σημεία πλέγματος. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Λαμβάνει ή ορίζει τα στοιχεία περιγραφέα των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| αριστερά | double | r/w | Λαμβάνει ή ορίζει την αριστερή θέση του τοποθετημένου στρώματος στο αρχείο PSD. |
| μήκος | int | r | Λαμβάνει το μήκος του πόρου έξυπνου αντικειμένου σε bytes. |
| non_affine_transform_matrix | double | r/w | Λαμβάνει ή ορίζει τον μη-αφινικό πίνακα μετασχηματισμού των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| original_comp_id | int | r | Λαμβάνει το αρχικό ID του τρέχοντος επιλεγμένου Comp για το υπο-έγγραφο, το οποίο θα είναι -1 εάν δεν υπάρχει επιλογή.<br/>            Αυτή η ιδιότητα λαμβάνει το αρχικό αναγνωριστικό επιλογής layer Comp για τη στρώση έξυπνου αντικειμένου στο αρχείο PSD.<br/>            <see href=\"https://helpx.adobe.com/photoshop/using/layer-comps.html\">Layer comps in Smart Objects</see> |
| page_number | int | r/w | Λαμβάνει ή ορίζει τον αριθμό σελίδας των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| perspective | double | r/w | Λαμβάνει ή ορίζει την τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| perspective_other | double | r/w | Λαμβάνει ή ορίζει την άλλη τιμή προοπτικής του τοποθετημένου στρώματος στο αρχείο PSD. |
| placed_id | Guid | r/w | Λαμβάνει ή ορίζει το μοναδικό αναγνωριστικό αυτών των δεδομένων στρώσης έξυπνου αντικειμένου στην εικόνα PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Λαμβάνει ή ορίζει τον τύπο των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| resolution | double | r/w | Λαμβάνει ή ορίζει την ανάλυση των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Λαμβάνει ή ορίζει τη μονάδα μέτρησης της ανάλυσης των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| δεξιά | double | r/w | Λαμβάνει ή ορίζει τη δεξιά θέση του τοποθετημένου στρώματος στο αρχείο PSD. |
| signature | int | r | Αποκτά την υπογραφή. |
| επάνω | double | r/w | Λαμβάνει ή ορίζει την άνω θέση του τοποθετημένου στρώματος στην εικόνα PSD. |
| total_pages | int | r/w | Λαμβάνει ή ορίζει τον συνολικό αριθμό σελίδων των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| transform_matrix | double | r/w | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού των δεδομένων στρώσης έξυπνου αντικειμένου στο αρχείο PSD. |
| u_order | int | r/w | Λαμβάνει ή ορίζει την τιμή σειράς U του τοποθετημένου στρώματος στο αρχείο PSD. |
| unique_id | Guid | r/w | Λαμβάνει ή ορίζει το παγκόσμιο μοναδικό αναγνωριστικό των δεδομένων στρώσης έξυπνου αντικειμένου [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) στην εικόνα PSD. |
| v_order | int | r/w | Λαμβάνει ή ορίζει την τιμή σειράς V του τοποθετημένου στρώματος στο αρχείο PSD. |
| value | double | r/w | Λαμβάνει ή ορίζει την τιμή παραμόρφωσης του τοποθετημένου στρώματος στην εικόνα PSD. |
| version | int | r | Λαμβάνει την έκδοση του τοποθετημένου στρώματος στο αρχείο PSD, συνήθως 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Λαμβάνει ή ορίζει τη μονάδα μέτρησης των κάθετων σημείων πλέγματος. |
| vertical_mesh_points | double | r/w | Λαμβάνει ή ορίζει τα οριζόντια σημεία πλέγματος του τοποθετημένου στρώματος στο αρχείο PSD. |
| width | double | r/w | Λαμβάνει ή ορίζει το πλάτος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο του έξυπνου αντικειμένου στο καθορισμένο κοντέινερ ροής. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει τον πόρο του έξυπνου αντικειμένου στο καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το κοντέινερ ροής στο οποίο θα αποθηκευτεί. |
| psd_version | int | Η έκδοση PSD. |

