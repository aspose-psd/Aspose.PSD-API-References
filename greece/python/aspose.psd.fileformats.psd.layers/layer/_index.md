---
title: "Layer Κλάση"
type: docs
weight: 930
url: /el/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [Layer()](#Layer__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). Κατασκευαστής για αργή αρχικοποίηση. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) από πίνακες byte. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [Layer(stream)](#Layer_stream_4) | Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | Αναπαριστά την υπογραφή του τρόπου ανάμειξης. |
| LAYER_HEADER_SIZE [static] | int | r | Το μέγεθος της κεφαλίδας στρώματος. |
| auto_adjust_palette | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| bits_per_pixel | int | r | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| blend_clipped_elements | bool | r/w | Λαμβάνει ή ορίζει την ανάμειξη του αποκομμένου στοιχείου. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Λαμβάνει ή ορίζει το κλειδί λειτουργίας ανάμειξης. |
| blend_mode_signature | int | r | Λαμβάνει την υπογραφή της λειτουργίας ανάμειξης. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | Λαμβάνει τις επιλογές ανάμειξης. |
| bottom | int | r/w | Λαμβάνει ή ορίζει τη θέση του κάτω στρώματος. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Λαμβάνει τα όρια του αντικειμένου. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | Λαμβάνει ή ορίζει τις πληροφορίες του καναλιού. |
| channels_count | ushort | r | Λαμβάνει τον αριθμό καναλιών του στρώματος. |
| clipping | byte | r/w | Λαμβάνει ή ορίζει το κλιπ του στρώματος. 0 = βάση, 1 = μη βάση. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Λαμβάνει το δοχείο [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| display_name | string | r/w | Λαμβάνει ή ορίζει το εμφανιζόμενο όνομα του στρώματος. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| πρόσθετο_μήκος | int | r | Λαμβάνει το μήκος των πρόσθετων πληροφοριών του στρώματος σε byte. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει μια τιμή μορφής αρχείου |
| διαφάνεια_γέμισης | int | r/w | Λαμβάνει ή ορίζει τη διαφάνεια γεμίσματος. |
| γέμιση | byte | r/w | Λαμβάνει ή ορίζει το γέμισμα του στρώματος. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | Λαμβάνει ή ορίζει τις σημαίες του στρώματος.<br/>            bit 0 = προστασία διαφάνειας;<br/>            bit 1 = ορατό;<br/>            bit 2 = παρωχημένο;<br/>            bit 3 = 1 για Photoshop 5.0 και μεταγενέστερα, υποδεικνύει αν το bit 4 περιέχει χρήσιμες πληροφορίες;<br/>            bit 4 = τα δεδομένα pixel δεν επηρεάζουν την εμφάνιση του εγγράφου. |
| έχει_άλφα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει alpha. |
| έχει_χρώμα_υπόβαθρου | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| έχει_διαφανές_χρώμα | bool | r/w | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| height | int | r | Λαμβάνει το ύψος της εικόνας. |
| horizontal_resolution | double | r/w | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| διαφάνεια_εικόνας | float | r | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| είναι_στη_μνήμη | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της εικόνας είναι προσωρινά αποθηκευμένα αυτή τη στιγμή. |
| διατίθεται_ακατέργαστα_δεδομένα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν υποστηρίζεται η φόρτωση ακατέργαστων δεδομένων. |
| είναι_ορατό | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το στρώμα είναι ορατό |
| είναι_ορατό_στην_ομάδα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ορατή σε ομάδα(Εάν το στρώμα δεν βρίσκεται σε ομάδα σημαίνει ότι είναι η ριζική ομάδα). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | Λαμβάνει ή ορίζει τα δεδομένα περιοχών ανάμειξης του στρώματος. |
| ημερομηνία_και_ώρα_δημιουργίας_στρώσης | datetime | r/w | Λαμβάνει ή ορίζει την ημερομηνία και ώρα δημιουργίας του στρώματος. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | Λαμβάνει ή ορίζει τα δεδομένα μάσκας του στρώματος. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | Λαμβάνει τις επιλογές του στρώματος. |
| αριστερά | int | r/w | Λαμβάνει ή ορίζει τη θέση του αριστερού στρώματος. |
| μήκος | int | r | Λαμβάνει το συνολικό μήκος του στρώματος σε bytes. |
| name | string | r/w | Λαμβάνει ή ορίζει το όνομα του στρώματος. |
| opacity | byte | r/w | Λαμβάνει ή ορίζει τη διαφάνεια του στρώματος. 0 = διαφανές, 255 = αδιαφανές. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| προπολλαπλασιασμός_συστατικών | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά της εικόνας πρέπει να προπολλαπλασιαστούν. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| δείκτης_εφεδρικού_ακατέργαστου | int | r/w | Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Λαμβάνει ή ορίζει τον μετατροπέα χρωμάτων με ευρετήριο |
| μέγεθος_γραμμής_ακατέργαστου | int | r | Λαμβάνει το μέγεθος ακατέργαστης γραμμής σε bytes. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | Λαμβάνει ή ορίζει τους πόρους του στρώματος. |
| δεξιά | int | r/w | Λαμβάνει ή ορίζει τη θέση του δεξιού στρώματος. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | Λαμβάνει ή ορίζει την διακοσμητική επισήμανση χρώματος φύλλου στη λίστα των στρωμάτων |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Λαμβάνει το μέγεθος του αντικειμένου. |
| επάνω | int | r/w | Λαμβάνει ή ορίζει τη θέση του άνω στρώματος. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| update_xmp_data | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| use_palette | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα εικόνας χρησιμοποιείται. |
| use_raw_data | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| vertical_resolution | double | r/w | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Λαμβάνει το πλάτος της εικόνας. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | Προσθέτει τη μάσκα στο τρέχον στρώμα. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | Ρύθμιση της φωτεινότητας της εικόνας. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | Αντίθεση εικόνας |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | Διόρθωση γάμμα εικόνας. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | Διόρθωση γάμμα εικόνας. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι. |
| binarize_otsu() | Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu. |
| cache_data() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_9) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες επιλογές ανοίγματος. |
| [can_load(stream)](#can_load_stream_11) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα και προαιρετικά χρησιμοποιώντας το καθορισμένο <paramref name=\"loadOptions\" />. |
| [can_save(options)](#can_save_options_13) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο καθορισμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις δοθείσες επιλογές αποθήκευσης. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | Περικοπή της εικόνας. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [draw_image(location, image)](#draw_image_location_image_18) | Σχεδιάζει την εικόνα στο στρώμα. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| [get_default_options(args)](#get_default_options_args_21) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Λαμβάνει το μορφότυπο αρχείου. |
| [get_file_format(stream)](#get_file_format_stream_26) | Λαμβάνει το μορφότυπο αρχείου. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |
| [get_original_options()](#get_original_options__30) | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων αρχείου.<br/>            Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες.<br/>            Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) μέθοδο, θα παραχθεί η εξαγόμενη εικόνα PNG με 8-bit ανά pixel.<br/>            Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις<br/>            στη [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) μέθοδο ως δεύτερη παράμετρο. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | Λαμβάνει ένα pixel εικόνας.<br/>            Προειδοποίηση απόδοσης: Αποφύγετε τη χρήση αυτής της μεθόδου για επανάληψη σε όλα τα pixel της εικόνας, καθώς μπορεί να προκαλέσει σημαντικά προβλήματα απόδοσης.<br/>            Για πιο αποδοτικό χειρισμό pixel, χρησιμοποιήστε τη μέθοδο `LoadArgb32Pixels` για να ανακτήσετε ολόκληρο τον πίνακα pixel ταυτόχρονα. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Λαμβάνει ένα ανάλογο ύψος. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Λαμβάνει ένα ανάλογο πλάτος. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | Μετασχηματισμός μιας εικόνας στην αποχρώσεις του γκρι |
| [load(file_path)](#load_file_path_35) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| [load(stream)](#load_stream_37) | Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα. |
| [load(stream, load_options)](#load_stream_load_options_38) | Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | Φορτώνει pixel ARGB 32-bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | Φορτώνει pixel ARGB 64-bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | Φορτώνει pixel σε μορφή CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | Φορτώνει pixel σε μορφή CMYK.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | Φορτώνει μερικά pixel 32-bit ARGB (ανά μπλοκ). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | Φορτώνει pixel μερικώς ανά πακέτα. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | Φορτώνει pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | Φορτώνει ακατέργαστα δεδομένα. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | Φορτώνει ακατέργαστα δεδομένα. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | Συγχωνεύει το στρώμα με το καθορισμένο στρώμα |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με το καθορισμένο δείκτη γραμμής σάρωσης. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με το καθορισμένο δείκτη γραμμής σάρωσης. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | Αλλάζει το μέγεθος της εικόνας. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | Αλλάζει το ύψος αναλογικά. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | Αλλάζει το ύψος αναλογικά. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | Αλλάζει το ύψος αναλογικά. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | Αλλάζει το πλάτος αναλογικά. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | Αλλάζει το πλάτος αναλογικά. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| save() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| [save(file_path)](#save_file_path_62) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(file_path, options)](#save_file_path_options_63) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(stream)](#save_stream_66) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(stream, options_base)](#save_stream_options_base_67) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | Αποθηκεύει τα 32-bit ARGB pixel. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | Αποθηκεύει pixel (μέθοδος ειδική για μορφότυπο). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | Αποθηκεύει τα ακατέργαστα δεδομένα. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | Ορίζει ένα 32-bit ARGB pixel εικόνας για τη συγκεκριμένη θέση. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Ορίζει την παλέτα εικόνας. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | Ορίζει ένα pixel εικόνας για τη συγκεκριμένη θέση. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | Δημιουργεί ένα ρηχό αντίγραφο του τρέχοντος Layer.<br/>            Παρακαλώ <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> για εξήγηση. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). Κατασκευαστής για αργή αρχικοποίηση.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) από πίνακες byte.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Τα όρια του layer. |
| red_bytes | byte | Τα κόκκινα bytes. |
| green_bytes | byte | Τα πράσινα bytes. |
| blue_bytes | byte | Τα μπλε bytes. |
| name | string | Το όνομα του layer. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η εικόνα. |
| dispose_image | bool | αν οριστεί σε <c>true</c> [dispose image]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή εικόνας |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

Προσθέτει τη μάσκα στο τρέχον στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | Η μάσκα layer. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

Ρύθμιση της φωτεινότητας της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| φωτεινότητα | int | Τιμή φωτεινότητας. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

Αντίθεση εικόνας

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| αντίθεση | float | Τιμή αντίθεσης (σε εύρος [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

Διόρθωση γάμμα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γάμμα | float | Συντελεστής γάμμα για τα κανάλια κόκκινο, πράσινο και μπλε |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Διόρθωση γάμμα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| gamma_red | float | Συντελεστής γάμμα για το κόκκινο κανάλι |
| gamma_green | float | Συντελεστής γάμμα για το πράσινο κανάλι |
| gamma_blue | float | Συντελεστής γάμμα για το μπλε κανάλι |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brightness_difference | double | Η διαφορά φωτεινότητας μεταξύ του pixel και του μέσου όρου ενός παραθύρου s x s εικονοστοιχείων κεντραρισμένου γύρω από αυτό το pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brightness_difference | double | Η διαφορά φωτεινότητας μεταξύ του pixel και του μέσου όρου ενός παραθύρου s x s εικονοστοιχείων κεντραρισμένου γύρω από αυτό το pixel. |
| window_size | int | Το μέγεθος του παραθύρου s x s εικονοστοιχείων κεντραρισμένου γύρω από αυτό το pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| threshold | byte | Τιμή κατωφλίου. Εάν η αντίστοιχη γκρι τιμή ενός pixel είναι μεγαλύτερη από το κατώφλι, θα του ανατεθεί τιμή 255, διαφορετικά 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


```
 can_load(file_path) 
```

Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η εικόνα μπορεί να φορτωθεί από το συγκεκριμένο αρχείο; διαφορετικά, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


```
 can_load(file_path, load_options) 
```

Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες επιλογές ανοίγματος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η εικόνα μπορεί να φορτωθεί από το συγκεκριμένο αρχείο; διαφορετικά, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_11}


```
 can_load(stream) 
```

Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή από την οποία θα φορτωθεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή; διαφορετικά, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


```
 can_load(stream, load_options) 
```

Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα και προαιρετικά χρησιμοποιώντας το καθορισμένο <paramref name=\"loadOptions\" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή από την οποία θα φορτωθεί. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη ροή; διαφορετικά, <c>false</c>. |


### Method: can_save(options) {#can_save_options_13}


```
 can_save(options) 
```

Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο καθορισμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις δοθείσες επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν η εικόνα μπορεί να αποθηκευτεί στη συγκεκριμένη μορφή αρχείου που αντιπροσωπεύεται από τις παρεχόμενες επιλογές αποθήκευσης; διαφορετικά, <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


```
 create(image_options, width, height) 
```

Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές εικόνας. |
| width | int | Το πλάτος. |
| height | int | Το ύψος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Η νεοδημιουργημένη εικόνα. |


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

Περικοπή της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

Εκτελεί dithering στην τρέχουσα εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Η μέθοδος dithering. |
| bits_count | int | Ο τελικός αριθμός bits για dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Εκτελεί dithering στην τρέχουσα εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Η μέθοδος dithering. |
| bits_count | int | Ο τελικός αριθμός bits για dithering. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η προσαρμοσμένη παλέτα για dithering. |

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

Σχεδιάζει την εικόνα στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Η θέση. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η εικόνα. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


```
 get_argb_32_pixel(x, y) 
```

Λαμβάνει ένα pixel εικόνας 32-bit ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το 32-bit ARGB pixel για τη συγκεκριμένη θέση. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


```
 get_default_argb_32_pixels(rectangle) 
```

Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο προεπιλεγμένος πίνακας pixel. |


### Method: get_default_options(args) {#get_default_options_args_21}


```
 get_default_options(args) 
```

Λαμβάνει τις προεπιλεγμένες επιλογές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| args | object | Τα επιχειρήματα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Προεπιλεγμένες επιλογές |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Ο μερικός φορτωτής pixel. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Ο μερικός φορτωτής ακατέργαστων δεδομένων. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη ακατέργαστων δεδομένων. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Ο προεπιλεγμένος πίνακας ακατέργαστων δεδομένων. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


```
 get_file_format(file_path) 
```

Λαμβάνει το μορφότυπο αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Η καθορισμένη μορφή αρχείου. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


```
 get_file_format(stream) 
```

Λαμβάνει το μορφότυπο αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Η καθορισμένη μορφή αρχείου. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη κατάλληλου ορθογωνίου. |
| pixels | int | Τα 32-bit ARGB pixels. |
| width | int | Το πλάτος του αντικειμένου. |
| height | int | Το ύψος του αντικειμένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το κατάλληλο ορθογώνιο ή εξαίρεση εάν δεν βρεθεί κανένα κατάλληλο ορθογώνιο. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη κατάλληλου ορθογωνίου. |
| width | int | Το πλάτος του αντικειμένου. |
| height | int | Το ύψος του αντικειμένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το κατάλληλο ορθογώνιο ή εξαίρεση εάν δεν βρεθεί κανένα κατάλληλο ορθογώνιο. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


```
 get_modify_date(use_default) 
```

Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| use_default | bool | αν οριστεί σε <c>true</c> χρησιμοποιεί τις πληροφορίες από το FileInfo ως προεπιλεγμένη τιμή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| datetime | Η ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων αρχείου.<br/>            Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες.<br/>            Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) μέθοδο, θα παραχθεί η εξαγόμενη εικόνα PNG με 8-bit ανά pixel.<br/>            Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις<br/>            στη [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) μέθοδο ως δεύτερη παράμετρο.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές βασισμένες στις αρχικές ρυθμίσεις του αρχείου. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


```
 get_pixel(x, y) 
```

Λαμβάνει ένα pixel εικόνας.<br/>            Προειδοποίηση απόδοσης: Αποφύγετε τη χρήση αυτής της μεθόδου για επανάληψη σε όλα τα pixel της εικόνας, καθώς μπορεί να προκαλέσει σημαντικά προβλήματα απόδοσης.<br/>            Για πιο αποδοτικό χειρισμό pixel, χρησιμοποιήστε τη μέθοδο `LoadArgb32Pixels` για να ανακτήσετε ολόκληρο τον πίνακα pixel ταυτόχρονα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Το χρώμα pixel για την καθορισμένη θέση. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


```
 get_proportional_height(width, height, new_width) 
```

Λαμβάνει ένα ανάλογο ύψος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | int | Το πλάτος. |
| height | int | Το ύψος. |
| new_width | int | Το νέο πλάτος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το ανάλογο ύψος. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


```
 get_proportional_width(width, height, new_height) 
```

Λαμβάνει ένα ανάλογο πλάτος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | int | Το πλάτος. |
| height | int | Το ύψος. |
| new_height | int | Το νέο ύψος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Το ανάλογο πλάτος. |


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


```
 load(file_path) 
```

Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου από την οποία θα φορτωθεί η εικόνα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Η φορτωμένη εικόνα. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


```
 load(file_path, load_options) 
```

Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου από την οποία θα φορτωθεί η εικόνα. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Η φορτωμένη εικόνα. |


### Method: load(stream)  [static] {#load_stream_37}


```
 load(stream) 
```

Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή από την οποία θα φορτωθεί η εικόνα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Η φορτωμένη εικόνα. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


```
 load(stream, load_options) 
```

Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή από την οποία θα φορτωθεί η εικόνα. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Η φορτωμένη εικόνα. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


```
 load_argb_32_pixels(rectangle) 
```

Φορτώνει pixel ARGB 32-bit.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο φορτωμένος πίνακας 32-bit ARGB pixel. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


```
 load_argb_64_pixels(rectangle) 
```

Φορτώνει pixel ARGB 64-bit.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| long | Ο φορτωμένος πίνακας 64-bit ARGB pixel. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


```
 load_cmyk_32_pixels(rectangle) 
```

Φορτώνει pixel σε μορφή CMYK.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Τα φορτωμένα CMYK pixel παρουσιάζονται ως 32-bit ακέραιες τιμές. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


```
 load_cmyk_pixels(rectangle) 
```

Φορτώνει pixel σε μορφή CMYK.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Ο φορτωμένος πίνακας CMYK pixel. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Φορτώνει μερικά pixel 32-bit ARGB (ανά μπλοκ).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Ο μερικός φορτωτής pixel. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Φορτώνει pixel μερικώς ανά πακέτα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το επιθυμητό ορθογώνιο. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Ο φορτωτής pixel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


```
 load_pixels(rectangle) 
```

Φορτώνει pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Ο φορτωμένος πίνακας pixel. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Φορτώνει ακατέργαστα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα ακατέργαστα δεδομένα. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Τα όρια της εικόνας dest. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων για χρήση με τα φορτωμένα δεδομένα. Σημειώστε ότι εάν τα δεδομένα δεν είναι στη μορφή που έχει οριστεί, θα πραγματοποιηθεί μετατροπή δεδομένων. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Ο φορτωτής ακατέργαστων δεδομένων. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Φορτώνει ακατέργαστα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα ακατέργαστα δεδομένα. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων για χρήση με τα φορτωμένα δεδομένα. Σημειώστε ότι εάν τα δεδομένα δεν είναι στη μορφή που έχει οριστεί, θα πραγματοποιηθεί μετατροπή δεδομένων. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Ο φορτωτής ακατέργαστων δεδομένων. |

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

Συγχωνεύει το στρώμα με το καθορισμένο στρώμα

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Το επίπεδο στο οποίο θα συγχωνευτεί. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


```
 read_argb_32_scan_line(scan_line_index) 
```

Διαβάζει ολόκληρη τη γραμμή σάρωσης με το καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scan_line_index | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο πίνακας τιμών χρώματος 32-bit ARGB της γραμμής σάρωσης. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


```
 read_scan_line(scan_line_index) 
```

Διαβάζει ολόκληρη τη γραμμή σάρωσης με το καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scan_line_index | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Ο πίνακας τιμών χρώματος pixel της γραμμής σάρωσης. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| new_height | int | Το νέο ύψος. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


```
 resize(new_width, new_height, resize_type) 
```

Αλλάζει το μέγεθος της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| new_height | int | Το νέο ύψος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Ο τύπος αλλαγής μεγέθους. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


```
 resize(new_width, new_height, settings) 
```

Αλλάζει το μέγεθος της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| new_height | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Τύπος της αλλαγής μεγέθους. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους της εικόνας. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

Αλλάζει το πλάτος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Τύπος της αλλαγής μεγέθους. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

Αλλάζει το πλάτος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους της εικόνας. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

Περιστρέφει την εικόνα γύρω από το κέντρο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές θα περιστρέφουν δεξιόστροφα. |
| resize_proportionally | bool | εάν οριστεί σε <c>true</c> το μέγεθος της εικόνας σας θα αλλάξει σύμφωνα με τις προβολές του περιστραμμένου ορθογωνίου (σημεία γωνιών), σε άλλη περίπτωση οι διαστάσεις παραμένουν αμετάβλητες και μόνο τα εσωτερικά περιεχόμενα της εικόνας περιστρέφονται. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Χρώμα του φόντου. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Ο τύπος περιστροφής/αναστροφής. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |
| over_write | bool | εάν οριστεί σε <c>true</c> θα αντικαταστήσει τα περιεχόμενα του αρχείου, διαφορετικά θα γίνει προσθήκη. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


```
 save(stream, options_base, bounds_rectangle) 
```

Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Αποθηκεύει τα 32-bit ARGB pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | int | Ο πίνακας εικονοστοιχείων ARGB 32-bit. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

Αποθηκεύει pixel (μέθοδος ειδική για μορφότυπο).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Ο πίνακας εικονοστοιχείων ARGB 32-bit. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Αποθηκεύει τα ακατέργαστα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| δεδομένα | byte | Τα ακατέργαστα δεδομένα. |
| data_offset | int | Η αρχική μετατόπιση των ακατέργαστων δεδομένων. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο των ακατέργαστων δεδομένων. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Οι ρυθμίσεις των ακατέργαστων δεδομένων στα οποία βρίσκονται τα δεδομένα. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Ορίζει ένα 32-bit ARGB pixel εικόνας για τη συγκεκριμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |
| argb_32_color | int | Το εικονοστοιχείο ARGB 32-bit για τη συγκεκριμένη θέση. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Ορίζει την παλέτα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα για ορισμό. |
| update_colors | bool | εάν οριστεί σε <c>true</c> τα χρώματα θα ενημερωθούν σύμφωνα με τη νέα παλέτα· διαφορετικά οι δείκτες χρωμάτων παραμένουν αμετάβλητοι. Σημειώστε ότι οι αμετάβλητοι δείκτες μπορεί να προκαλέσουν σφάλμα στην εικόνα κατά τη φόρτωση εάν κάποιοι δείκτες δεν έχουν αντίστοιχες καταχωρίσεις στην παλέτα. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


```
 set_pixel(x, y, color) 
```

Ορίζει ένα pixel εικόνας για τη συγκεκριμένη θέση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | int | Η θέση x του pixel. |
| y | int | Η θέση y του pixel. |
| color | [Color](/psd/python-net/aspose.psd/color) | Το χρώμα pixel για τη συγκεκριμένη θέση. |

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

Δημιουργεί ένα ρηχό αντίγραφο του τρέχοντος Layer.<br/>            Παρακαλώ <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> για εξήγηση.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Ένα ρηχό αντίγραφο του τρέχοντος Layer. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scan_line_index | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |
| argb_32_pixels | int | Ο 32-bit ARGB πίνακας χρωμάτων για εγγραφή. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scan_line_index | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Ο πίνακας χρωμάτων pixel για εγγραφή. |

