---
title: "Κλάση PatternFillSettings"
type: docs
weight: 130
url: /el/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [link with layer]. |
| γωνία | double | r/w | Λαμβάνει ή ορίζει τη γωνία. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το χρώμα. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Ο τύπος γεμίσματος |
| horizontal_offset | int | r/w | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση. |
| linked | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/) είναι συνδεδεμένο. |
| pattern_data | int | r/w | Λαμβάνει ή ορίζει τα δεδομένα του pattern. |
| pattern_height | int | r/w | Λαμβάνει ή ορίζει το ύψος του μοτίβου. |
| pattern_id | string | r/w | Λαμβάνει ή ορίζει το αναγνωριστικό του μοτίβου. |
| pattern_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του μοτίβου. |
| pattern_width | int | r/w | Λαμβάνει ή ορίζει το πλάτος του μοτίβου. |
| point_type | string | r/w | Λαμβάνει ή ορίζει τον τύπο του σημείου. |
| scale | double | r/w | Λαμβάνει ή ορίζει την κλίμακα. |
| vertical_offset | int | r/w | Λαμβάνει ή ορίζει την κατακόρυφη μετατόπιση. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Δημιουργεί τους κόμβους πόρων LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Δημιουργεί τους κόμβους πόρων LFX2.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point_type | string | Τύπος του σημείου. |
| color | [Color](/psd/python-net/aspose.psd/color) | Το χρώμα. |
| pattern_name | string | Όνομα του μοτίβου. |
| αναγνωριστικό | string | Το αναγνωριστικό. |
| scale | double | Η κλίμακα. |
| συνδεδεμένο | bool | αν οριστεί σε <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Η μετατόπιση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Λίστα των [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


