---
title: "Txt2Resource Κλάση"
type: docs
weight: 970
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Δημιουργεί μια νέα παρουσία της κλάσης Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| δεδομένα | byte | r/w | Λαμβάνει ή ορίζει τα δεδομένα. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Προσθέτει την εγγραφή κειμένου στο Resource και επιστρέφει το id της εγγραφής κειμένου. |
| [get_text_data()](#get_text_data__2) | Ανακτά την εγγραφή κειμένου από τα δεδομένα του resource. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Αποθηκεύει το καθορισμένο κοντέινερ ροής. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Δημιουργεί μια νέα παρουσία της κλάσης Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Προσθέτει την εγγραφή κειμένου στο Resource και επιστρέφει το id της εγγραφής κειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | string | Το κείμενο της εγγραφής. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Τα όρια. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Επιστρέφει το Id της εγγραφής κειμένου για το resource |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Ανακτά την εγγραφή κειμένου από τα δεδομένα του resource.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Πίνακας εγγραφής κειμένου |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει το καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| psd_version | int | Η έκδοση PSD. |

