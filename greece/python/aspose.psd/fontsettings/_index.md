---
title: "FontSettings Κλάση"
type: docs
weight: 1370
url: /el/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Λαμβάνει ή ορίζει το προεπιλεγμένο όνομα της γραμματοσειράς. |
| get_system_alternative_font [static] | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [get alternative font]. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| clear_font_replacements() | Καθαρίζει όλες τις αντικαταστάσεις γραμματοσειρών |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Λαμβάνει το όνομα γραμματοσειράς Adobe με βάση το όνομα οικογένειας γραμματοσειράς. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Λαμβάνει τους προεπιλεγμένους φακέλους γραμματοσειρών. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Λαμβάνει τον πίνακα αντικαταστάσεων γραμματοσειρών με βάση το όνομα της γραμματοσειράς |
| [get_fonts_folders()](#get_fonts_folders__4) | Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα των φακέλων όπου το Aspose.Words αναζητά γραμματοσειρές TrueType. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Λαμβάνει τη πιο κατάλληλη γραμματοσειρά αντικατάστασης.<br/>            Εάν όλες οι αντικαταστάσεις δεν επιτρέπονται, τότε θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά.<br/>            Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, τότε θα επιστραφεί η γραμματοσειρά από το όρισμα |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Καθορίζει εάν [is font allowed] [το συγκεκριμένο όνομα γραμματοσειράς]. |
| remove_font_cache_file() | Αφαιρεί το αρχείο cache γραμματοσειρών. |
| reset() | Επαναφέρει το φάκελο γραμματοσειρών και το προεπιλεγμένο όνομα γραμματοσειράς στην προεπιλογή του συστήματος. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Περιορίζει τη χρήση γραμματοσειρών με λίστα γραμματοσειρών. Παρακαλώ ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από τον περιορισμό<br/>            Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε τους περιορισμούς |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, θα βρεθεί αντικατάσταση.<br/>            Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτα. Εάν και αυτή περιοριστεί, θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα.<br/>            Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή όλες οι αντικαταστάσεις δεν επιτρέπονται, θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών.<br/>            Εάν δεν υπάρχουν επιτρεπτές και διαθέσιμες γραμματοσειρές, η βιβλιοθήκη θα προσπαθήσει να χρησιμοποιήσει τη προεπιλεγμένη γραμματοσειρά του συστήματος ακόμη και αν δεν επιτρέπεται. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Αυτή είναι μια συντόμευση προς [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) για ορισμό μόνο ενός καταλόγου γραμματοσειρών.<br/>            Δεν γίνονται έλεγχοι στον φάκελο γραμματοσειρών. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Ορίζει τους φακέλους από τους οποίους φορτώνονται οι γραμματοσειρές TrueType και διαγράφει όλες τις φορτωμένες γραμματοσειρές.<br/>            Δεν γίνονται έλεγχοι στους φακέλους γραμματοσειρών. |
| update_fonts() | Ενημερώνει την κρυφή μνήμη γραμματοσειρών για αρχεία PSD που περιέχουν στρώματα κειμένου. Αυτή η μέθοδος εγγυάται ότι οι γραμματοσειρές από το φάκελο fontsFolder χρησιμοποιώντας<br/>            τη μέθοδο FontSettings.SetFontsFolder(fontsFolder) ή μετά την επαναφορά γραμματοσειρών με FontSettings.Reset() θα ληφθούν υπόψη κατά την επεξεργασία αρχείων PSD. Παρακαλώ χρησιμοποιήστε αυτή τη μέθοδο κάθε φορά που <br/>            καλείται FontSettings.SetFontsFolder(fontsFolder) ή FontSettings.Reset() για εικόνες PSD. Χωρίς την κλήση αυτής της Μεθόδου δεν υπάρχει εγγύηση ότι οι γραμματοσειρές θα ενημερωθούν. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Λαμβάνει το όνομα γραμματοσειράς Adobe με βάση το όνομα οικογένειας γραμματοσειράς.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_family_name | string | Το όνομα οικογένειας γραμματοσειράς. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Το όνομα γραμματοσειράς Adobe βάσει του ονόματος οικογένειας γραμματοσειράς. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Λαμβάνει τους προεπιλεγμένους φακέλους γραμματοσειρών.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Επιστρέφει τον φάκελο του συστήματος |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Λαμβάνει τον πίνακα αντικαταστάσεων γραμματοσειρών με βάση το όνομα της γραμματοσειράς

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Όνομα της γραμματοσειράς. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Πίνακας ονομάτων αντικαταστάσεων για τις παρεχόμενες γραμματοσειρές |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα των φακέλων όπου το Aspose.Words αναζητά γραμματοσειρές TrueType.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Ένα αντίγραφο των τρεχουσών τοποθεσιών γραμματοσειρών. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Λαμβάνει τη πιο κατάλληλη γραμματοσειρά αντικατάστασης.<br/>            Εάν όλες οι αντικαταστάσεις δεν επιτρέπονται, τότε θα επιστραφεί η πρώτη επιτρεπόμενη και διαθέσιμη γραμματοσειρά.<br/>            Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, τότε θα επιστραφεί η γραμματοσειρά από το όρισμα

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Όνομα της γραμματοσειράς. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Το όνομα της αντικατεστημένης γραμματοσειράς |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Καθορίζει εάν [is font allowed] [το συγκεκριμένο όνομα γραμματοσειράς].

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_name | string | Όνομα της γραμματοσειράς. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <c>true</c> εάν [is font allowed] [the specified font name]; διαφορετικά, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Περιορίζει τη χρήση γραμματοσειρών με λίστα γραμματοσειρών. Παρακαλώ ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από τον περιορισμό<br/>            Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε τους περιορισμούς

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_list | string | Η λίστα γραμματοσειρών. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, θα βρεθεί αντικατάσταση.<br/>            Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτα. Εάν και αυτή περιοριστεί, θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα.<br/>            Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή όλες οι αντικαταστάσεις δεν επιτρέπονται, θα χρησιμοποιηθεί η πρώτη επιτρεπόμενη γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών.<br/>            Εάν δεν υπάρχουν επιτρεπτές και διαθέσιμες γραμματοσειρές, η βιβλιοθήκη θα προσπαθήσει να χρησιμοποιήσει τη προεπιλεγμένη γραμματοσειρά του συστήματος ακόμη και αν δεν επιτρέπεται.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_to_replace | string | Η γραμματοσειρά προς αντικατάσταση. |
| font_names | string | Τα ονόματα αντικατάστασης γραμματοσειρών με σειρά ομοιότητας. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Αυτή είναι μια συντόμευση προς [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) για ορισμό μόνο ενός καταλόγου γραμματοσειρών.<br/>            Δεν γίνονται έλεγχοι στον φάκελο γραμματοσειρών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_folder | string | Ο φάκελος γραμματοσειρών. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Ορίζει τους φακέλους από τους οποίους φορτώνονται οι γραμματοσειρές TrueType και διαγράφει όλες τις φορτωμένες γραμματοσειρές.<br/>            Δεν γίνονται έλεγχοι στους φακέλους γραμματοσειρών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| fonts_folders | string | Οι φάκελοι γραμματοσειρών. |
| αναδρομική | bool | εάν οριστεί σε <c>true</c> [recursive]. |

