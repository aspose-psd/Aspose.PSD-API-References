---
title: "Κλάση CgEdResource"
type: docs
weight: 130
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/
---

**Summary:** Class CgEdResource. Content Generator Extra Data (Photoshop CS5)

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.CgEdResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [CgEdResource()](#CgEdResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης CgEdResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| auto | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) είναι αυτόματο. |
| φωτεινότητα | int | r/w | Λαμβάνει ή ορίζει τη φωτεινότητα. |
| αντίθεση | int | r/w | Λαμβάνει ή ορίζει την αντίθεση. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| lab_color | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται το [lab color]. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| mean_value_for_brightness_and_contrast | int | r/w | Λαμβάνει ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
| use_legacy | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται [use legacy]. |
| version | int | r/w | Λαμβάνει ή ορίζει την έκδοση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: CgEdResource() {#CgEdResource__1}


```
 CgEdResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης CgEdResource

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

