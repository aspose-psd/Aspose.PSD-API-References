---
title: "Κλάση CmxRasterizationOptions"
type: docs
weight: 20
url: /el/python-net/aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Summary:** the CMX exporter options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.CmxRasterizationOptions

**Inheritance:** VectorRasterizationOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης CmxRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει ένα χρώμα φόντου. |
| border_x | float | r/w | Λαμβάνει ή ορίζει το όριο X. |
| border_y | float | r/w | Λαμβάνει ή ορίζει το όριο Y. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| center_drawing | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η σχεδίαση είναι κεντρική. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει ένα χρώμα προσκηνίου. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| page_height | float | r/w | Λαμβάνει ή ορίζει το ύψος της σελίδας. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Λαμβάνει ή ορίζει το μέγεθος της σελίδας. |
| page_width | float | r/w | Λαμβάνει ή ορίζει το πλάτος της σελίδας. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| positioning | [PositioningTypes](/psd/python-net/aspose.psd.imageoptions/positioningtypes) | r/w | Λαμβάνει ή ορίζει τη θέση. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Λαμβάνει ή ορίζει τη λειτουργία εξομάλυνσης. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Λαμβάνει ή ορίζει τη συμβουλή απόδοσης κειμένου. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Αντιγράφει στο. |


### Constructor: CmxRasterizationOptions() {#CmxRasterizationOptions__1}


```
 CmxRasterizationOptions() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης CmxRasterizationOptions

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Αντιγράφει στο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | Οι επιλογές rasterization διανύσματος. |

