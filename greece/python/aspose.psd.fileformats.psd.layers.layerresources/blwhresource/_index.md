---
title: "Κλάση BlwhResource"
type: docs
weight: 90
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Summary:** BlwhResource class is a resource of Black and White Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlwhResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [BlwhResource()](#BlwhResource__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BlwhResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| black_and_white_preset_file_name | string | r/w | Λαμβάνει ή ορίζει το όνομα αρχείου προεπιλογής ασπρόμαυρου. |
| μπλε | int | r/w | Λαμβάνει ή ορίζει την τιμή του μπλε. |
| bw_preset_kind | int | r/w | Λαμβάνει ή ορίζει την τιμή του τύπου προεπιλογής ασπρόμαυρου. |
| κυανό | int | r/w | Λαμβάνει ή ορίζει την τιμή των κυανών. |
| πράσινα | int | r/w | Λαμβάνει ή ορίζει την τιμή των πράσινων. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| ματζέντα | int | r/w | Λαμβάνει ή ορίζει την τιμή των ματζέντα. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| κόκκινα | int | r/w | Λαμβάνει ή ορίζει την τιμή των κόκκινων. |
| signature | int | r | Αποκτά την υπογραφή. |
| tint_color | int | r/w | Λαμβάνει ή ορίζει την τιμή ARGB του χρώματος Tint. |
| use_tint | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το [tint color] χρησιμοποιείται. |
| yellows | int | r/w | Λαμβάνει ή ορίζει την τιμή των yellows. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: BlwhResource() {#BlwhResource__1}


```
 BlwhResource() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης BlwhResource

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

