---
title: "GradientFillSettings Κλάση"
type: docs
weight: 50
url: /el/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Αρχικοποιεί μια νέα παρουσία της [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) κλάσης. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [align with layer]. |
| γωνία | double | r/w | Λαμβάνει ή ορίζει τη γωνία. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει το χρώμα. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Λαμβάνει ή ορίζει τα σημεία χρώματος. |
| dither | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) είναι dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Ο τύπος γεμίσματος. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Λαμβάνει τη λειτουργία για αυτό το gradient.<br/>            Καθορίζει 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του gradient. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Λαμβάνει ή ορίζει τον τύπο του gradient. |
| horizontal_offset | double | r/w | Λαμβάνει ή ορίζει την οριζόντια μετατόπιση σε ποσοστό. |
| παρεμβολή | short | r/w | Παρεμβολή. Καθορίζει την ομαλότητα, όταν 'Gradient Type' = 'Solid'. Εύρος τιμών: 0-4096. |
| reverse | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) είναι reverse. |
| scale | int | r/w | Λαμβάνει ή ορίζει την κλίμακα. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Λαμβάνει ή ορίζει τα σημεία διαφάνειας. |
| vertical_offset | double | r/w | Λαμβάνει ή ορίζει την κάθετη μετατόπιση σε ποσοστό. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Προσθέτει το σημείο χρώματος. |
| [add_transparency_point()](#add_transparency_point__2) | Προσθέτει το σημείο χρώματος. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Δημιουργεί τους κόμβους πόρων LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | Αφαιρεί το σημείο χρώματος. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Αφαιρεί το σημείο διαφάνειας. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Αρχικοποιεί μια νέα παρουσία της [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) κλάσης.

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Προσθέτει το σημείο χρώματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Δημιουργήθηκε σημείο χρώματος |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Προσθέτει το σημείο χρώματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Δημιουργήθηκε σημείο διαφάνειας |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Δημιουργεί τους κόμβους πόρων LFX2.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Δημιουργήθηκε λίστα του [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Αφαιρεί το σημείο χρώματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Το σημείο. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Αφαιρεί το σημείο διαφάνειας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Το σημείο. |

