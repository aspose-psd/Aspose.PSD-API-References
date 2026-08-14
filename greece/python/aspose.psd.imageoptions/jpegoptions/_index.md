---
title: "Κλάση JpegOptions"
type: docs
weight: 60
url: /el/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Λαμβάνει ή ορίζει τα bits ανά κανάλι για εικόνα jpeg χωρίς απώλειες. Τώρα υποστηρίζουμε από 2 έως 8 bits ανά κανάλι. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Ο προορισμός προφίλ χρώματος CMYK για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να είναι σε ζεύγος με το RGBColorProfile για σωστή μετατροπή χρώματος. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Λαμβάνει ή ορίζει τον τύπο χρώματος για την εικόνα jpeg. |
| σχόλιο | string | r/w | Λαμβάνει ή ορίζει το σχόλιο του αρχείου jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Λαμβάνει ή ορίζει τον τύπο συμπίεσης. |
| default_memory_allocation_limit | int | r/w | Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Λάβε ή ορίστε το δοχείο δεδομένων exif |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| horizontal_sampling | byte | r/w | Λαμβάνει ή ορίζει τις οριζόντιες υποδειγματοληψίες για κάθε στοιχείο. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Λαμβάνει ή ορίζει το jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Λαμβάνει ή ορίζει το όριο διαφοράς JPEG-LS για κωδικοποίηση σχεδόν χωρίς απώλειες (παράμετρος NEAR από την προδιαγραφή JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία διαπλέγματος JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Λαμβάνει ή ορίζει τις προκαθορισμένες παραμέτρους JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| preblend_alpha_if_present | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν τα κόκκινα, πράσινα και μπλε συστατικά πρέπει να αναμειχθούν με ένα χρώμα φόντου, εάν υπάρχει κανάλι άλφα. |
| quality | int | r/w | Λαμβάνει ή ορίζει την ποιότητα εικόνας. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις του βελτιστοποιητή RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Το προφίλ χρώματος RGB προορισμού για εικόνες jpeg CMYK. Χρησιμοποιείται για αποθήκευση εικόνων. Πρέπει να είναι σε ζεύγος με το CMYKColorProfile για σωστή μετατροπή χρώματος. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Λαμβάνει ή ορίζει τη λειτουργία στρογγυλοποίησης δείγματος για να ταιριάζει μια τιμή 8-bit σε τιμή n-bit. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | Η κλιμακωμένη ποιότητα. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| vertical_sampling | byte | r/w | Λαμβάνει ή ορίζει τις κάθετες υποδειγματοληψίες για κάθε στοιχείο. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτήν την παρουσία. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Οι επιλογές JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


