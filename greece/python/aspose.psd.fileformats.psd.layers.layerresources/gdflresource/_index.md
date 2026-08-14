---
title: "GdFlResource Κλάση"
type: docs
weight: 330
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| align_with_layer | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| γωνία | double | r/w | Λαμβάνει ή ορίζει τη γωνία. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει το χρώμα του RGB. |
| color_model | string | r/w | Μοντέλο Χρώματος - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Ανακτά τα σημεία χρώματος. |
| dither | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) είναι dither. |
| gradient_interval | double | r/w | Λαμβάνει ή ορίζει το διάστημα του gradient. |
| gradient_mode | string | r/w | Λειτουργία για αυτό το gradient.<br/>            Determines 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| gradient_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του gradient. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| horizontal_offset | double | r/w | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Μέγιστο χρώμα του PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Ελάχιστο χρώμα του PixelDataFormat. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| reverse | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) είναι αντίστροφο. |
| rnd_number_seed | int | r/w | Ο σπόρος τυχαίου αριθμού που χρησιμοποιείται για τη δημιουργία χρωμάτων για το gradient Θορύβου. |
| roughness | int | r/w | Συντελεστής τραχύτητας. |
| scale | int | r/w | Λαμβάνει ή ορίζει την κλίμακα. |
| show_transparency | bool | r/w | Σημαία για την εμφάνιση διαφάνειας. |
| signature | int | r | Αποκτά την υπογραφή. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Ανακτά τα σημεία διαφάνειας. |
| use_vector_color | bool | r/w | Σημαία για τη χρήση διανυσματικού χρώματος. |
| vertical_offset | double | r/w | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης GdFlResource

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

