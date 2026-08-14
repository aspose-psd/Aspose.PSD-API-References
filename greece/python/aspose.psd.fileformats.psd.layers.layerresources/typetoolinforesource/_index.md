---
title: "Κλάση TypeToolInfoResource"
type: docs
weight: 1000
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| a_component | short | r/w | Λαμβάνει ή ορίζει ένα συστατικό. |
| b_component | short | r/w | Λαμβάνει ή ορίζει το b συστατικό. |
| character_count | int | r/w | Λαμβάνει ή ορίζει τον αριθμό χαρακτήρων. |
| color_space_value | short | r/w | Λαμβάνει ή ορίζει την τιμή του χρωματικού χώρου. |
| font_version | short | r/w | Λαμβάνει ή ορίζει την έκδοση της γραμματοσειράς. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Λαμβάνει ή ορίζει τις γραμματοσειρές. |
| fonts_count | short | r | Λαμβάνει τον αριθμό των γραμματοσειρών. |
| g_component | short | r/w | Λαμβάνει ή ορίζει το g συστατικό. |
| horizontal_placement | int | r/w | Λαμβάνει ή ορίζει την οριζόντια τοποθέτηση. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| line_count | short | r | Λαμβάνει τον αριθμό γραμμών. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Λαμβάνει ή ορίζει τις γραμμές. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| r_component | short | r/w | Λαμβάνει ή ορίζει το συστατικό r. |
| scale_factor | int | r/w | Λαμβάνει ή ορίζει τον συντελεστή κλίμακας. |
| selection_end | int | r/w | Λαμβάνει ή ορίζει το τέλος επιλογής. |
| selection_start | int | r/w | Λαμβάνει ή ορίζει την αρχή επιλογής. |
| signature | int | r | Αποκτά την υπογραφή. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Λαμβάνει ή ορίζει τα στυλ γραμματοσειράς. |
| styles_count | short | r | Λαμβάνει τον αριθμό των στυλ. |
| transform_matrix | double | r/w | Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού. |
| type_value | short | r/w | Λαμβάνει ή ορίζει την τιμή τύπου. |
| version | short | r/w | Λαμβάνει ή ορίζει την έκδοση. |
| vertical_placement | int | r/w | Λαμβάνει ή ορίζει την κατακόρυφη τοποθέτηση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει το καθορισμένο κοντέινερ ροής. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Αποθηκεύει το καθορισμένο κοντέινερ ροής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Το container ροής. |
| psd_version | int | Η έκδοση PSD. |

