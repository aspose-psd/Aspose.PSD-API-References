---
title: "Κλάση Image"
type: docs
weight: 2170
url: /el/python-net/aspose.psd/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Image

**Inheritance:** IObjectWithBounds, DataStreamSupporter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν γίνεται αυτόματη προσαρμογή παλέτας. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Λαμβάνει ή ορίζει μια τιμή για το χρώμα φόντου. |
| bits_per_pixel | int | r | Λαμβάνει τον αριθμό των bits ανά pixel της εικόνας. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Λαμβάνει τα όρια της εικόνας. |
| buffer_size_hint | int | r/w | Λαμβάνει ή ορίζει την υπόδειξη μεγέθους buffer που ορίζεται ως μέγιστο επιτρεπόμενο μέγεθος για όλα τα εσωτερικά buffers. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Λαμβάνει το δοχείο [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Λαμβάνει τη ροή δεδομένων του αντικειμένου. |
| απορρίφθηκε | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει απελευθερωθεί. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Λαμβάνει μια τιμή μορφής αρχείου |
| έχει_χρώμα_υπόβαθρου | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η εικόνα έχει χρώμα φόντου. |
| height | int | r | Λαμβάνει το ύψος της εικόνας. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Λαμβάνει ή ορίζει τον παρακολουθητή διακοπής. |
| είναι_στη_μνήμη | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν τα δεδομένα του αντικειμένου είναι προσωρινά αποθηκευμένα αυτή τη στιγμή και δεν απαιτείται ανάγνωση δεδομένων. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Λαμβάνει ή ορίζει την παλέτα χρωμάτων. Η παλέτα χρωμάτων δεν χρησιμοποιείται όταν τα pixel αναπαρίστανται άμεσα. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Λαμβάνει το μέγεθος της εικόνας. |
| use_palette | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα εικόνας χρησιμοποιείται. |
| width | int | r | Λαμβάνει το πλάτος της εικόνας. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| cache_data() | Αποθηκεύει στην κρυφή μνήμη τα δεδομένα και εξασφαλίζει ότι δεν θα γίνει επιπλέον φόρτωση δεδομένων από το υποκείμενο [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από τη συγκεκριμένη διαδρομή αρχείου και προαιρετικά χρησιμοποιώντας τις καθορισμένες επιλογές ανοίγματος. |
| [can_load(stream)](#can_load_stream_3) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Καθορίζει εάν η εικόνα μπορεί να φορτωθεί από το καθορισμένο ρεύμα και προαιρετικά χρησιμοποιώντας το καθορισμένο <paramref name=\"loadOptions\" />. |
| [can_save(options)](#can_save_options_5) | Καθορίζει εάν η εικόνα μπορεί να αποθηκευτεί στο καθορισμένο μορφότυπο αρχείου που αντιπροσωπεύεται από τις δοθείσες επιλογές αποθήκευσης. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Δημιουργεί μια νέα εικόνα χρησιμοποιώντας τις καθορισμένες επιλογές δημιουργίας. |
| [get_default_options(args)](#get_default_options_args_7) | Λαμβάνει τις προεπιλεγμένες επιλογές. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | Λαμβάνει το μορφότυπο αρχείου. |
| [get_file_format(stream)](#get_file_format_stream_9) | Λαμβάνει το μορφότυπο αρχείου. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | Λαμβάνει το ορθογώνιο που ταιριάζει στην τρέχουσα εικόνα. |
| [get_original_options()](#get_original_options__12) | Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων αρχείου.<br/>            Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες.<br/>            Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) μέθοδο, θα παραχθεί η εξαγόμενη εικόνα PNG με 8-bit ανά pixel.<br/>            Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις<br/>            στη [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) μέθοδο ως δεύτερη παράμετρο. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | Λαμβάνει ένα ανάλογο ύψος. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | Λαμβάνει ένα ανάλογο πλάτος. |
| [load(file_path)](#load_file_path_15) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | Φορτώνει μια νέα εικόνα από το καθορισμένο αρχείο. |
| [load(stream)](#load_stream_17) | Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα. |
| [load(stream, load_options)](#load_stream_load_options_18) | Φορτώνει μια νέα εικόνα από το καθορισμένο ρεύμα. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | Αλλάζει το μέγεθος της εικόνας. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | Αλλάζει το μέγεθος της εικόνας. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | Αλλάζει το ύψος αναλογικά. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | Αλλάζει το ύψος αναλογικά. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | Αλλάζει το ύψος αναλογικά. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | Αλλάζει το πλάτος αναλογικά. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | Αλλάζει το πλάτος αναλογικά. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα. |
| save() | Αποθηκεύει τα δεδομένα της εικόνας στο υποκείμενο ρεύμα. |
| [save(file_path)](#save_file_path_29) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(file_path, options)](#save_file_path_options_30) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου. |
| [save(stream)](#save_stream_33) | Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή. |
| [save(stream, options_base)](#save_stream_options_base_34) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | Ορίζει την παλέτα εικόνας. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_save(options) {#can_save_options_5}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


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


### Method: get_default_options(args) {#get_default_options_args_7}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


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


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

Λαμβάνει τις επιλογές βάσει των αρχικών ρυθμίσεων αρχείου.<br/>            Αυτό μπορεί να είναι χρήσιμο για τη διατήρηση του βάθους χρώματος και άλλων παραμέτρων της αρχικής εικόνας αμετάβλητες.<br/>            Για παράδειγμα, εάν φορτώσουμε μια ασπρόμαυρη εικόνα PNG με 1 bit ανά pixel και στη συνέχεια την αποθηκεύσουμε χρησιμοποιώντας τη<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) μέθοδο, θα παραχθεί η εξαγόμενη εικόνα PNG με 8-bit ανά pixel.<br/>            Για να το αποφύγουμε και να αποθηκεύσουμε την εικόνα PNG με 1-bit ανά pixel, χρησιμοποιήστε αυτή τη μέθοδο για να λάβετε τις αντίστοιχες επιλογές αποθήκευσης και περάστε τις<br/>            στη [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) μέθοδο ως δεύτερη παράμετρο.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές βασισμένες στις αρχικές ρυθμίσεις του αρχείου. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


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


### Method: load(file_path)  [static] {#load_file_path_15}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


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


### Method: load(stream)  [static] {#load_stream_17}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| new_height | int | Το νέο ύψος. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Τύπος της αλλαγής μεγέθους. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

Αλλάζει το ύψος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_height | int | Το νέο ύψος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους της εικόνας. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

Αλλάζει το πλάτος αναλογικά. Χρησιμοποιείται η προεπιλογή [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

Αλλάζει το πλάτος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Τύπος της αλλαγής μεγέθους. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

Αλλάζει το πλάτος αναλογικά.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_width | int | Το νέο πλάτος. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Οι ρυθμίσεις αλλαγής μεγέθους της εικόνας. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

Περιστρέφει, αναστρέφει ή περιστρέφει και αναστρέφει την εικόνα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Τύπος της περιστροφής/αναστροφής. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη θέση αρχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_path | string | Η διαδρομή αρχείου για αποθήκευση των δεδομένων του αντικειμένου. |
| over_write | bool | εάν οριστεί σε <c>true</c> θα αντικαταστήσει τα περιεχόμενα του αρχείου, διαφορετικά θα γίνει προσθήκη. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

Αποθηκεύει τα δεδομένα του αντικειμένου στην καθορισμένη ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων του αντικειμένου. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

Αποθηκεύει τα δεδομένα της εικόνας στην καθορισμένη ροή με το καθορισμένο μορφότυπο αρχείου σύμφωνα με τις επιλογές αποθήκευσης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Η ροή για αποθήκευση των δεδομένων της εικόνας. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Οι επιλογές αποθήκευσης. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

Ορίζει την παλέτα εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Η παλέτα για ορισμό. |
| update_colors | bool | εάν οριστεί σε <c>true</c> τα χρώματα θα ενημερωθούν σύμφωνα με τη νέα παλέτα· διαφορετικά οι δείκτες χρωμάτων παραμένουν αμετάβλητοι. Σημειώστε ότι οι αμετάβλητοι δείκτες μπορεί να προκαλέσουν σφάλμα στην εικόνα κατά τη φόρτωση εάν κάποιοι δείκτες δεν έχουν αντίστοιχες καταχωρίσεις στην παλέτα. |

