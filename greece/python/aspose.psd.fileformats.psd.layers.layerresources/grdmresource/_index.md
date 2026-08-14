---
title: "GrdmResource Κλάση"
type: docs
weight: 340
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| color_model | short | r/w | Μοντέλο χρώματος.<br/>            Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε το 'Color Model' σε RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| δισδιάταξη | bool | r/w | Το gradient είναι δισδιατεμένο. |
| expansion_count | short | r/w | Αριθμός επέκτασης ( = 2 για Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Λειτουργία για αυτό το gradient<br/>            Καθορίζει το 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Όνομα του gradient: συμβολοσειρά Unicode, με συμπλήρωση. |
| παρεμβολή | short | r/w | Παρεμβολή. Καθορίζει την ομαλότητα, όταν 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Μέγιστο χρώμα του μορφότυπου PixelDataFormat.Rgba64Bpp.<br/>            Το χρώμα έχει κανάλια ARGB, κάθε κανάλι είναι 16bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Ελάχιστο χρώμα του μορφότυπου PixelDataFormat.Rgba64Bpp.<br/>            Το χρώμα έχει κανάλια ARGB, κάθε κανάλι είναι 16bit. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| αντίστροφο | bool | r/w | Το gradient είναι αντίστροφο. |
| rnd_number_seed | int | r/w | Ο σπόρος τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για το gradient Θορύβου. |
| roughness | int | r/w | Συντελεστής τραχύτητας<br/>            Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε το 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Σημαία για εμφάνιση διαφάνειας<br/>            Όταν 'Gradient type' = 'Noise', μπορούμε να ορίσουμε το 'Add transparency' σε true. |
| signature | int | r | Αποκτά την υπογραφή. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| use_vector_color | short | r/w | Σημαία για τη χρήση διανυσματικού χρώματος. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τα δεδομένα του πόρου στο καθορισμένο κοντέινερ ροής. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| psd_version | int | Η έκδοση psd του πόρου. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει τα δεδομένα του πόρου στο καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| psd_version | int | Η έκδοση PSD. |

