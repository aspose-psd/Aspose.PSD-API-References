---
title: "BlncResource Κλάση"
type: docs
weight: 80
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/
---

**Summary:** BlncResource class is a resource of Color Adjustment Layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.BlncResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [BlncResource()](#BlncResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| highlights_cyan_red_balance | short | r/w | Λαμβάνει ή ορίζει το Highlights Cyan Red Balance. |
| highlights_magenta_green_balance | short | r/w | Λαμβάνει ή ορίζει το Highlights Magenta Green Balance. |
| highlights_yellow_blue_balance | short | r/w | Λαμβάνει ή ορίζει το Highlights Yellow Blue Balance. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| midtones_cyan_red_balance | short | r/w | Λαμβάνει ή ορίζει το Midtones Cyan Red Balance. |
| midtones_magenta_green_balance | short | r/w | Λαμβάνει ή ορίζει το Midtones Magenta Green Balance. |
| midtones_yellow_blue_balance | short | r/w | Λαμβάνει ή ορίζει το Midtones Yellow Blue Balance. |
| preserve_luminosity | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) διατηρεί τη φωτεινότητα. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| shadows_cyan_red_balance | short | r/w | Λαμβάνει ή ορίζει το Shadows Cyan Red Balance. |
| shadows_magenta_green_balance | short | r/w | Λαμβάνει ή ορίζει το Shadows Magenta Green Balance. |
| shadows_yellow_blue_balance | short | r/w | Λαμβάνει ή ορίζει το Shadows Yellow Blue Balance. |
| signature | int | r | Αποκτά την υπογραφή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: BlncResource() {#BlncResource__1}


```
 BlncResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/).

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

