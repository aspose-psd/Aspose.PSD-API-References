---
title: "PsdImage Κλάση"
type: docs
weight: 1760
url: /el/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα στη διαδρομή). Χρησιμοποιείται για την αρχικοποίηση psd εικόνας με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα στη διαδρομή) με παραμέτρους κατασκευής. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από υπάρχουσα raster εικόνα (όχι psd εικόνα) με λειτουργία χρώματος RGB, 4 κανάλια, 8 bit/κανάλι και χωρίς συμπίεση. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από υπάρχουσα raster εικόνα (όχι psd εικόνα) με παραμέτρους κατασκευής. |
| [PsdImage(stream)](#PsdImage_stream_5) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα σε ροή). Χρησιμοποιείται για την αρχικοποίηση psd εικόνας με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα σε ροή) με παραμέτρους κατασκευής. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την αρχικοποίηση κενής psd εικόνας. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, αριθμό καναλιών και μήκος bit καναλιών, καθώς και παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την αρχικοποίηση κενής psd εικόνας. |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | Η προεπιλεγμένη έκδοση PSD. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Λαμβάνει ή ορίζει το ενεργό επίπεδο. |
| auto_adjust_palette | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| bits_per_channel | int | r | Λαμβάνει τα bits ανά κανάλι. |
| bits_per_pixel | int | r | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Λαμβάνει τα όρια του αντικειμένου. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| channels_count | int | r | Λαμβάνει τον αριθμό καναλιών PSD. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Λαμβάνει ή ορίζει το προφίλ χρώματος CMYK για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με RgbColorProfile για σωστή μετατροπή χρώματος. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Λαμβάνει ή ορίζει τη λειτουργία χρώματος. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Λαμβάνει τη μέθοδο συμπίεσης. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Λαμβάνει το δοχείο [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει μια τιμή μορφής αρχείου |
| global_angle | int | r/w | Λαμβάνει ή ορίζει τη γενική γωνία. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Λαμβάνει τις πληροφορίες μάσκας παγκόσμιου επιπέδου. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Λαμβάνει ή ορίζει τους παγκόσμιους πόρους επιπέδου. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Λαμβάνει ή ορίζει το προφίλ χρώματος GRAY (μονόχρωμο) για εικόνες Grayscale PSD. |
| has_alpha | bool | r | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| έχει_χρώμα_υπόβαθρου | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| has_transparency_data | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν το πρώτο κανάλι άλφα περιέχει τα δεδομένα διαφάνειας για το συγχωνευμένο αποτέλεσμα όταν καθορίζονται τα δεδομένα επιπέδων. |
| έχει_διαφανές_χρώμα | bool | r/w | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα έχει διαφανές χρώμα. |
| height | int | r | Λαμβάνει το ύψος της εικόνας. |
| horizontal_resolution | double | r/w | Λαμβάνει ή ορίζει την οριζόντια ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| διαφάνεια_εικόνας | float | r | Λαμβάνει τη διαφάνεια αυτής της εικόνας. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | Λαμβάνει ή ορίζει τους πόρους εικόνας PSD. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| είναι_στη_μνήμη | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα της εικόνας είναι προσωρινά αποθηκευμένα αυτή τη στιγμή. |
| is_flatten | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η εικόνα psd είναι επίπεδη. |
| διατίθεται_ακατέργαστα_δεδομένα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν υποστηρίζεται η φόρτωση ακατέργαστων δεδομένων. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Λαμβάνει ή ορίζει τα επίπεδα PSD. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Λαμβάνει τον διαχειριστή συνδεδεμένων επιπέδων. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| προπολλαπλασιασμός_συστατικών | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν τα συστατικά της εικόνας πρέπει να προπολλαπλασιαστούν. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Λαμβάνει ή ορίζει τον προσαρμοσμένο μετατροπέα χρωμάτων |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Λαμβάνει τη μορφή ακατέργαστων δεδομένων. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
| δείκτης_εφεδρικού_ακατέργαστου | int | r/w | Λαμβάνει ή ορίζει το εφεδρικό δείκτη που θα χρησιμοποιηθεί όταν ο δείκτης παλέτας είναι εκτός ορίων |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Λαμβάνει ή ορίζει τον μετατροπέα χρωμάτων με ευρετήριο |
| μέγεθος_γραμμής_ακατέργαστου | int | r | Λαμβάνει το μέγεθος ακατέργαστης γραμμής σε bytes. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Λαμβάνει ή ορίζει το προφίλ χρώματος RGB για εικόνες CMYK PSD. Πρέπει να είναι σε ζεύγος με CmykColorProfile για σωστή μετατροπή χρώματος. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Λαμβάνει το μέγεθος του αντικειμένου. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Λαμβάνει τον πάροχο έξυπνου αντικειμένου. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Λαμβάνει το [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) αυτού του [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει το διαφανές χρώμα της εικόνας. |
| update_xmp_data | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα ενημερωθούν τα μεταδεδομένα XMP. |
| use_palette | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα εικόνας χρησιμοποιείται. |
| use_raw_data | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν θα χρησιμοποιηθεί η φόρτωση ακατέργαστων δεδομένων όταν η φόρτωση ακατέργαστων δεδομένων είναι διαθέσιμη. |
| version | int | r/w | Λαμβάνει ή ορίζει την έκδοση. |
| vertical_resolution | double | r/w | Λαμβάνει ή ορίζει την κάθετη ανάλυση, σε pixel ανά ίντσα, αυτού του [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| width | int | r | Λαμβάνει το πλάτος της εικόνας. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Λαμβάνει ή ορίζει τα μεταδεδομένα XMP. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Προσθέτει το επίπεδο προσαρμογής ασπρόμαυρο. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Προσθέτει το επίπεδο προσαρμογής φωτεινότητας/αντίθεσης. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Προσθέτει το επίπεδο προσαρμογής μίκτη καναλιών με προεπιλεγμένες παραμέτρους |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Προσθέτει τη στρώση προσαρμογής ισορροπίας χρώματος. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Προσθέτει τη στρώση Curves Adjustment. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Προσθέτει τη στρώση προσαρμογής exposure. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | Προσθέτει τη στρώση GradientMap Adjustment. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Προσθέτει τη στρώση hue/saturation adjustment. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Προσθέτει μια στρώση προσαρμογής invert. |
| [add_layer(layer)](#add_layer_layer_10) | Προσθέτει τη στρώση. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Προσθέτει την ομάδα στρωμάτων. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Προσθέτει τη στρώση Levels adjustment. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | Προσθέτει τη στρώση PhotoFilter. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Προσθέτει τη στρώση Posterize Adjustment. |
| [add_regular_layer()](#add_regular_layer__15) | Προσθέτει μια νέα κανονική στρώση. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Προσθέτει τη στρώση selective color adjustment. |
| [add_shape_layer()](#add_shape_layer__17) | Προσθέτει κενή στρώση Shape.<br/>            Χωρίς διαδρομές. Πρέπει να προστεθούν στη στρώση shape πριν από την αποθήκευση. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Προσθέτει μια νέα στρώση Text. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Προσθέτει τη στρώση Threshold adjustment. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Προσθέτει τη στρώση Vibrance adjustment. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Ρύθμιση της φωτεινότητας της εικόνας. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Αντίθεση εικόνας |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Διόρθωση γάμμα εικόνας. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Διόρθωση γάμμα εικόνας. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι. |
| binarize_otsu() | Δυαδικοποίηση μιας εικόνας με κατώφλι Otsu. |
| cache_data() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_28) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες επιλογές ανοίγματος. |
| [can_load(stream)](#can_load_stream_30) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα και προαιρετικά χρησιμοποιώντας το καθορισμένο <paramref name=\"loadOptions\" />. |
| [can_save(options)](#can_save_options_32) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο καθορισμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις δοθείσες επιλογές αποθήκευσης. |
| [convert(new_options)](#convert_new_options_33) | Μετατρέπει αυτή τη μορφή εικόνας στην καθορισμένη στις επιλογές. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Περικοπή της εικόνας. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Εκτελεί dithering στην τρέχουσα εικόνα. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Φιλτράρει το καθορισμένο ορθογώνιο. |
| flatten_image() | Ισοπεδώνει όλες τις στρώσεις. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | Λαμβάνει ένα pixel εικόνας 32-bit ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel 32-bit ARGB. |
| [get_default_options(args)](#get_default_options_args_41) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων χρησιμοποιώντας μερικό φορτωτή pixel. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Λαμβάνει τον προεπιλεγμένο ακατέργαστο πίνακα δεδομένων. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Λαμβάνει το μορφότυπο αρχείου. |
| [get_file_format(stream)](#get_file_format_stream_46) | Λαμβάνει το μορφότυπο αρχείου. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Λαμβάνει την ημερομηνία και ώρα που η εικόνα πόρου τροποποιήθηκε τελευταία. |
| [get_original_options()](#get_original_options__50) | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων αρχείου.<br/>            Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες.<br/>            Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) μέθοδο, θα παραχθεί η εξαγόμενη εικόνα PNG με 8-bit ανά pixel.<br/>            Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις<br/>            στη [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) μέθοδο ως δεύτερη παράμετρο. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Λαμβάνει ένα pixel εικόνας.<br/>            Προειδοποίηση απόδοσης: Αποφύγετε τη χρήση αυτής της μεθόδου για επανάληψη σε όλα τα pixel της εικόνας, καθώς μπορεί να προκαλέσει σημαντικά προβλήματα απόδοσης.<br/>            Για πιο αποδοτικό χειρισμό pixel, χρησιμοποιήστε τη μέθοδο `LoadArgb32Pixels` για να ανακτήσετε ολόκληρο τον πίνακα pixel ταυτόχρονα. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Λαμβάνει ένα ανάλογο ύψος. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Λαμβάνει ένα ανάλογο πλάτος. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Μετασχηματισμός μιας εικόνας στην αποχρώσεις του γκρι |
| [load(file_path)](#load_file_path_55) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| [load(stream)](#load_stream_57) | Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα. |
| [load(stream, load_options)](#load_stream_load_options_58) | Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Φορτώνει pixel ARGB 32-bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Φορτώνει pixel ARGB 64-bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Φορτώνει pixel σε μορφή CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Φορτώνει pixel σε μορφή CMYK.<br/>            Αυτή η μέθοδος είναι παρωχημένη. Παρακαλώ χρησιμοποιήστε πιο αποτελεσματική τη μέθοδο [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Φορτώνει μερικά pixel 32-bit ARGB (ανά μπλοκ). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Φορτώνει pixel μερικώς ανά πακέτα. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Φορτώνει pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Φορτώνει ακατέργαστα δεδομένα. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Φορτώνει ακατέργαστα δεδομένα. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Συγχωνεύει τις στρώσεις. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με το καθορισμένο δείκτη γραμμής σάρωσης. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Διαβάζει ολόκληρη τη γραμμή σάρωσης με το καθορισμένο δείκτη γραμμής σάρωσης. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρηθούν οι ομαλές άκρες. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρηθούν οι ομαλές άκρες. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες.<br/>            Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες.<br/>            Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Αλλάζει το μέγεθος της εικόνας. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Αλλάζει το ύψος αναλογικά. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Αλλάζει το ύψος αναλογικά. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Αλλάζει το ύψος αναλογικά. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Αλλάζει το πλάτος αναλογικά. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Αλλάζει το πλάτος αναλογικά. |
| [rotate(angle)](#rotate_angle_84) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Περιστρέφει την εικόνα γύρω από το κέντρο. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| save() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| [save(file_path)](#save_file_path_87) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(file_path, options)](#save_file_path_options_88) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(stream)](#save_stream_91) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(stream, options_base)](#save_stream_options_base_92) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | Αποθηκεύει τα 32-bit ARGB pixel. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Αποθηκεύει pixel (μέθοδος ειδική για μορφότυπο). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Αποθηκεύει τα ακατέργαστα δεδομένα. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Ορίζει ένα 32-bit ARGB pixel εικόνας για τη συγκεκριμένη θέση. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Ορίζει την παλέτα εικόνας. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Ορίζει ένα pixel εικόνας για τη συγκεκριμένη θέση. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Ορίζει την ανάλυση για αυτό το [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα στη διαδρομή). Χρησιμοποιείται για την αρχικοποίηση psd εικόνας με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| διαδρομή | string | Η διαδρομή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα στη διαδρομή) με παραμέτρους κατασκευής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| διαδρομή | string | Η διαδρομή για τη φόρτωση δεδομένων pixel και παλέτας και την αρχικοποίηση. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Η λειτουργία χρώματος. |
| channel_bit_depth | short | Το βάθος bit του PSD ανά κανάλι. |
| κανάλια | short | Ο αριθμός καναλιών του PSD. |
| psd_version | int | Η έκδοση PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Η συμπίεση που θα χρησιμοποιηθεί. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από υπάρχουσα raster εικόνα (όχι psd εικόνα) με λειτουργία χρώματος RGB, 4 κανάλια, 8 bit/κανάλι και χωρίς συμπίεση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η εικόνα από την οποία θα φορτωθούν τα δεδομένα εικονοστοιχείων και παλέτας και με την οποία θα αρχικοποιηθεί. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από υπάρχουσα raster εικόνα (όχι psd εικόνα) με παραμέτρους κατασκευής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Η εικόνα από την οποία θα φορτωθούν τα δεδομένα εικονοστοιχείων και παλέτας και με την οποία θα αρχικοποιηθεί. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Η λειτουργία χρώματος. |
| channel_bit_depth | short | Το βάθος bit του PSD ανά κανάλι. |
| κανάλια | short | Ο αριθμός καναλιών του PSD. |
| psd_version | int | Η έκδοση PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Η συμπίεση που θα χρησιμοποιηθεί. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα σε ροή). Χρησιμοποιείται για την αρχικοποίηση psd εικόνας με προεπιλεγμένες παραμέτρους - Λειτουργία χρώματος - rgb, 4 κανάλια, 8 bit ανά κανάλι, Συμπίεση - Raw.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή από την οποία θα φορτωθούν τα δεδομένα εικονοστοιχείων και παλέτας και με την οποία θα αρχικοποιηθεί. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) από καθορισμένη διαδρομή raster εικόνας (όχι psd εικόνα σε ροή) με παραμέτρους κατασκευής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή από την οποία θα φορτωθούν τα δεδομένα εικονοστοιχείων και παλέτας και με την οποία θα αρχικοποιηθεί. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Η λειτουργία χρώματος. |
| channel_bit_depth | short | Το βάθος bit του PSD ανά κανάλι. |
| κανάλια | short | Ο αριθμός καναλιών του PSD. |
| psd_version | int | Η έκδοση PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Η συμπίεση που θα χρησιμοποιηθεί. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) με καθορισμένο πλάτος και ύψος. Χρησιμοποιείται για την αρχικοποίηση κενής psd εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | int | Το πλάτος της εικόνας. |
| height | int | Το ύψος της εικόνας. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) με καθορισμένο πλάτος, ύψος, παλέτα, λειτουργία χρώματος, αριθμό καναλιών και μήκος bit καναλιών, καθώς και παραμέτρους λειτουργίας συμπίεσης. Χρησιμοποιείται για την αρχικοποίηση κενής psd εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | int | Το πλάτος της εικόνας. |
| height | int | Το ύψος της εικόνας. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα χρωμάτων. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Η λειτουργία χρώματος. |
| channel_bit_depth | short | Το βάθος bit του PSD ανά κανάλι. |
| κανάλια | short | Ο αριθμός καναλιών του PSD. |
| psd_version | int | Η έκδοση PSD. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Η συμπίεση που θα χρησιμοποιηθεί. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Προσθέτει το επίπεδο προσαρμογής ασπρόμαυρο.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | Το δημιουργημένο στρώμα προσαρμογής μαύρο-άσπρο. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Προσθέτει το επίπεδο προσαρμογής φωτεινότητας/αντίθεσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| φωτεινότητα | int | Η φωτεινότητα. |
| αντίθεση | int | Η αντίθεση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Δημιουργήθηκε στρώμα φωτεινότητας/αντίθεσης |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Προσθέτει το επίπεδο προσαρμογής μίκτη καναλιών με προεπιλεγμένες παραμέτρους

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Προστέθηκε στρώμα μίξης καναλιών |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Προσθέτει τη στρώση προσαρμογής ισορροπίας χρώματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Ένα νέο δημιουργημένο στρώμα ισορροπίας χρωμάτων. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Προσθέτει τη στρώση Curves Adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Δημιουργήθηκε στρώμα [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/)  |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Προσθέτει τη στρώση προσαρμογής exposure.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| έκθεση | float | Η έκθεση. |
| offset | float | Η μετατόπιση. |
| gamma_correction | float | Η διόρθωση γάμμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Δημιουργήθηκε στρώμα προσαρμογής έκθεσης |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

Προσθέτει τη στρώση GradientMap Adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | Παράδειγμα GradientMap. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Προσθέτει τη στρώση hue/saturation adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Ένα νέο δημιουργημένο στρώμα απόχρωσης/κορεσμού. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Προσθέτει μια στρώση προσαρμογής invert.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | Το δημιουργημένο στρώμα αντιστροφής |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Προσθέτει τη στρώση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Το στρώμα. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Προσθέτει την ομάδα στρωμάτων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| group_name | string | Όνομα της ομάδας. |
| index | int | Το ευρετήριο του στρώματος μετά το οποίο θα εισαχθεί. |
| start_behaviour | bool | αν οριστεί σε <c>true</c> [start behaviour] τότε η ομάδα θα είναι σε ανοιχτή κατάσταση κατά την εκκίνηση, διαφορετικά σε ελαχιστοποιημένη κατάσταση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Άνοιγμα στρώματος ομάδας |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Προσθέτει τη στρώση Levels adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Ένα νέο δημιουργημένο στρώμα επιπέδων |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

Προσθέτει τη στρώση PhotoFilter.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Το χρώμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Δημιουργήθηκε στρώμα φίλτρου φωτογραφίας |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Προσθέτει τη στρώση Posterize Adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | Παράδειγμα PosterizeLayer. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Προσθέτει μια νέα κανονική στρώση.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Δημιουργήθηκε κανονικό στρώμα. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Προσθέτει τη στρώση selective color adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | Το δημιουργημένο στρώμα προσαρμογής επιλεκτικού χρώματος. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Προσθέτει κενή στρώση Shape.<br/>            Χωρίς διαδρομές. Πρέπει να προστεθούν στη στρώση shape πριν από την αποθήκευση.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Παράδειγμα ShapeLayer. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Προσθέτει μια νέα στρώση Text.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | string | Το κείμενο του στρώματος. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο του στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Δημιουργήθηκε στρώμα κειμένου. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Προσθέτει τη στρώση Threshold adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | Το δημιουργημένο στρώμα ρύθμισης Threshold. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Προσθέτει τη στρώση Vibrance adjustment.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Ένα νεοδημιουργημένο στρώμα Vibrance. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Ρύθμιση της φωτεινότητας της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| φωτεινότητα | int | Τιμή φωτεινότητας. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Αντίθεση εικόνας

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| αντίθεση | float | Τιμή αντίθεσης (σε εύρος [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Διόρθωση γάμμα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γάμμα | float | Συντελεστής γάμμα για τα κανάλια κόκκινο, πράσινο και μπλε |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brightness_difference | double | Η διαφορά φωτεινότητας μεταξύ του pixel και του μέσου όρου ενός παραθύρου s x s εικονοστοιχείων κεντραρισμένου γύρω από αυτό το pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Δυαδικοποίηση μιας εικόνας χρησιμοποιώντας τον αλγόριθμο προσαρμοστικού κατωφλίου του Bradley με χρήση του ολοκληρωτικού κατωφλίου εικόνας

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| brightness_difference | double | Η διαφορά φωτεινότητας μεταξύ του pixel και του μέσου όρου ενός παραθύρου s x s εικονοστοιχείων κεντραρισμένου γύρω από αυτό το pixel. |
| window_size | int | Το μέγεθος του παραθύρου s x s εικονοστοιχείων κεντραρισμένου γύρω από αυτό το pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Δυαδικοποίηση μιας εικόνας με προκαθορισμένο κατώφλι.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| threshold | byte | Τιμή κατωφλίου. Εάν η αντίστοιχη γκρι τιμή ενός pixel είναι μεγαλύτερη από το κατώφλι, θα του ανατεθεί τιμή 255, διαφορετικά 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Μετατρέπει αυτή τη μορφή εικόνας στην καθορισμένη στις επιλογές.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | Οι νέες επιλογές. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Περικοπή της εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Εκτελεί dithering στην τρέχουσα εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Η μέθοδος dithering. |
| bits_count | int | Ο τελικός αριθμός bits για dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Φιλτράρει το καθορισμένο ορθογώνιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | Οι επιλογές. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Λαμβάνει τον προεπιλεγμένο πίνακα pixel χρησιμοποιώντας μερικό φορτωτή pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για λήψη pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Ο μερικός φορτωτής pixel. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων αρχείου.<br/>            Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες.<br/>            Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) μέθοδο, θα παραχθεί η εξαγόμενη εικόνα PNG με 8-bit ανά pixel.<br/>            Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις<br/>            στη [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) μέθοδο ως δεύτερη παράμετρο.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές βασισμένες στις αρχικές ρυθμίσεις του αρχείου. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Φορτώνει μερικά pixel 32-bit ARGB (ανά μπλοκ).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Ο μερικός φορτωτής pixel. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Φορτώνει pixel μερικώς ανά πακέτα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το επιθυμητό ορθογώνιο. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Ο φορτωτής pixel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Συγχωνεύει τις στρώσεις.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Το κάτω στρώμα. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Το άνω στρώμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Κάτω στρώμα μετά τη συγχώνευση |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρηθούν οι ομαλές άκρες.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | Επιτρεπόμενη διαφορά στο παλιό χρώμα για να είναι δυνατή η διεύρυνση του τόνου του αντικατεστημένου χρώματος. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Αντικαθιστά ένα χρώμα με άλλο με επιτρεπόμενη διαφορά και διατηρεί την αρχική τιμή άλφα για να διατηρηθούν οι ομαλές άκρες.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| old_color_argb | int | Τιμή ARGB παλιού χρώματος προς αντικατάσταση. |
| old_color_diff | byte | Επιτρεπόμενη διαφορά στο παλιό χρώμα για να είναι δυνατή η διεύρυνση του τόνου του αντικατεστημένου χρώματος. |
| new_color_argb | int | Τιμή ARGB νέου χρώματος για αντικατάσταση του παλιού χρώματος. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες.<br/>            Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Αντικαθιστά όλα τα μη διαφανή χρώματα με νέο χρώμα και διατηρεί την αρχική τιμή άλφα για να διατηρήσει ομαλές άκρες.<br/>            Σημείωση: εάν το χρησιμοποιήσετε σε εικόνες χωρίς διαφάνεια, όλα τα χρώματα θα αντικατασταθούν με ένα ενιαίο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_argb | int | Νέα τιμή ARGB χρώματος για αντικατάσταση μη διαφανών χρωμάτων. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| new_height | int | Το νέο ύψος. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Τύπος της αλλαγής μεγέθους. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους της εικόνας. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Αλλάζει το πλάτος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Τύπος της αλλαγής μεγέθους. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Αλλάζει το πλάτος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους της εικόνας. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Περιστρέφει την εικόνα γύρω από το κέντρο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γωνία | float | Η γωνία περιστροφής σε μοίρες. Οι θετικές τιμές θα περιστρέφουν δεξιόστροφα. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Ο τύπος περιστροφής/αναστροφής. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο των ορίων της εικόνας προορισμού. Ορίστε το κενό ορθογώνιο για χρήση των ορίων πηγής. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |
| over_write | bool | εάν οριστεί σε <c>true</c> θα αντικαταστήσει τα περιεχόμενα του αρχείου, διαφορετικά θα γίνει προσθήκη. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Αποθηκεύει τα 32-bit ARGB pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | int | Ο πίνακας εικονοστοιχείων ARGB 32-bit. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Αποθηκεύει pixel (μέθοδος ειδική για μορφότυπο).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο για αποθήκευση των εικονοστοιχείων. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Ο πίνακας εικονοστοιχείων ARGB 32-bit. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Ορίζει την παλέτα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα για ορισμό. |
| update_colors | bool | εάν οριστεί σε <c>true</c> τα χρώματα θα ενημερωθούν σύμφωνα με τη νέα παλέτα· διαφορετικά οι δείκτες χρωμάτων παραμένουν αμετάβλητοι. Σημειώστε ότι οι αμετάβλητοι δείκτες μπορεί να προκαλέσουν σφάλμα στην εικόνα κατά τη φόρτωση εάν κάποιοι δείκτες δεν έχουν αντίστοιχες καταχωρίσεις στην παλέτα. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Ορίζει την ανάλυση για αυτό το [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| dpi_x | double | Η οριζόντια ανάλυση, σε κουκκίδες ανά ίντσα, του [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | Η κάθετη ανάλυση, σε κουκκίδες ανά ίντσα, του [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scan_line_index | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |
| argb_32_pixels | int | Ο 32-bit ARGB πίνακας χρωμάτων για εγγραφή. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Γράφει ολόκληρη τη γραμμή σάρωσης στον καθορισμένο δείκτη γραμμής σάρωσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| scan_line_index | int | Δείκτης μηδενικής βάσης της γραμμής σάρωσης. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Ο πίνακας χρωμάτων pixel για εγγραφή. |

