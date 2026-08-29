---
title: "StringFormat"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιλαμβάνει πληροφορίες διάταξης κειμένου όπως ευθυγράμμιση, προσανατολισμό και διακοσμητικά σημεία στηλοθέτη, καθώς και χειρισμούς εμφάνισης όπως εισαγωγή αποσιωπητικών, αντικατάσταση εθνικών ψηφίων και χαρακτηριστικά OpenType."
type: docs
weight: 106
url: /el/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Περιλαμβάνει πληροφορίες διάταξης κειμένου (όπως ευθυγράμμιση, προσανατολισμό και διακοσμητικά σημεία στηλοθέτη) χειρισμούς εμφάνισης (όπως εισαγωγή αποσιωπητικών και αντικατάσταση εθνικών ψηφίων) και χαρακτηριστικά OpenType. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [StringFormat()](#StringFormat--) | Αρχικοποιεί ένα νέο αντικείμενο  com.aspose.psd.StringFormat . |
| [StringFormat(int options)](#StringFormat-int-) | Αρχικοποιεί ένα νέο αντικείμενο  com.aspose.psd.StringFormat  με την καθορισμένη απαρίθμηση  com.aspose.psd.StringFormatFlags  και γλώσσα. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Αρχικοποιεί ένα νέο αντικείμενο  com.aspose.psd.StringFormat  από το καθορισμένο υπάρχον αντικείμενο  com.aspose.psd.StringFormat . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα βαθύ κλώνο αυτού του αντικειμένου  com.aspose.psd.StringFormat . |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Αποκτά πληροφορίες ευθυγράμμισης κειμένου στον κατακόρυφο άξονα. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Αποκτά τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Αποκτά τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων. |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Αποκτά τον αριθμό των κενών μεταξύ της αρχής μιας γραμμής κειμένου και του πρώτου διακοσμητικού σημείου στηλοθέτη. |
| [getFormatFlags()](#getFormatFlags--) | Αποκτά μια απαρίθμηση  com.aspose.psd.StringFormatFlags  που περιέχει πληροφορίες μορφοποίησης. |
| [getGenericDefault()](#getGenericDefault--) | Αποκτά ένα γενικό προεπιλεγμένο αντικείμενο  com.aspose.psd.StringFormat . |
| [getGenericTypographic()](#getGenericTypographic--) | Αποκτά ένα γενικό τυπογραφικό αντικείμενο  com.aspose.psd.StringFormat . |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Αποκτά το αντικείμενο  com.aspose.psd.HotkeyPrefix  για αυτό το αντικείμενο  com.aspose.psd.StringFormat . |
| [getLineAlignment()](#getLineAlignment--) | Αποκτά την ευθυγράμμιση γραμμής στον οριζόντιο άξονα. |
| [getTabStops()](#getTabStops--) | Αποκτά έναν πίνακα αποστάσεων μεταξύ των διακοσμητικών σημείων στηλοθέτη στις μονάδες που καθορίζονται από την ιδιότητα  P:Aspose.Imaging.getGraphics().PageUnit . |
| [getTrimming()](#getTrimming--) | Αποκτά την απαρίθμηση  com.aspose.psd.StringTrimming  για αυτό το αντικείμενο  com.aspose.psd.StringFormat . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Ορίζει πληροφορίες ευθυγράμμισης κειμένου στον κατακόρυφο άξονα. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Ορίζει τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Ορίζει τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Ορίζει μια  com.aspose.psd.StringFormatFlags  απαρίθμηση που περιέχει πληροφορίες μορφοποίησης. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Ορίζει το  com.aspose.psd.HotkeyPrefix  αντικείμενο για αυτό το  com.aspose.psd.StringFormat  αντικείμενο. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Ορίζει την ευθυγράμμιση γραμμής στον οριζόντιο άξονα. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Ορίζει τις στάσεις στηλοθέτη για αυτό το  com.aspose.psd.StringFormat  αντικείμενο. |
| [setTrimming(int value)](#setTrimming-int-) | Ορίζει την  com.aspose.psd.StringTrimming  απαρίθμηση για αυτό το  com.aspose.psd.StringFormat  αντικείμενο. |
| [toString()](#toString--) | Μετατρέπει αυτό το  com.aspose.psd.StringFormat  αντικείμενο σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Αρχικοποιεί ένα νέο αντικείμενο  com.aspose.psd.StringFormat .

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Αρχικοποιεί ένα νέο αντικείμενο  com.aspose.psd.StringFormat  με την καθορισμένη απαρίθμηση  com.aspose.psd.StringFormatFlags  και γλώσσα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | int | Η  com.aspose.psd.StringFormatFlags  απαρίθμηση για το νέο  com.aspose.psd.StringFormat  αντικείμενο. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Αρχικοποιεί ένα νέο αντικείμενο  com.aspose.psd.StringFormat  από το καθορισμένο υπάρχον αντικείμενο  com.aspose.psd.StringFormat .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Το  com.aspose.psd.StringFormat  αντικείμενο από το οποίο θα αρχικοποιηθεί το νέο  com.aspose.psd.StringFormat  αντικείμενο. |

### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Δημιουργεί ένα βαθύ κλώνο αυτού του αντικειμένου  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Αποδεσμεύει την τρέχουσα παρουσία.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Αποκτά πληροφορίες ευθυγράμμισης κειμένου στον κατακόρυφο άξονα.

**Returns:**
int - Μια  com.aspose.psd.StringAlignment  απαρίθμηση που καθορίζει πληροφορίες ευθυγράμμισης κειμένου.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Αποκτά τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία.

**Returns:**
int - Ένα αναγνωριστικό γλώσσας National Language Support (NLS) που προσδιορίζει τη γλώσσα που θα χρησιμοποιηθεί όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία. Μπορείτε να περάσετε την ιδιότητα  P:System.Globalization.CultureInfo.LCID  ενός αντικειμένου  System.Globalization.CultureInfo  ως το αναγνωριστικό γλώσσας NLS. Για παράδειγμα, υποθέστε ότι δημιουργείτε ένα αντικείμενο  System.Globalization.CultureInfo  περνώντας τη συμβολοσειρά "ar-EG" σε έναν κατασκευαστή  System.Globalization.CultureInfo . Εάν περάσετε την ιδιότητα  P:System.Globalization.CultureInfo.LCID  αυτού του αντικειμένου  System.Globalization.CultureInfo  μαζί με  com.aspose.psd.StringDigitSubstitute.Traditional  στη μέθοδο  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute) , τότε τα αραβικά-ινδικά ψηφία θα αντικατασταθούν από δυτικά ψηφία κατά την εμφάνιση.

Ο setter εισάγεται για την παρωχημένη μέθοδο setDigitSubstitution.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Αποκτά τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων.

**Returns:**
int - Μια τιμή της  com.aspose.psd.StringDigitSubstitute  απαρίθμησης που καθορίζει πώς να αντικαταστήσετε χαρακτήρες σε μια συμβολοσειρά που δεν μπορεί να εμφανιστεί επειδή δεν υποστηρίζεται από την τρέχουσα γραμματοσειρά.

Ο setter εισάγεται για την παρωχημένη μέθοδο SetDigitSubstitution.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Αποκτά τον αριθμό των κενών μεταξύ της αρχής μιας γραμμής κειμένου και του πρώτου διακοσμητικού σημείου στηλοθέτη.

**Returns:**
float - Η πρώτη απόσταση στηλοθέτη.

Η ιδιότητα εισάγεται για την αφαιρεθείσα μέθοδο GetTabStops.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Αποκτά μια απαρίθμηση  com.aspose.psd.StringFormatFlags  που περιέχει πληροφορίες μορφοποίησης.

**Returns:**
int - Μια  com.aspose.psd.StringFormatFlags  απαρίθμηση που περιέχει πληροφορίες μορφοποίησης.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Αποκτά ένα γενικό προεπιλεγμένο αντικείμενο  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Αποκτά ένα γενικό τυπογραφικό αντικείμενο  com.aspose.psd.StringFormat .

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Αποκτά το αντικείμενο  com.aspose.psd.HotkeyPrefix  για αυτό το αντικείμενο  com.aspose.psd.StringFormat .

**Returns:**
int - Το  com.aspose.psd.HotkeyPrefix  αντικείμενο για αυτό το  com.aspose.psd.StringFormat  αντικείμενο, η προεπιλογή είναι  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Αποκτά την ευθυγράμμιση γραμμής στον οριζόντιο άξονα.

**Returns:**
int - Μια  com.aspose.psd.StringAlignment  απαρίθμηση που αντιπροσωπεύει την ευθυγράμμιση γραμμής.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Αποκτά έναν πίνακα αποστάσεων μεταξύ των διακοσμητικών σημείων στηλοθέτη στις μονάδες που καθορίζονται από την ιδιότητα  P:Aspose.Imaging.getGraphics().PageUnit .

**Returns:**
float[] - Οι στάσεις στηλοθέτη.

Η ιδιότητα εισάγεται για την αφαιρεθείσα μέθοδο GetTabStops.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Αποκτά την απαρίθμηση  com.aspose.psd.StringTrimming  για αυτό το αντικείμενο  com.aspose.psd.StringFormat .

**Returns:**
int - Μια  com.aspose.psd.StringTrimming  απαρίθμηση που υποδεικνύει πώς το κείμενο που σχεδιάζεται με αυτό το  com.aspose.psd.StringFormat  αντικείμενο περικόπτεται όταν υπερβαίνει τα άκρα του ορθογωνίου διάταξης.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ορίζει πληροφορίες ευθυγράμμισης κειμένου στον κατακόρυφο άξονα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια  com.aspose.psd.StringAlignment  απαρίθμηση που καθορίζει πληροφορίες ευθυγράμμισης κειμένου. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Ορίζει τη γλώσσα που χρησιμοποιείται όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Ένα αναγνωριστικό γλώσσας National Language Support (NLS) που προσδιορίζει τη γλώσσα που θα χρησιμοποιηθεί όταν τα τοπικά ψηφία αντικαθίστανται από δυτικά ψηφία. Μπορείτε να περάσετε την ιδιότητα  P:System.Globalization.CultureInfo.LCID  ενός αντικειμένου  System.Globalization.CultureInfo  ως το αναγνωριστικό γλώσσας NLS. Για παράδειγμα, υποθέστε ότι δημιουργείτε ένα αντικείμενο  System.Globalization.CultureInfo  περνώντας τη συμβολοσειρά "ar-EG" σε έναν κατασκευαστή  System.Globalization.CultureInfo . Εάν περάσετε την ιδιότητα  P:System.Globalization.CultureInfo.LCID  αυτού του αντικειμένου  System.Globalization.CultureInfo  μαζί με  com.aspose.psd.StringDigitSubstitute.Traditional  στη μέθοδο  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute) , τότε τα αραβικά-ινδικά ψηφία θα αντικατασταθούν από δυτικά ψηφία κατά την εμφάνιση. |

The setter is introduced for the obsolete method SetDigitSubstitution. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Ορίζει τη μέθοδο που θα χρησιμοποιηθεί για την αντικατάσταση ψηφίων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | int | Μια τιμή της απαρίθμησης com.aspose.psd.StringDigitSubstitute που καθορίζει πώς να αντικαταστήσετε χαρακτήρες σε μια συμβολοσειρά που δεν μπορεί να εμφανιστεί επειδή δεν υποστηρίζονται από την τρέχουσα γραμματοσειρά. |

The setter is introduced for the obsolete method SetDigitSubstitution. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Ορίζει μια  com.aspose.psd.StringFormatFlags  απαρίθμηση που περιέχει πληροφορίες μορφοποίησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια απαρίθμηση com.aspose.psd.StringFormatFlags που περιέχει πληροφορίες μορφοποίησης. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Ορίζει το  com.aspose.psd.HotkeyPrefix  αντικείμενο για αυτό το  com.aspose.psd.StringFormat  αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Το αντικείμενο com.aspose.psd.HotkeyPrefix για αυτό το αντικείμενο com.aspose.psd.StringFormat, η προεπιλογή είναι F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Ορίζει την ευθυγράμμιση γραμμής στον οριζόντιο άξονα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια απαρίθμηση com.aspose.psd.StringAlignment που αντιπροσωπεύει την ευθυγράμμιση της γραμμής. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Ορίζει τις στάσεις στηλοθέτη για αυτό το  com.aspose.psd.StringFormat  αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| firstTabOffset | float | Ο αριθμός των κενών μεταξύ της αρχής μιας γραμμής κειμένου και του πρώτου σημείου στηλοθέτη. |
| tabStops | float[] | Ένας πίνακας αποστάσεων μεταξύ των σημείων στηλοθέτη στις μονάδες που καθορίζονται από την ιδιότητα com.aspose.psd.Graphics.PageUnit. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Ορίζει την  com.aspose.psd.StringTrimming  απαρίθμηση για αυτό το  com.aspose.psd.StringFormat  αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια απαρίθμηση com.aspose.psd.StringTrimming που υποδεικνύει πώς το κείμενο που σχεδιάζεται με αυτό το αντικείμενο com.aspose.psd.StringFormat περικόπτεται όταν υπερβαίνει τα άκρα του ορθογωνίου διάταξης. |

### toString() {#toString--}
```
public String toString()
```


Μετατρέπει αυτό το  com.aspose.psd.StringFormat  αντικείμενο σε μια αναγνώσιμη από άνθρωπο συμβολοσειρά.

**Returns:**
java.lang.String - Μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου com.aspose.psd.StringFormat.
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

