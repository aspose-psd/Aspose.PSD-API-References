---
title: "Κλάση BritResource"
type: docs
weight: 120
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/
---

**Summary:** Class BritResource. Resource of Brightness/Contrast Adjustment Layer

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BritResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [BritResource()](#BritResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color)](#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/). |
| [BritResource(bytes)](#BritResource_bytes_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή:<br/>            2 Φωτεινότητα<br/>            2 Αντίθεση<br/>            2 Μέση τιμή για φωτεινότητα και αντίθεση<br/>            1 Μόνο χρώμα Lab<br/>            Δεν χρησιμοποιείται σε σύγχρονα PSD (CS5 και άνω) όπου υπάρχει το CgEd. Το CgEd αποθηκεύει ιδιότητες πληροφοριών |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| φωτεινότητα | short | r/w | Λαμβάνει ή ορίζει τη φωτεινότητα. |
| αντίθεση | short | r/w | Λαμβάνει ή ορίζει την αντίθεση. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| lab_color | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [lab color]. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| mean_value_for_brightness_and_contrast | short | r/w | Λαμβάνει ή ορίζει τη μέση τιμή για τη φωτεινότητα και την αντίθεση. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: BritResource() {#BritResource__1}


```
 BritResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

### Constructor: BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) {#BritResource_brightness_contrast_mean_value_for_brightness_and_contrast_lab_color_2}


```
 BritResource(brightness, contrast, mean_value_for_brightness_and_contrast, lab_color) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| φωτεινότητα | short | Η φωτεινότητα. |
| αντίθεση | short | Η αντίθεση. |
| mean_value_for_brightness_and_contrast | short | Η μέση τιμή για φωτεινότητα και αντίθεση |
| lab_color | bool | αν οριστεί σε <c>true</c> [χρώμα Lab]. |

### Constructor: BritResource(bytes) {#BritResource_bytes_3}


```
 BritResource(bytes) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/).<br/>            Η προδιαγραφή μορφής PSD περιέχει την ακόλουθη περιγραφή:<br/>            2 Φωτεινότητα<br/>            2 Αντίθεση<br/>            2 Μέση τιμή για φωτεινότητα και αντίθεση<br/>            1 Μόνο χρώμα Lab<br/>            Δεν χρησιμοποιείται σε σύγχρονα PSD (CS5 και άνω) όπου υπάρχει το CgEd. Το CgEd αποθηκεύει ιδιότητες πληροφοριών

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bytes | byte | Τα bytes. |

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

