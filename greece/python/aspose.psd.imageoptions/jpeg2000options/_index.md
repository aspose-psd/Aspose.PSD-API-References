---
title: "Jpeg2000Options Κλάση"
type: docs
weight: 50
url: /el/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Λαμβάνει ή ορίζει τον κωδικοποιητή JPEG2000 |
| comments | string | r/w | Λαμβάνει ή ορίζει τα δείκτες σχολίων Jpeg. |
| compression_ratios | int | r/w | Λαμβάνει ή ορίζει τον Πίνακα των συντελεστών συμπίεσης.<br/>            Διαφορετικοί συντελεστές συμπίεσης για διαδοχικά στρώματα.<br/>            Ο ρυθμός που καθορίζεται για κάθε επίπεδο ποιότητας είναι ο επιθυμητός<br/>            συντελεστής συμπίεσης.<br/>            Απαιτούνται μειωμένοι συντελεστές. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| irreversible | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν χρησιμοποιείται η μη αντιστρέψιμη DWT 9-7 (true) ή η χωρίς απώλειες DWT 5-3 συμπίεση (προεπιλογή). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Οι επιλογές μορφής αρχείου Jpeg2000 από τις οποίες θα αντιγραφούν οι ρυθμίσεις. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


