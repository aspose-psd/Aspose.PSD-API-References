---
title: "Γραμματοσειρά"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει μια συγκεκριμένη μορφή για το κείμενο, συμπεριλαμβανομένων των χαρακτηριστικών γραμματοσειράς, μεγέθους και στυλ."
type: docs
weight: 46
url: /el/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Ορίζει μια συγκεκριμένη μορφή για το κείμενο, συμπεριλαμβανομένων της γραμματοσειράς, του μεγέθους και των χαρακτηριστικών στυλ. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Αρχικοποιεί ένα νέο  com.aspose.psd.Font  που χρησιμοποιεί την καθορισμένη υπάρχουσα  com.aspose.psd.Font  και την απαρίθμηση  com.aspose.psd.FontStyle . |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος και στυλ. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του  Font . |
| [equals(Object obj)](#equals-java.lang.Object-) | Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα  com.aspose.psd.Font  και έχει τις ίδιες τιμές ιδιοτήτων με αυτό το  com.aspose.psd.Font . |
| [getBold()](#getBold--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  είναι έντονο. |
| [getCharacterSet()](#getCharacterSet--) | Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που χρησιμοποιεί αυτό το  Font . |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  είναι πλάγιο. |
| [getName()](#getName--) | Λαμβάνει το όνομα προσώπου αυτού του  Font . |
| [getSize()](#getSize--) | Λαμβάνει το em-size αυτού του  Font  μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα  P:Aspose.Imaging.Font.Unit . |
| [getStrikeout()](#getStrikeout--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  καθορίζει μια οριζόντια γραμμή μέσω της γραμματοσειράς. |
| [getStyle()](#getStyle--) | Λαμβάνει πληροφορίες στυλ για αυτό το  Font . |
| [getUnderline()](#getUnderline--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  είναι υπογραμμισμένο. |
| [getUnit()](#getUnit--) | Λαμβάνει τη μονάδα μέτρησης για αυτό το  Font . |
| [hashCode()](#hashCode--) | Λαμβάνει τον κωδικό κατακερματισμού για αυτό το  com.aspose.psd.Font . |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος και μονάδα. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  com.aspose.psd.Font . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Αρχικοποιεί ένα νέο  com.aspose.psd.Font  που χρησιμοποιεί την καθορισμένη υπάρχουσα  com.aspose.psd.Font  και την απαρίθμηση  com.aspose.psd.FontStyle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Η υπάρχουσα  com.aspose.psd.Font  από την οποία θα δημιουργηθεί η νέα  com.aspose.psd.Font . |
| newStyle | int | Η  com.aspose.psd.FontStyle  που θα εφαρμοστεί στο νέο  com.aspose.psd.Font . Πολλαπλές τιμές της απαρίθμησης  com.aspose.psd.FontStyle  μπορούν να συνδυαστούν με τον τελεστή OR. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος. Το σύνολο χαρακτήρων ορίζεται σε  F:Aspose.Imaging.CharacterSet.Default , η μονάδα γραφικών σε  F:Aspose.Imaging.GraphicsUnit.Point , το στυλ γραμματοσειράς σε  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Μία αναπαράσταση συμβολοσειράς του ονόματος του  com.aspose.psd.Font . |
| emSize | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος και στυλ. Το σύνολο χαρακτήρων ορίζεται σε  F:Aspose.Imaging.CharacterSet.Default , η μονάδα γραφικών σε  F:Aspose.Imaging.GraphicsUnit.Point .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Μία αναπαράσταση συμβολοσειράς του ονόματος του  com.aspose.psd.Font . |
| emSize | float | Το em-size, σε σημεία, της νέας γραμματοσειράς. |
| style | int | Το  com.aspose.psd.FontStyle  της νέας γραμματοσειράς. |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ, μονάδα και σύνολο χαρακτήρων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Μία αναπαράσταση συμβολοσειράς του ονόματος του  com.aspose.psd.Font . |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο  unit . |
| style | int | Το  com.aspose.psd.FontStyle  της νέας γραμματοσειράς. |
| unit | int | Το  com.aspose.psd.GraphicsUnit  της νέας γραμματοσειράς. |
| characterSet | int | Ένα σύνολο χαρακτήρων για χρήση με αυτή τη γραμματοσειρά. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος, στυλ και μονάδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Μία αναπαράσταση συμβολοσειράς του ονόματος του  com.aspose.psd.Font . |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο  unit . |
| style | int | Το  com.aspose.psd.FontStyle  της νέας γραμματοσειράς. |
| unit | int | Το  com.aspose.psd.GraphicsUnit  της νέας γραμματοσειράς. |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του  Font .

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Δείχνει εάν το καθορισμένο αντικείμενο είναι ένα  com.aspose.psd.Font  και έχει τις ίδιες τιμές ιδιοτήτων με αυτό το  com.aspose.psd.Font .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το αντικείμενο για δοκιμή. |

**Returns:**
boolean - True εάν η παράμετρος  obj  είναι ένα  com.aspose.psd.Font  και έχει τις ίδιες τιμές ιδιοτήτων με αυτό το  com.aspose.psd.Font ; διαφορετικά, false.
### getBold() {#getBold--}
```
public boolean getBold()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  είναι έντονο.

**Returns:**
boolean - True εάν αυτή η  Font  είναι bold; διαφορετικά, false.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Λαμβάνει μια τιμή byte που καθορίζει το σύνολο χαρακτήρων που χρησιμοποιεί αυτό το  Font .

**Returns:**
int - Ένα σύνολο χαρακτήρων που χρησιμοποιεί αυτή η  Font .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  είναι πλάγιο.

**Returns:**
boolean - True εάν αυτή η  Font  είναι italic; διαφορετικά, false.
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα προσώπου αυτού του  Font .

**Returns:**
java.lang.String - Μία αναπαράσταση συμβολοσειράς του ονόματος προσώπου αυτής της  Font .
### getSize() {#getSize--}
```
public float getSize()
```


Λαμβάνει το em-size αυτού του  Font  μετρημένο στις μονάδες που καθορίζονται από την ιδιότητα  P:Aspose.Imaging.Font.Unit .

**Returns:**
float - Το em-size αυτής της  Font .
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  καθορίζει μια οριζόντια γραμμή μέσω της γραμματοσειράς.

**Returns:**
boolean - True εάν αυτή η  Font  έχει μια οριζόντια γραμμή· διαφορετικά, false.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Λαμβάνει πληροφορίες στυλ για αυτό το  Font .

**Returns:**
int - Μια απαρίθμηση  FontStyle  που περιέχει πληροφορίες στυλ για αυτή τη  Font .
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το  Font  είναι υπογραμμισμένο.

**Returns:**
boolean - True εάν αυτή η  Font  είναι underlined; διαφορετικά, false.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Λαμβάνει τη μονάδα μέτρησης για αυτό το  Font .

**Returns:**
int - Ένα  GraphicsUnit  που αντιπροσωπεύει τη μονάδα μέτρησης για αυτή τη  Font .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Λαμβάνει τον κωδικό κατακερματισμού για αυτό το  com.aspose.psd.Font .

**Returns:**
int - Ο κωδικός κατακερματισμού (hash code) για αυτό το  com.aspose.psd.Font .
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Αρχικοποιεί ένα νέο  com.aspose.psd.Font  χρησιμοποιώντας ένα καθορισμένο μέγεθος και μονάδα. Το σύνολο χαρακτήρων ορίζεται σε  F:Aspose.Imaging.CharacterSet.Default , το στυλ ορίζεται σε  F:Aspose.Imaging.FontStyle.Regular .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | java.lang.String | Μία αναπαράσταση συμβολοσειράς του ονόματος του  com.aspose.psd.Font . |
| emSize | float | Το em-size της νέας γραμματοσειράς στις μονάδες που καθορίζονται από την παράμετρο  unit . |
| unit | int | Το  com.aspose.psd.GraphicsUnit  της νέας γραμματοσειράς. |

**Returns:**
[Font](../../com.aspose.psd/font)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  com.aspose.psd.Font .

**Returns:**
java.lang.String - Μία συμβολοσειρά που αντιπροσωπεύει αυτό το  com.aspose.psd.Font .
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

