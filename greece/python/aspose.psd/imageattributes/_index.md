---
title: "ImageAttributes Κλάση"
type: docs
weight: 2180
url: /el/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης ImageAttributes |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| clear_brush_remap_table() | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος πινέλου αυτού του αντικειμένου [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) αντικειμένου. |
| clear_color_key() | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [clear_color_key(type)](#clear_color_key_type_1) | Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| clear_color_matrix() | Καθαρίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Καθαρίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία. |
| clear_gamma() | Απενεργοποιεί τη διόρθωση γάμμα για την προεπιλεγμένη κατηγορία. |
| [clear_gamma(type)](#clear_gamma_type_3) | Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία. |
| clear_no_op() | Καθαρίζει τη ρύθμιση NoOp για την προεπιλεγμένη κατηγορία. |
| [clear_no_op(type)](#clear_no_op_type_4) | Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία. |
| clear_output_channel() | Καθαρίζει τη ρύθμιση του καναλιού εξόδου CMYK (cyan-magenta-yellow-black) για την προεπιλεγμένη κατηγορία. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Καθαρίζει τη ρύθμιση του καναλιού εξόδου (cyan-magenta-yellow-black) για μια καθορισμένη κατηγορία. |
| clear_output_channel_color_profile() | Καθαρίζει τη ρύθμιση του προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Καθαρίζει τη ρύθμιση του προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| clear_remap_table() | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| clear_threshold() | Καθαρίζει την τιμή κατωφλίου για την προεπιλεγμένη κατηγορία. |
| [clear_threshold(type)](#clear_threshold_type_8) | Καθαρίζει την τιμή κατωφλίου για μια καθορισμένη κατηγορία. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για μια καθορισμένη κατηγορία. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Ορίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία. |
| set_no_op() | Απενεργοποιεί τη ρύθμιση χρώματος για την προεπιλεγμένη κατηγορία. |
| [set_no_op(type)](#set_no_op_type_20) | Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία. |
| [set_remap_table(map)](#set_remap_table_map_25) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Ορίζει το όριο (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Ορίζει το όριο (εύρος διαφάνειας) για μια καθορισμένη κατηγορία. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί μια υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί μια υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης ImageAttributes

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Καθαρίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία το κλειδί χρώματος διαγράφεται. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Καθαρίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία ο πίνακας ρύθμισης χρώματος διαγράφεται. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Απενεργοποιεί τη διόρθωση γάμμα για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία η διόρθωση γάμμα είναι απενεργοποιημένη. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Καθαρίζει τη ρύθμιση NoOp για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία η ρύθμιση NoOp διαγράφεται. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Καθαρίζει τη ρύθμιση του καναλιού εξόδου (cyan-magenta-yellow-black) για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία η ρύθμιση του καναλιού εξόδου διαγράφεται. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Καθαρίζει τη ρύθμιση του προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία η ρύθμιση του προφίλ καναλιού εξόδου διαγράφεται. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Καθαρίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία ο πίνακας επαναχαρτογράφησης διαγράφεται. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Καθαρίζει την τιμή κατωφλίου για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία το όριο διαγράφεται. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την κατηγορία πινέλου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Μια σειρά αντικειμένων [ColorMap](/psd/python-net/aspose.psd/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Ορίζει το κλειδί χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Η χαμηλή τιμή του χρωματικού κλειδιού. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Η υψηλή τιμή του χρωματικού κλειδιού. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Ορίζει το κλειδί χρώματος (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Η χαμηλή τιμή του χρωματικού κλειδιού. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Η υψηλή τιμή του χρωματικού κλειδιού. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία το χρωματικό κλειδί ορίζεται. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ένα στοιχείο του [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστούν από τους πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Ορίζει τον πίνακα ρύθμισης χρώματος και τον πίνακα ρύθμισης γκρι κλίμακας για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής κλίμακας του γκρι. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ένα στοιχείο του [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστούν από τους πίνακες προσαρμογής χρώματος και κλίμακας του γκρι. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία οι πίνακες προσαρμογής χρώματος και κλίμακας του γκρι ορίζονται. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Ορίζει τον πίνακα ρύθμισης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ένα στοιχείο του [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστεί από τον πίνακα προσαρμογής χρώματος. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Ορίζει τον πίνακα ρύθμισης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Ο πίνακας προσαρμογής χρώματος. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ένα στοιχείο του [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) που καθορίζει τον τύπο της εικόνας και του χρώματος που θα επηρεαστεί από τον πίνακα προσαρμογής χρώματος. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία ο πίνακας προσαρμογής χρώματος ορίζεται. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Ορίζει την τιμή γάμμα για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γάμμα | float | Η τιμή διόρθωσης γάμμα. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Ορίζει την τιμή γάμμα για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γάμμα | float | Η τιμή διόρθωσης γάμμα. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο της απαρίθμησης [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία η τιμή γάμμα ορίζεται. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Απενεργοποιεί τη ρύθμιση χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία η διόρθωση χρώματος απενεργοποιείται. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Ένα στοιχείο του [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) που καθορίζει το κανάλι εξόδου. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Ορίζει το κανάλι εξόδου CMYK (κυανό-ματζέντα-κίτρινο-μαύρο) για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Ένα στοιχείο του [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) που καθορίζει το κανάλι εξόδου. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία το κανάλι εξόδου ορίζεται. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_profile_filename | string | Το όνομα διαδρομής ενός αρχείου προφίλ χρώματος. Εάν το αρχείο προφίλ χρώματος βρίσκεται στον κατάλογο %SystemRoot%\System32\Spool\Drivers\Color, αυτή η παράμετρος μπορεί να είναι το όνομα του αρχείου. Διαφορετικά, αυτή η παράμετρος πρέπει να είναι το πλήρως καθορισμένο όνομα διαδρομής. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Ορίζει το αρχείο προφίλ χρώματος του καναλιού εξόδου για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| color_profile_filename | string | Το όνομα διαδρομής ενός αρχείου προφίλ χρώματος. Εάν το αρχείο προφίλ χρώματος βρίσκεται στον κατάλογο %SystemRoot%\System32\Spool\Drivers\Color, αυτή η παράμετρος μπορεί να είναι το όνομα του αρχείου. Διαφορετικά, αυτή η παράμετρος πρέπει να είναι το πλήρως καθορισμένο όνομα διαδρομής. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία το αρχείο προφίλ χρώματος του καναλιού εξόδου ορίζεται. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Μια σειρά ζευγών χρωμάτων τύπου [ColorMap](/psd/python-net/aspose.psd/colormap/). Κάθε ζεύγος χρωμάτων περιέχει ένα υπάρχον χρώμα (η πρώτη τιμή) και το χρώμα στο οποίο θα αντιστοιχιστεί (η δεύτερη τιμή). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Ορίζει τον πίνακα επαναχαρτογράφησης χρώματος για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Μια σειρά ζευγών χρωμάτων τύπου [ColorMap](/psd/python-net/aspose.psd/colormap/). Κάθε ζεύγος χρωμάτων περιέχει ένα υπάρχον χρώμα (η πρώτη τιμή) και το χρώμα στο οποίο θα αντιστοιχιστεί (η δεύτερη τιμή). |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία ο πίνακας επαναχαρτογράφησης χρώματος ορίζεται. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Ορίζει το όριο (εύρος διαφάνειας) για την προεπιλεγμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| threshold | float | Ένας πραγματικός αριθμός που καθορίζει την τιμή του ορίου. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Ορίζει το όριο (εύρος διαφάνειας) για μια καθορισμένη κατηγορία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| threshold | float | Μια τιμή κατωφλίου από 0.0 έως 1.0 που χρησιμοποιείται ως σημείο διακοπής για την ταξινόμηση χρωμάτων που θα αντιστοιχιστούν είτε σε μέγιστη είτε σε ελάχιστη τιμή. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ένα στοιχείο του [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) που καθορίζει την κατηγορία για την οποία ορίζεται το κατώφλι χρώματος. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Ορίζει τη λειτουργία περιτύλιξης που χρησιμοποιείται για να αποφασίσει πώς θα τοποθετηθεί ένα υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ένα στοιχείο του [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς χρησιμοποιούνται αντίγραφα μιας εικόνας για την επικάλυψη μιας περιοχής. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί μια υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ένα στοιχείο του [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς χρησιμοποιούνται αντίγραφα μιας εικόνας για την επικάλυψη μιας περιοχής. |
| color | [Color](/psd/python-net/aspose.psd/color) | Ένα αντικείμενο [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) που καθορίζει το χρώμα των εικονοστοιχείων εκτός μιας αποδομένης εικόνας. Αυτό το χρώμα είναι ορατό εάν η παράμετρος mode οριστεί σε [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) και το πηγαίο ορθογώνιο που περνιέται στη DrawImage είναι μεγαλύτερο από την ίδια την εικόνα. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Ορίζει τη λειτουργία περιτύλιξης και το χρώμα που χρησιμοποιούνται για να αποφασίσουν πώς θα τοποθετηθεί μια υφή πάνω σε ένα σχήμα ή στα όρια του σχήματος. Μια υφή τοποθετείται επαναλαμβανόμενα πάνω σε ένα σχήμα για να το γεμίσει όταν η υφή είναι μικρότερη από το σχήμα που γεμίζει.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ένα στοιχείο του [WrapMode](/psd/python-net/aspose.psd/wrapmode/) που καθορίζει πώς χρησιμοποιούνται αντίγραφα μιας εικόνας για την επικάλυψη μιας περιοχής. |
| color | [Color](/psd/python-net/aspose.psd/color) | Ένα αντικείμενο χρώματος που καθορίζει το χρώμα των εικονοστοιχείων εκτός μιας αποδομένης εικόνας. Αυτό το χρώμα είναι ορατό εάν η παράμετρος mode οριστεί σε [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) και το πηγαίο ορθογώνιο που περνιέται στη DrawImage είναι μεγαλύτερο από την ίδια την εικόνα. |
| clamp | bool | Αυτή η παράμετρος δεν έχει καμία επίδραση. Ορίστε την σε false. |

