---
title: "FontSettings"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Γενικές ρυθμίσεις γραμματοσειράς του renderer μορφότυπων διανυσματικών εικόνων"
type: docs
weight: 47
url: /el/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Γενικές ρυθμίσεις γραμματοσειράς του renderer μορφότυπων διανυσματικών εικόνων
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Λαμβάνει το όνομα γραμματοσειράς adobe με βάση το όνομα οικογένειας γραμματοσειράς. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Λαμβάνει το προεπιλεγμένο όνομα γραμματοσειράς. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Λαμβάνει τους προεπιλεγμένους φακέλους γραμματοσειρών. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Λαμβάνει τον πίνακα αντικατάστασης γραμματοσειρών με βάση το όνομα γραμματοσειράς. |
| [getFontsFolders()](#getFontsFolders--) | Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα φακέλων όπου το Aspose.Imaging αναζητά γραμματοσειρές TrueType. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Λαμβάνει τη πιο κατάλληλη γραμματοσειρά αντικατάστασης. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Καθορίζει εάν [is font allowed] [το συγκεκριμένο όνομα γραμματοσειράς]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Αφαιρεί το αρχείο cache γραμματοσειρών. |
| [reset()](#reset--) | Επαναφέρει τον φάκελο γραμματοσειρών και το προεπιλεγμένο όνομα γραμματοσειράς στην προεπιλογή του συστήματος. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Περιορίζει τη χρήση γραμματοσειρών με βάση λίστα γραμματοσειρών. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Ορίζει το προεπιλεγμένο όνομα γραμματοσειράς. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Παρακάμψη λίστας φακέλων γραμματοσειρών για φάκελο |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Παρακάμψη λίστας φακέλων γραμματοσειρών για φακέλους |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Ορίζει τους φακέλους από τους οποίους φορτώνονται γραμματοσειρές TrueType και διαγράφει όλες τις φορτωμένες γραμματοσειρές. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Ενημερώνει την cache γραμματοσειρών για αρχεία PSD που περιέχουν στρώματα κειμένου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Λαμβάνει το όνομα γραμματοσειράς adobe με βάση το όνομα οικογένειας γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Το όνομα οικογένειας γραμματοσειράς. |

**Returns:**
java.lang.String - Το όνομα γραμματοσειράς adobe με βάση το όνομα οικογένειας γραμματοσειράς.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Λαμβάνει το προεπιλεγμένο όνομα γραμματοσειράς.

**Returns:**
java.lang.String - το προεπιλεγμένο όνομα γραμματοσειράς
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Λαμβάνει τους προεπιλεγμένους φακέλους γραμματοσειρών.

**Returns:**
java.lang.String[] - Επιστρέφει το φάκελο του συστήματος
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Λαμβάνει τον πίνακα αντικατάστασης γραμματοσειρών με βάση το όνομα γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Όνομα της γραμματοσειράς. |

**Returns:**
java.lang.String[] - Πίνακας ονομάτων αντικαταστάσεων για τις παρεχόμενες γραμματοσειρές
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Λαμβάνει ένα αντίγραφο του πίνακα που περιέχει τη λίστα φακέλων όπου το Aspose.Imaging αναζητά γραμματοσειρές TrueType.

Η επιστρεφόμενη τιμή είναι ένα αντίγραφο των δεδομένων που χρησιμοποιεί το Aspose.Imaging. Εάν αλλάξετε τις καταχωρήσεις στον επιστρεφόμενο πίνακα, δεν θα επηρεάσει την απόδοση του εγγράφου. Για να καθορίσετε νέες θέσεις γραμματοσειρών, χρησιμοποιήστε τη μέθοδο  setFontsFolders .

**Returns:**
java.lang.String[] - Ένα αντίγραφο των τρεχουσών θέσεων γραμματοσειρών.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [get alternative font].

Τιμή:  true  εάν [get alternative font]; διαφορετικά,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Αποκτά τη πιο κατάλληλη γραμματοσειρά αντικατάστασης. Εάν όλες οι αντικαταστάσεις δεν επιτρέπονται, θα επιστραφεί η πρώτη επιτρεπτή και διαθέσιμη γραμματοσειρά. Εάν δεν υπάρχουν διαθέσιμες γραμματοσειρές, θα επιστραφεί η γραμματοσειρά από το όρισμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Όνομα της γραμματοσειράς. |

**Returns:**
java.lang.String - Το όνομα της αντικατεστημένης γραμματοσειράς
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


Καθορίζει εάν [is font allowed] [το συγκεκριμένο όνομα γραμματοσειράς].

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Όνομα της γραμματοσειράς. |

**Returns:**
boolean -  true  εάν [is font allowed] [το καθορισμένο όνομα γραμματοσειράς]; διαφορετικά,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


Αφαιρεί το αρχείο cache γραμματοσειρών.

### reset() {#reset--}
```
public static void reset()
```


Επαναφέρει τον φάκελο γραμματοσειρών και το προεπιλεγμένο όνομα γραμματοσειράς στην προεπιλογή του συστήματος.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Περιορίζει τη γραμματοσειρά χρησιμοποιώντας λίστα γραμματοσειρών. Παρακαλώ ελέγξτε τα πραγματικά ονόματα γραμματοσειρών πριν από τον περιορισμό. Ορίστε τη λίστα επιτρεπόμενων γραμματοσειρών σε Null για να αφαιρέσετε τους περιορισμούς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontList | java.lang.String[] | Η λίστα γραμματοσειρών. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Ορίζει το προεπιλεγμένο όνομα γραμματοσειράς.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Το προεπιλεγμένο όνομα της γραμματοσειράς. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Ορίζει τη λίστα αντικατάστασης γραμματοσειρών. Εάν η γραμματοσειρά δεν επιτρέπεται, θα βρεθεί αντικατάσταση. Η πρώτη γραμματοσειρά στη λίστα θα χρησιμοποιηθεί πρώτα. Εάν είναι επίσης περιορισμένη, θα επιλεγεί η επόμενη γραμματοσειρά από τη λίστα. Εάν η γραμματοσειρά δεν έχει αντικαταστάσεις ή όλες οι αντικαταστάσεις δεν επιτρέπονται, θα χρησιμοποιηθεί η πρώτη επιτρεπτή γραμματοσειρά από τη λίστα επιτρεπόμενων γραμματοσειρών. Εάν δεν υπάρχουν επιτρεπτές και διαθέσιμες γραμματοσειρές, η βιβλιοθήκη θα προσπαθήσει να χρησιμοποιήσει την προεπιλεγμένη γραμματοσειρά του συστήματος ακόμη και αν δεν επιτρέπεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontToReplace | java.lang.String | Η γραμματοσειρά προς αντικατάσταση. |
| fontNames | java.lang.String[] | Τα ονόματα των γραμματοσειρών αντικατάστασης με σειρά ομοιότητας. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Παρακάμψη λίστας φακέλων γραμματοσειρών για φάκελο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| folder | java.lang.String | Φάκελος με γραμματοσειρές TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Παρακάμψη λίστας φακέλων γραμματοσειρών για φακέλους

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| folders | java.lang.String[] | Πίνακας φακέλων |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Ορίζει τους φακέλους από τους οποίους φορτώνονται οι γραμματοσειρές TrueType και καθαρίζει όλες τις φορτωμένες γραμματοσειρές. Δεν γίνονται έλεγχοι στους φακέλους γραμματοσειρών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| folders | java.lang.String[] | Οι φάκελοι γραμματοσειρών. |
| recursive | boolean | εάν οριστεί σε  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν [get alternative font].

Τιμή:  true  εάν [get alternative font]; διαφορετικά,  false .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Ενημερώνει την κρυφή μνήμη γραμματοσειρών για αρχεία PSD που περιέχουν στρώσεις κειμένου. Αυτή η Μέθοδος εγγυάται ότι οι γραμματοσειρές από το φάκελο fontsFolder χρησιμοποιώντας τη μέθοδο FontSettings.setFontsFolder(fontsFolder) ή μετά την επαναφορά γραμματοσειρών με FontSettings.reset() θα ληφθούν υπόψη κατά την επεξεργασία αρχείων PSD. Παρακαλούμε χρησιμοποιήστε αυτή τη μέθοδο κάθε φορά που καλείται FontSettings.setFontsFolder(fontsFolder) ή FontSettings.reset() για εικόνες PSD. Χωρίς την κλήση αυτής της Μεθόδου δεν υπάρχει εγγύηση ότι οι γραμματοσειρές θα ενημερωθούν.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

