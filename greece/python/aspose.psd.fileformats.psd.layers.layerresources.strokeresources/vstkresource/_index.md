---
title: "Κλάση VstkResource"
type: docs
weight: 40
url: /el/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Η υπογραφή πόρου ειδική για PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Η κοινή υπογραφή πόρου. |
| TYPE_TOOL_KEY [static] | int | r | Το κλειδί πληροφοριών εργαλείου τύπου. |
| fill_enabled | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το γέμισμα Stroke είναι ενεργό. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Αποκτά ή ορίζει τις ρυθμίσεις Fill του Stroke. |
| key | int | r | Αποκτά το κλειδί πόρου του επιπέδου. |
| μήκος | int | r | Αποκτά το μήκος του πόρου του επιπέδου σε bytes. |
| psd_version | int | r | Αποκτά την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. Το 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| signature | int | r | Αποκτά την υπογραφή. |
| stroke_enabled | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το εφέ stroke είναι ενεργό. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία ανάμειξης Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Λαμβάνει ή ορίζει την οντότητα Stroke. Η ιδιότητα καθορίζει τις ρυθμίσεις γεμίσματος του stroke. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Αποκτά ή ορίζει την ευθυγράμμιση γραμμής του στυλ Stroke. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Λαμβάνει ή ορίζει τον τύπο του άκρου γραμμής του στυλ stroke. |
| stroke_style_line_cap_width | double | r/w | Λαμβάνει ή ορίζει το πλάτος άκρου γραμμής Stroke. |
| stroke_style_line_dash_offset | int | r/w | Λαμβάνει ή ορίζει την απόσταση διακεκομμένης γραμμής του στυλ stroke. |
| stroke_style_line_dash_set | double | r/w | Αποκτά ή ορίζει τον πίνακα των παύλων γραμμής. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Λαμβάνει ή ορίζει τον τύπο ένωσης γραμμής του στυλ Stroke. |
| stroke_style_line_width | double | r/w | Λαμβάνει ή ορίζει το πλάτος γραμμής Stroke. |
| stroke_style_miter_limit | double | r/w | Λαμβάνει ή ορίζει το όριο μύτης του στυλ stroke. |
| stroke_style_opacity | int | r/w | Λαμβάνει ή ορίζει τη διαφάνεια του στυλ Stroke (0-100%). |
| stroke_style_resolution | double | r/w | Λαμβάνει ή ορίζει την ανάλυση στυλ Stroke. |
| stroke_style_scale_lock | bool | r/w | Λαμβάνει ή ορίζει το κλείδωμα κλίμακας στυλ Stroke. |
| stroke_style_stroke_adjust | bool | r/w | Λαμβάνει ή ορίζει τη ρύθμιση Stroke. |
| stroke_style_version | int | r/w | Λαμβάνει ή ορίζει την έκδοση stroke style version. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης VstkResource

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

