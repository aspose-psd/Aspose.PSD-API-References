---
title: "Κλάση GifOptions"
type: docs
weight: 30
url: /el/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Λαμβάνει ή ορίζει το δείκτη χρώματος φόντου του GIF. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| color_resolution | byte | r/w | Λαμβάνει ή ορίζει την ανάλυση χρώματος του GIF. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| do_palette_correction | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν εφαρμόζεται διόρθωση παλέτας. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| has_trailer | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το GIF έχει trailer. |
| interlaced | bool | r/w | Αληθές εάν η εικόνα πρέπει να είναι διαπλεκόμενη. |
| is_palette_sorted | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν οι καταχωρήσεις της παλέτας είναι ταξινομημένες. |
| max_diff | int | r/w | Λαμβάνει ή ορίζει τη μέγιστη επιτρεπόμενη διαφορά pixel. Εάν είναι μεγαλύτερη του μηδενός, θα χρησιμοποιηθεί συμπίεση με απώλειες.<br/>            Η συνιστώμενη τιμή για βέλτιστη συμπίεση με απώλειες είναι 80. Το 30 είναι πολύ ελαφριά συμπίεση, το 200 είναι βαριά.<br/>            Λειτουργεί καλύτερα όταν εισάγεται μόνο μικρή απώλεια, και λόγω περιορισμού του αλγορίθμου συμπίεσης πολύ υψηλά επίπεδα απώλειας δεν προσφέρουν τόσο κέρδος.<br/>            Το εύρος των επιτρεπόμενων τιμών είναι [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| pixel_aspect_ratio | byte | r/w | Λαμβάνει ή ορίζει την αναλογία διαστάσεων pixel του GIF. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | Οι επιλογές GIF. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


