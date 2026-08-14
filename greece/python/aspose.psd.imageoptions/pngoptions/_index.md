---
title: "PngOptions Class"
type: docs
weight: 90
url: /el/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | Το προεπιλεγμένο επίπεδο συμπίεσης. |
| bit_depth | byte | r/w | Το βάθος bit. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Λαμβάνει ή ορίζει τον τύπο του χρώματος. |
| compression_level | int | r/w | Το επίπεδο συμπίεσης της εικόνας png στην κλίμακα 0-9, όπου το 9 είναι μέγιστη συμπίεση και το 0 είναι λειτουργία αποθήκευσης. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Λαμβάνει ή ορίζει τον τύπο φίλτρου που χρησιμοποιείται κατά τη διαδικασία αποθήκευσης του αρχείου png. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| progressive | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) είναι προοδευτικό. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Αρχικοποιεί ένα νέο παράδειγμα της κλάσης [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | Οι επιλογές PNG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


