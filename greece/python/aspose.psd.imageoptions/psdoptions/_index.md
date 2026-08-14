---
title: "Κλάση PsdOptions"
type: docs
weight: 100
url: /el/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Λαμβάνει ή ορίζει το χρώμα του φόντου.<br/>            Μπορεί να φαίνεται κάτω από διαφανή αντικείμενα. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| channel_bits_count | short | r/w | Λαμβάνει ή ορίζει τον αριθμό των δυαδικών ανά κανάλι χρώματος. |
| channels_count | short | r/w | Λαμβάνει ή ορίζει τον αριθμό των καναλιών χρώματος. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία χρώματος του psd. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Λαμβάνει ή ορίζει τη μέθοδο συμπίεσης του psd. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Λαμβάνει ή ορίζει την έκδοση μορφής αρχείου. Μπορεί να είναι PSD ή PSB. |
| refresh_image_preview_data | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [refresh image preview data] - επιλογή που χρησιμοποιείται για τη μεγιστοποίηση της συμβατότητας με άλλους προβολείς εικόνων PSD.<br/>            Παρακαλώ σημειώστε ότι η σχεδίαση των στρωμάτων κειμένου στην τελική διάταξη δεν υποστηρίζεται για την πλατφόρμα Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν - Remove the global text engine resource - Χρησιμοποιείται για ορισμένα αρχεία psd με στρώματα κειμένου, μόνο στην περίπτωση που δεν μπορούν να ανοιχτούν στο Adobe Photoshop μετά την επεξεργασία (κυρίως για στρώματα κειμένου με απουσία γραμματοσειρών).<br/>            Μετά τη χρήση αυτής της επιλογής, ο χρήστης πρέπει να εκτελέσει τα εξής στο αρχείο που άνοιξε στο Photoshop: Μενού "Text" -> "Process absent fonts". Μετά από αυτή τη λειτουργία, όλο το κείμενο θα εμφανιστεί ξανά.<br/>            Παρακαλώ σημειώστε ότι αυτή η λειτουργία μπορεί να προκαλέσει κάποιες αλλαγές στην τελική διάταξη. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Λαμβάνει ή ορίζει τους πόρους του psd. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| update_metadata | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [update metadata].<br/>            Εάν η τιμή είναι true, τα μεταδεδομένα θα ενημερωθούν κατά την αποθήκευση μιας εικόνας. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| version | int | r/w | Λαμβάνει ή ορίζει την έκδοση του αρχείου psd. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Απόκτηση ή ορισμός του δοχείου δεδομένων XMP |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | Η εικόνα. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Οι επιλογές. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


