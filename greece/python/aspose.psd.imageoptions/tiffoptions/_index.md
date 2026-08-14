---
title: "TiffOptions Κλάση"
type: docs
weight: 130
url: /el/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) . Από προεπιλογή χρησιμοποιείται η σύμβαση little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Λαμβάνει ή ορίζει την επιλογή αποθήκευσης άλφα. Επιλογές εκτός του [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            χρησιμοποιούνται όταν ορίζονται περισσότερα από 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| καλλιτέχνης | string | r/w | Λαμβάνει ή ορίζει τον καλλιτέχνη. |
| bits_per_pixel | int | r | Λαμβάνει τα bits ανά pixel. |
| bits_per_sample | ushort | r/w | Λαμβάνει ή ορίζει τα bits ανά δείγμα. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει τη σειρά byte του tiff. |
| color_map | ushort | r/w | Λαμβάνει ή ορίζει το χάρτη χρωμάτων. |
| compressed_quality | int | r/w | Λαμβάνει ή ορίζει την ποιότητα συμπιεσμένης εικόνας.<br/>            Χρησιμοποιείται με τη συμπίεση Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Λαμβάνει ή ορίζει τη συμπίεση. |
| copyright | string | r/w | Λαμβάνει ή ορίζει τα πνευματικά δικαιώματα. |
| date_time | string | r/w | Λαμβάνει ή ορίζει την ημερομηνία και την ώρα. |
| default_memory_allocation_limit | int | r/w | Λαμβάνει ή ορίζει το προεπιλεγμένο όριο κατανομής μνήμης. |
| default_replacement_font | string | r/w | Λαμβάνει ή ορίζει τη προεπιλεγμένη εναλλακτική γραμματοσειρά (η γραμματοσειρά που θα χρησιμοποιηθεί για τη σχεδίαση κειμένου κατά την εξαγωγή σε raster, εάν η υπάρχουσα γραμματοσειρά στρώματος στο αρχείο PSD δεν είναι διαθέσιμη στο σύστημα).<br/>            Για να ληφθεί το σωστό όνομα της προεπιλεγμένης γραμματοσειράς, μπορεί να χρησιμοποιηθεί το παρακάτω απόσπασμα κώδικα:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| document_name | string | r/w | Λαμβάνει ή ορίζει το όνομα του εγγράφου. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Λαμβάνει ή ορίζει τον δείκτη προς το EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Λαμβάνει ή ορίζει τις επιλογές fax t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Λαμβάνει ή ορίζει το πρότυπο αρχείου TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Λαμβάνει ή ορίζει τη σειρά γεμίσματος των bits του byte. |
| full_frame | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [full frame]. |
| half_tone_hints | ushort | r/w | Λαμβάνει ή ορίζει τις υποδείξεις ημιτόνου. |
| image_description | string | r/w | Λαμβάνει ή ορίζει την περιγραφή της εικόνας. |
| image_length | uint | r/w | Λαμβάνει ή ορίζει το μήκος της εικόνας. |
| image_width | uint | r/w | Λαμβάνει ή ορίζει το πλάτος της εικόνας. |
| ink_names | string | r/w | Λαμβάνει ή ορίζει τα ονόματα μελανιού. |
| is_extra_samples_present | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν υπάρχουν επιπλέον δείγματα. |
| is_tiled | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα είναι σε πλακίδια. |
| is_valid | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν οι [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) έχουν ρυθμιστεί σωστά. Χρησιμοποιήστε τη μέθοδο Validate για να βρείτε τον λόγο αποτυχίας. |
| max_sample_value | ushort | r/w | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. |
| min_sample_value | ushort | r/w | Λαμβάνει ή ορίζει τη ελάχιστη τιμή δείγματος. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Οι επιλογές πολλαπλών σελίδων |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Λαμβάνει ή ορίζει τον προσανατολισμό. |
| page_name | string | r/w | Λαμβάνει ή ορίζει το όνομα της σελίδας. |
| page_number | ushort | r/w | Λαμβάνει ή ορίζει την ετικέτα αριθμού σελίδας. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Λαμβάνει ή ορίζει το φωτομετρικό. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Λαμβάνει ή ορίζει τη διαμόρφωση επιπέδου. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Λαμβάνει ή ορίζει τον προβλέπτη για τη συμπίεση LZW. |
| προπολλαπλασιασμός_συστατικών | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά πρέπει να προπολλαπλασιαστούν. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Λαμβάνει ή ορίζει τις ρυθμίσεις ανάλυσης. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Λαμβάνει ή ορίζει τη μονάδα ανάλυσης. |
| rows_per_strip | uint | r/w | Λαμβάνει ή ορίζει τις γραμμές ανά λωρίδα. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Λαμβάνει ή ορίζει τη μορφή δείγματος. |
| samples_per_pixel | ushort | r | Λαμβάνει τα δείγματα ανά pixel. Για να αλλάξετε αυτήν την τιμή ιδιότητας, χρησιμοποιήστε τον setter της ιδιότητας [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Λαμβάνει ή ορίζει τον κατασκευαστή του σαρωτή. |
| scanner_model | string | r/w | Λαμβάνει ή ορίζει το μοντέλο του σαρωτή. |
| smax_sample_value | uint | r/w | Λαμβάνει ή ορίζει τη μέγιστη τιμή δείγματος. Η τιμή έχει τύπο πεδίου που ταιριάζει καλύτερα στα δεδομένα δείγματος (τύπος Byte, Short ή Long). |
| smin_sample_value | uint | r/w | Λαμβάνει ή ορίζει την τιμή ελάχιστου δείγματος. Η τιμή έχει έναν τύπο πεδίου που ταιριάζει καλύτερα στα δεδομένα του δείγματος (Byte, Short ή Long type). |
| software_type | string | r/w | Λαμβάνει ή ορίζει τον τύπο λογισμικού. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Λαμβάνει ή ορίζει την πηγή για τη δημιουργία της εικόνας. |
| strip_byte_counts | uint | r/w | Λαμβάνει ή ορίζει τις μετρήσεις byte της λωρίδας. |
| strip_offsets | uint | r/w | Λαμβάνει ή ορίζει τις μετατοπίσεις της λωρίδας. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Λαμβάνει ή ορίζει μια γενική ένδειξη του τύπου των δεδομένων που περιέχονται σε αυτό το υποαρχείο. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Λαμβάνει ή ορίζει τις ετικέτες. |
| target_printer | string | r/w | Λαμβάνει ή ορίζει τον εκτυπωτή-στόχο. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Λαμβάνει ή ορίζει το κατώφλι. |
| tile_byte_counts | uint | r/w | Λαμβάνει ή ορίζει τις μετρήσεις byte του πλακιδίου. |
| tile_length | uint | r/w | Λαμβάνει ή ορίζει το μήκος του πλακιδίου. |
| tile_offsets | uint | r/w | Λαμβάνει ή ορίζει τις μετατοπίσεις του πλακιδίου. |
| tile_width | uint | r/w | Λαμβάνει ή ορίζει το πλάτος του πλακιδίου. |
| total_pages | ushort | r | Λαμβάνει τις συνολικές σελίδες. |
| valid_tag_count | int | r | Λαμβάνει τον έγκυρο αριθμό ετικετών. Αυτό δεν είναι ο συνολικός αριθμός ετικετών αλλά ο αριθμός των ετικετών που μπορούν να διατηρηθούν. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Λαμβάνει ή ορίζει τις επιλογές rasterization διανύσματος. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει το δοχείο μεταδεδομένων XMP. |
| xp_author | string | r/w | Λαμβάνει ή ορίζει τον συγγραφέα της εικόνας, που χρησιμοποιείται από τον Windows Explorer. |
| xp_comment | string | r/w | Λαμβάνει ή ορίζει το σχόλιο στην εικόνα, που χρησιμοποιείται από τον Windows Explorer. |
| xp_keywords | string | r/w | Λαμβάνει ή ορίζει το θέμα της εικόνας, που χρησιμοποιείται από τον Windows Explorer. |
| xp_subject | string | r/w | Λαμβάνει ή ορίζει πληροφορίες σχετικά με την εικόνα, που χρησιμοποιείται από τον Windows Explorer. |
| xp_title | string | r/w | Λαμβάνει ή ορίζει πληροφορίες σχετικά με την εικόνα, που χρησιμοποιείται από τον Windows Explorer. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τη θέση x. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την ανάλυση x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τους συντελεστές YCbCr. |
| y_cb_cr_subsampling | ushort | r/w | Λαμβάνει ή ορίζει τους παράγοντες υποδειγματοληψίας για το φωτομετρικό YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει τη θέση y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Λαμβάνει ή ορίζει την ανάλυση y. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Προσθέτει μια νέα ετικέτα. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Προσθέτει τις ετικέτες. |
| [clone()](#clone__3) | Κλωνοποιεί αυτήν την παρουσία. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Λαμβάνει το αντίτυπο της ετικέτας κατά τύπο. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Λαμβάνει τον αριθμό των έγκυρων ετικετών. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Καθορίζει αν η ετικέτα υπάρχει στις επιλογές ή όχι. |
| [remove_tag(tag)](#remove_tag_tag_7) | Αφαιρεί την ετικέτα. |
| validate() | Επικυρώνει εάν οι επιλογές έχουν έγκυρο συνδυασμό ετικετών. |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) . Από προεπιλογή χρησιμοποιείται η σύμβαση little endian.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Η αναμενόμενη μορφή αρχείου tiff. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Η αναμενόμενη μορφή αρχείου tiff. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | Η σειρά byte του μορφότυπου αρχείου TIFF που θα χρησιμοποιηθεί. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Οι επιλογές από τις οποίες θα γίνει αντιγραφή. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Οι ετικέτες για την αρχικοποίηση των επιλογών. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Προσθέτει μια νέα ετικέτα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Η ετικέτα για προσθήκη. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Προσθέτει τις ετικέτες.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Οι ετικέτες για προσθήκη. |

### Method: clone() {#clone__3}


```
 clone() 
```

Κλωνοποιεί αυτήν την παρουσία.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Επιστρέφει ρηχή αντιγραφή αυτού του αντικειμένου |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Λαμβάνει το αντίτυπο της ετικέτας κατά τύπο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Το κλειδί της ετικέτας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Παράδειγμα της ετικέτας εάν υπάρχει ή null διαφορετικά. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Λαμβάνει τον αριθμό των έγκυρων ετικετών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Οι ετικέτες προς επικύρωση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο αριθμός των έγκυρων ετικετών. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Καθορίζει αν η ετικέτα υπάρχει στις επιλογές ή όχι.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Το αναγνωριστικό (id) της ετικέτας για έλεγχο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η ετικέτα υπάρχει· διαφορετικά, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Αφαιρεί την ετικέτα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Η ετικέτα για αφαίρεση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | true εάν αφαιρεθεί επιτυχώς |


