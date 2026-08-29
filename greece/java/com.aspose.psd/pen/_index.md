---
title: "Pen"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ορίζει ένα αντικείμενο που χρησιμοποιείται για τη σχεδίαση γραμμών, καμπυλών και σχημάτων."
type: docs
weight: 77
url: /el/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Ορίζει ένα αντικείμενο που χρησιμοποιείται για τη σχεδίαση γραμμών, καμπυλών και σχημάτων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με το καθορισμένο χρώμα. |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με τις καθορισμένες ιδιότητες Color και Pen.Width. |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με το καθορισμένο Brush. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με το καθορισμένο Brush και Pen.Width. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Λαμβάνει την ευθυγράμμιση για αυτό το Pen. |
| [getBrush()](#getBrush--) | Λαμβάνει το Brush που καθορίζει τα χαρακτηριστικά αυτού του Pen. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Λαμβάνει το χρώμα αυτού του Pen. |
| [getCompoundArray()](#getCompoundArray--) | Λαμβάνει έναν πίνακα τιμών που καθορίζει ένα σύνθετο Pen. |
| [getCustomEndCap()](#getCustomEndCap--) | Λαμβάνει μια προσαρμοσμένη άκρη για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getCustomStartCap()](#getCustomStartCap--) | Λαμβάνει μια προσαρμοσμένη άκρη για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getDashCap()](#getDashCap--) | Λαμβάνει το στυλ άκρης που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen. |
| [getDashOffset()](#getDashOffset--) | Λαμβάνει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του προτύπου παύλας. |
| [getDashPattern()](#getDashPattern--) | Λαμβάνει έναν πίνακα προσαρμοσμένων παύλων και κενών. |
| [getDashStyle()](#getDashStyle--) | Λαμβάνει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen. |
| [getEndCap()](#getEndCap--) | Λαμβάνει το στυλ άκρης που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getLineJoin()](#getLineJoin--) | Λαμβάνει το στυλ ένωσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getMiterLimit()](#getMiterLimit--) | Λαμβάνει το όριο του πάχους της ένωσης σε γωνία μύτης. |
| [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια του αντικειμένου. |
| [getPenType()](#getPenType--) | Λαμβάνει το στυλ των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getStartCap()](#getStartCap--) | Λαμβάνει το στυλ άκρης που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [getTransform()](#getTransform--) | Λαμβάνει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το Pen. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για τη σχεδίαση. |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το Pen με τον καθορισμένο Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το Pen με τον καθορισμένο Matrix με την καθορισμένη σειρά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Επαναφέρει τον πίνακα γεωμετρικού μετασχηματισμού για αυτό το Pen στην ταυτότητα. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη συγκεκριμένη γωνία. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη συγκεκριμένη γωνία με τη συγκεκριμένη σειρά. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό με τους συγκεκριμένους παράγοντες. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό με τους συγκεκριμένους παράγοντες με τη συγκεκριμένη σειρά. |
| [setAlignment(int value)](#setAlignment-int-) | Ορίζει την ευθυγράμμιση για αυτό το Pen. |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | Ορίζει το Brush που καθορίζει τα χαρακτηριστικά αυτού του Pen. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Ορίζει το χρώμα αυτού του Pen. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Ορίζει έναν πίνακα τιμών που καθορίζει ένα σύνθετο Pen. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | Ορίζει μια προσαρμοσμένη άκρη για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | Ορίζει μια προσαρμοσμένη άκρη για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setDashCap(int value)](#setDashCap-int-) | Ορίζει το στυλ άκρης που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen. |
| [setDashOffset(float value)](#setDashOffset-float-) | Ορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του προτύπου παύλας. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Ορίζει έναν πίνακα προσαρμοσμένων παύλων και κενών. |
| [setDashStyle(int value)](#setDashStyle-int-) | Ορίζει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen. |
| [setEndCap(int value)](#setEndCap-int-) | Ορίζει το στυλ άκρης που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Ορίζει τις τιμές που καθορίζουν το στυλ άκρης που χρησιμοποιείται για το τέλος των γραμμών που σχεδιάζει αυτό το Pen. |
| [setLineJoin(int value)](#setLineJoin-int-) | Ορίζει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Ορίζει το όριο του πάχους της σύνδεσης σε μια γωνία με γωνία κοπής. |
| [setOpacity(float value)](#setOpacity-float-) | Ορίζει τη διαφάνεια του αντικειμένου. |
| [setStartCap(int value)](#setStartCap-int-) | Ορίζει το στυλ άκρης που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το Pen. |
| [setWidth(float value)](#setWidth-float-) | Ορίζει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για το σχεδιασμό. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις συγκεκριμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις συγκεκριμένες διαστάσεις με τη συγκεκριμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με το καθορισμένο χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Μια δομή Color που υποδεικνύει το χρώμα αυτού του Pen. |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με τις καθορισμένες ιδιότητες Color και Pen.Width.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Μια δομή Color που υποδεικνύει το χρώμα αυτού του Pen. |
| πλάτος | float | Μια τιμή που υποδεικνύει το πλάτος αυτού του  Pen . |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με το καθορισμένο Brush.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Ένα  Brush  που καθορίζει τις ιδιότητες γεμίσματος αυτού του  Pen . |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Pen με το καθορισμένο Brush και Pen.Width.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | Ένα  Brush  που καθορίζει τα χαρακτηριστικά αυτού του  Pen . |
| πλάτος | float | Το πλάτος του νέου  Pen . |

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


Λαμβάνει την ευθυγράμμιση για αυτό το Pen.

**Returns:**
int - Ένα  PenAlignment  που αντιπροσωπεύει την ευθυγράμμιση για αυτό το  Pen .
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Λαμβάνει το Brush που καθορίζει τα χαρακτηριστικά αυτού του Pen.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Λαμβάνει το χρώμα αυτού του Pen.

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Λαμβάνει έναν πίνακα τιμών που καθορίζει ένα σύνθετο Pen. Ένα σύνθετο Pen σχεδιάζει μια σύνθετη γραμμή που αποτελείται από παράλληλες γραμμές και κενά.

**Returns:**
float[] - Ένας πίνακας πραγματικών αριθμών που καθορίζει τον σύνθετο πίνακα. Τα στοιχεία του πίνακα πρέπει να είναι σε αυξανόμενη σειρά, όχι μικρότερα από 0 και όχι μεγαλύτερα από 1.
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Λαμβάνει μια προσαρμοσμένη άκρη για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Λαμβάνει μια προσαρμοσμένη άκρη για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Λαμβάνει το στυλ άκρης που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen.

**Returns:**
int - Ένα από τις τιμές του  DashCap  που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή και στο τέλος των παύσεων που αποτελούν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το  Pen .
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Λαμβάνει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του προτύπου παύλας.

**Returns:**
float - Η απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του προτύπου παύσης.
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Λαμβάνει έναν πίνακα προσαρμοσμένων παύλων και κενών.

**Returns:**
float[] - Ένας πίνακας πραγματικών αριθμών που καθορίζει τα μήκη των εναλλασσόμενων παύσεων και κενών σε διακεκομμένες γραμμές.
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Λαμβάνει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen.

**Returns:**
int - Ένα  DashStyle  που αντιπροσωπεύει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το  Pen .
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Λαμβάνει το στυλ άκρης που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
int - Ένα από τις τιμές του  LineCap  που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το  Pen .
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Λαμβάνει το στυλ ένωσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
int - Ένα  LineJoin  που αντιπροσωπεύει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το  Pen .
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Λαμβάνει το όριο του πάχους της ένωσης σε γωνία μύτης.

**Returns:**
float - Το όριο του πάχους της σύνδεσης σε γωνία μύτης.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Λαμβάνει τη διαφάνεια του αντικειμένου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το αντικείμενο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το αντικείμενο είναι πλήρως αδιαφανές.

**Returns:**
float - Η τιμή διαφάνειας.
### getPenType() {#getPenType--}
```
public int getPenType()
```


Λαμβάνει το στυλ των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
int - Μια απαρίθμηση  PenType  που καθορίζει το στυλ των γραμμών που σχεδιάζονται με αυτό το  Pen .
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Λαμβάνει το στυλ άκρης που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen.

**Returns:**
int - Ένα από τις τιμές του  LineCap  που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το  Pen .
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Λαμβάνει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το Pen.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


Λαμβάνει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για τη σχεδίαση.

**Returns:**
float - Το πλάτος αυτού του  Pen .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το Pen με τον καθορισμένο Matrix.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Το αντικείμενο  Matrix  με το οποίο πολλαπλασιάζεται ο πίνακας μετασχηματισμού. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Πολλαπλασιάζει τον πίνακα μετασχηματισμού για αυτό το Pen με τον καθορισμένο Matrix με την καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η  Matrix  με την οποία πολλαπλασιάζεται ο πίνακας μετασχηματισμού. |
| order | int | Η σειρά με την οποία εκτελείται η λειτουργία πολλαπλασιασμού. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Επαναφέρει τον πίνακα γεωμετρικού μετασχηματισμού για αυτό το Pen στην ταυτότητα.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη συγκεκριμένη γωνία. Αυτή η μέθοδος προσθέτει την περιστροφή στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά τη συγκεκριμένη γωνία με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |
| order | int | Ένα  MatrixOrder  που καθορίζει εάν θα προσαρτηθεί ή θα προταθεί ο πίνακας περιστροφής. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τους καθορισμένους παράγοντες. Αυτή η μέθοδος προσθέτει τον πίνακα κλιμάκωσης στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Ο παράγοντας με τον οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Ο παράγοντας με τον οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό με τους συγκεκριμένους παράγοντες με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Ο παράγοντας με τον οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Ο παράγοντας με τον οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |
| order | int | Μια  MatrixOrder  που καθορίζει αν θα προσαρτηθεί ή θα προταθεί ο πίνακας κλιμάκωσης. |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Ορίζει την ευθυγράμμιση για αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια  PenAlignment  που αντιπροσωπεύει την ευθυγράμμιση για αυτό το  Pen . |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


Ορίζει το Brush που καθορίζει τα χαρακτηριστικά αυτού του Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | Μια  Brush  που καθορίζει τα χαρακτηριστικά αυτού του  Pen . |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Ορίζει το χρώμα αυτού του Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Μια  Color  δομή που αντιπροσωπεύει το χρώμα αυτού του  Pen . |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Ορίζει έναν πίνακα τιμών που καθορίζει ένα σύνθετο στυλό. Ένα σύνθετο στυλό σχεδιάζει μια σύνθετη γραμμή που αποτελείται από παράλληλες γραμμές και κενά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float[] | Ένας πίνακας πραγματικών αριθμών που καθορίζει τον σύνθετο πίνακα. Τα στοιχεία του πίνακα πρέπει να είναι σε αύξουσα σειρά, όχι μικρότερα από 0 και όχι μεγαλύτερα από 1. |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Ορίζει μια προσαρμοσμένη άκρη για χρήση στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Μια  CustomLineCap  που αντιπροσωπεύει το άκρο που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το  Pen . |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Ορίζει μια προσαρμοσμένη άκρη για χρήση στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | Μια  CustomLineCap  που αντιπροσωπεύει το άκρο που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το  Pen . |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Ορίζει το στυλ άκρης που χρησιμοποιείται στο τέλος των παύλων που σχηματίζουν διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μία από τις τιμές  DashCap  που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή και στο τέλος των παύλων που αποτελούν τις διακεκομμένες γραμμές που σχεδιάζονται με αυτό το  Pen . |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Ορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του προτύπου παύλας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας. |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Ορίζει έναν πίνακα προσαρμοσμένων παύλων και κενών.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float[] | Ένας πίνακας πραγματικών αριθμών που καθορίζει τα μήκη των εναλλασσόμενων παύλων και κενών σε διακεκομμένες γραμμές. |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Ορίζει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές σχεδιασμένες με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια  DashStyle  που αντιπροσωπεύει το στυλ που χρησιμοποιείται για διακεκομμένες γραμμές που σχεδιάζονται με αυτό το  Pen . |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Ορίζει το στυλ άκρης που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μία από τις τιμές  LineCap  που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στο τέλος των γραμμών που σχεδιάζονται με αυτό το  Pen . |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Ορίζει τις τιμές που καθορίζουν το στυλ άκρης που χρησιμοποιείται για το τέλος των γραμμών που σχεδιάζει αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startCap | int | Μια  LineCap  που αντιπροσωπεύει το στυλ άκρου που θα χρησιμοποιηθεί στην αρχή των γραμμών που σχεδιάζονται με αυτό το  Pen . |
| endCap | int | Μια  LineCap  που αντιπροσωπεύει το στυλ άκρου που θα χρησιμοποιηθεί στο τέλος των γραμμών που σχεδιάζονται με αυτό το  Pen . |
| dashCap | int | Μια  LineCap  που αντιπροσωπεύει το στυλ άκρου που θα χρησιμοποιηθεί στην αρχή ή στο τέλος των διακεκομμένων γραμμών που σχεδιάζονται με αυτό το  Pen . |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Ορίζει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μια  LineJoin  που αντιπροσωπεύει το στυλ σύνδεσης για τα άκρα δύο διαδοχικών γραμμών που σχεδιάζονται με αυτό το  Pen . |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Ορίζει το όριο του πάχους της σύνδεσης σε μια γωνία με γωνία κοπής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το όριο του πάχους της σύνδεσης σε μια γωνία μύτης σφήνας. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ορίζει τη διαφάνεια του αντικειμένου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το αντικείμενο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το αντικείμενο είναι πλήρως αδιαφανές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η τιμή διαφάνειας. |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Ορίζει το στυλ άκρης που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Μία από τις τιμές  LineCap  που αντιπροσωπεύει το στυλ άκρου που χρησιμοποιείται στην αρχή των γραμμών που σχεδιάζονται με αυτό το  Pen . |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Ορίζει ένα αντίγραφο του γεωμετρικού μετασχηματισμού για αυτό το Pen.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | Ένα αντίγραφο του  Matrix  που αντιπροσωπεύει τη γεωμετρική μετασχηματισμό για αυτό το  Pen . |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Ορίζει το πλάτος αυτού του Pen, σε μονάδες του αντικειμένου Graphics που χρησιμοποιείται για το σχεδιασμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Το πλάτος αυτού του  Pen . |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Μεταφράζει τη τοπική γεωμετρική μετασχηματισμό κατά τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει την μετάφραση στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Μεταφράζει τον τοπικό γεωμετρικό μετασχηματισμό με τις συγκεκριμένες διαστάσεις με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |
| order | int | Η σειρά (προσθήκη στην αρχή ή προσθήκη στο τέλος) με την οποία εφαρμόζεται η μετάφραση. |

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

