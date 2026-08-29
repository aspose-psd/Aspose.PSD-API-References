---
title: "Matrix"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντικαθιστά τον πίνακα GDI."
type: docs
weight: 69
url: /el/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

Αντικαθιστά τη μήτρα GDI+.

Οι περισσότεροι αλγόριθμοι προέρχονται από το AffineTransform.java της Sun. Τα ονόματα της Java για τα στοιχεία του πίνακα που χρησιμοποιούνται εσωτερικά. Χάρτης των ονομάτων Java σε .net με περιγραφή: m00 M11 Κλίμακα X m10 M12 Κάμψη Y m01 M21 Κάμψη X m11 M22 Κλίμακα Y m02 M31 Μετάθεση X m12 M32 Μετάθεση Y
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Matrix()](#Matrix--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Matrix ως τον μοναδιαίο πίνακα. |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Αρχικοποιεί ένα νέο αντικείμενο της  Matrix  κλάσης. |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Δημιουργεί ένα αντίγραφο της  Matrix  κλάσης. |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | Αρχικοποιεί ένα νέο αντικείμενο της  Aspose.Imaging.Matrix  κλάσης στην γεωμετρική μεταστροφή που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων. |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | Αρχικοποιεί ένα νέο αντικείμενο της  Aspose.Imaging.Matrix  κλάσης στην γεωμετρική μεταστροφή που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | Αυτό το δυαδικό σημείο σημαίας υποδεικνύει ότι η μεταστροφή που ορίζεται από αυτό το αντικείμενο εκτελεί αναστροφή καθρέφτη γύρω από κάποιο άξονα, η οποία αλλάζει το κανονικά δεξιόχειρο σύστημα συντεταγμένων σε αριστερόχειρο σύστημα, επιπλέον των μετατροπών που υποδεικνύονται από άλλα δυαδικά σημεία σημαίας. |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | Αυτό το δυαδικό σημείο σημαίας υποδεικνύει ότι η μεταστροφή που ορίζεται από αυτό το αντικείμενο εκτελεί περιστροφή με αυθαίρετη γωνία, επιπλέον των μετατροπών που υποδεικνύονται από άλλα δυαδικά σημεία σημαίας. |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | Μια γενική κλίμακα πολλαπλασιάζει το μήκος των διανυσμάτων κατά διαφορετικά ποσά στις κατευθύνσεις x και y χωρίς να αλλάζει τη γωνία μεταξύ των κάθετων διανυσμάτων. |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | Αυτή η σταθερά υποδεικνύει ότι ο μετασχηματισμός που ορίζεται από αυτό το αντικείμενο εκτελεί μια αυθαίρετη μετατροπή των εισερχόμενων συντεταγμένων. |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | Ένας ταυτοτικός μετασχηματισμός είναι αυτός όπου οι συντεταγμένες εξόδου είναι πάντα ίδιες με τις συντεταγμένες εισόδου. |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | Αυτή η σταθερά είναι μια μάσκα bit για οποιοδήποτε από τα bits σημαίας περιστροφής. |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | Αυτή η σταθερά είναι μια μάσκα bit για οποιοδήποτε από τα bits σημαίας κλιμάκωσης. |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | Αυτό το bit σημαίας υποδεικνύει ότι ο μετασχηματισμός που ορίζεται από αυτό το αντικείμενο εκτελεί μια περιστροφή τεταρτημορίου κατά κάποιο πολλαπλάσιο των 90 μοιρών, επιπλέον των μετατροπών που υποδεικνύονται από άλλα bits σημαίας. |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | Μια μετάθεση μετακινεί τις συντεταγμένες κατά μια σταθερή τιμή στο x και y χωρίς να αλλάζει το μήκος ή τη γωνία των διανυσμάτων. |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | Μια ομοιόμορφη κλιμάκωση πολλαπλασιάζει το μήκος των διανυσμάτων κατά την ίδια τιμή και στις δύο κατευθύνσεις x και y χωρίς να αλλάζει τη γωνία μεταξύ των διανυσμάτων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το καθορισμένο  System.Object  είναι ίσο με αυτήν την παρουσία. |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | Λαμβάνει το αντίγραφο των στοιχείων του πίνακα. |
| [getM11()](#getM11--) | Λαμβάνει το στοιχείο του πίνακα στην πρώτη γραμμή, πρώτη στήλη. |
| [getM12()](#getM12--) | Λαμβάνει το στοιχείο του πίνακα στην πρώτη γραμμή, δεύτερη στήλη. |
| [getM21()](#getM21--) | Λαμβάνει το στοιχείο του πίνακα στη δεύτερη γραμμή, πρώτη στήλη. |
| [getM22()](#getM22--) | Λαμβάνει το στοιχείο του πίνακα στη δεύτερη γραμμή, δεύτερη στήλη. |
| [getM31()](#getM31--) | Λαμβάνει το στοιχείο του πίνακα στην τρίτη γραμμή, πρώτη στήλη. |
| [getM32()](#getM32--) | Λαμβάνει το στοιχείο του πίνακα στην τρίτη γραμμή, πρώτη στήλη. |
| [hashCode()](#hashCode--) | Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | Καθορίζει εάν δύο πίνακες είναι ίσοι. |
| [isIdentity()](#isIdentity--) | Επιστρέφει `true` εάν αυτό το `AffineTransform` είναι ένας ταυτοτικός μετασχηματισμός. |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | Πολλαπλασιάζει αυτόν τον Matrix με τον πίνακα που καθορίζεται στην παράμετρο matrix χρησιμοποιώντας τη (προεπιλεγμένη) σειρά Prepend. |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | Πολλαπλασιάζει αυτόν τον Matrix με τον πίνακα που καθορίζεται στην παράμετρο matrix, και με τη σειρά που καθορίζεται στην παράμετρο order. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Επαναφέρει αυτόν τον Matrix ώστε να έχει τα στοιχεία του ταυτοτικού πίνακα. |
| [rotate(float angle)](#rotate-float-) | Εφαρμόζει μια δεξιόστροφη περιστροφή ποσού που καθορίζεται στην παράμετρο angle, γύρω από το αρχικό σημείο (μηδενικές συντεταγμένες x και y) για αυτόν τον Matrix στην προεπιλεγμένη (Prepend) σειρά. |
| [rotate(float angle, int order)](#rotate-float-int-) | Εφαρμόζει μια δεξιόστροφη περιστροφή ποσού που καθορίζεται στην παράμετρο angle, γύρω από το αρχικό σημείο (μηδενικές συντεταγμένες x και y) για αυτόν τον Matrix στην καθορισμένη σειρά. |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | Εφαρμόζει μια δεξιόστροφη περιστροφή γύρω από το καθορισμένο σημείο σε αυτόν τον Matrix στην προεπιλεγμένη (Prepend) σειρά. |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | Εφαρμόζει μια δεξιόστροφη περιστροφή γύρω από το καθορισμένο σημείο σε αυτόν τον Matrix στην καθορισμένη σειρά. |
| [scale(float sx, float sy)](#scale-float-float-) | Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας (scaleX και scaleY) σε αυτόν τον Matrix χρησιμοποιώντας τη (προεπιλεγμένη) σειρά Prepend. |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας (scaleX και scaleY) σε αυτόν τον Matrix χρησιμοποιώντας τη καθορισμένη σειρά. |
| [toString()](#toString--) | Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση. |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | Εφαρμόζει τον γεωμετρικό μετασχηματισμό που αντιπροσωπεύεται από αυτόν τον Matrix σε έναν καθορισμένο πίνακα σημείων. |
| [translate(float tx, float ty)](#translate-float-float-) | Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης σε αυτή τη Μήτρα χρησιμοποιώντας την (προεπιλεγμένη) σειρά Προσθήκης. |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης σε αυτή τη Μήτρα με τη καθορισμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Matrix ως τον μοναδιαίο πίνακα.

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Αρχικοποιεί ένα νέο αντικείμενο της  Matrix  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Δημιουργεί ένα αντίγραφο της  Matrix  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | η βασική μήτρα για την αντιμετώπιση |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


Αρχικοποιεί ένα νέο αντικείμενο της  Aspose.Imaging.Matrix  κλάσης στην γεωμετρική μεταστροφή που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μία δομή Aspose.Imaging.RectangleF που αντιπροσωπεύει το ορθογώνιο που θα μετασχηματιστεί. |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας τριών δομών Aspose.Imaging.PointF που αντιπροσωπεύει τα σημεία ενός παραλληλογράμμου στα οποία θα μετασχηματιστούν οι άνω αριστερές, άνω δεξιές και κάτω αριστερές γωνίες του ορθογωνίου. Η κάτω δεξιά γωνία του παραλληλογράμμου προκύπτει από τις πρώτες τρεις γωνίες. |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


Αρχικοποιεί ένα νέο αντικείμενο της  Aspose.Imaging.Matrix  κλάσης στην γεωμετρική μεταστροφή που ορίζεται από το καθορισμένο ορθογώνιο και τον πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μία δομή Aspose.Imaging.Rectangle που αντιπροσωπεύει το ορθογώνιο που θα μετασχηματιστεί. |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | Ένας πίνακας τριών δομών Aspose.Imaging.Point που αντιπροσωπεύει τα σημεία ενός παραλληλογράμμου στα οποία θα μετασχηματιστούν οι άνω αριστερές, άνω δεξιές και κάτω αριστερές γωνίες του ορθογωνίου. Η κάτω δεξιά γωνία του παραλληλογράμμου προκύπτει από τις πρώτες τρεις γωνίες. |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


Αυτό το δυαδικό σημείο σημαίας υποδεικνύει ότι η μετατροπή που ορίζεται από αυτό το αντικείμενο εκτελεί μια αναστροφή καθρέφτη γύρω από κάποιο άξονα, η οποία μετατρέπει το συνήθως δεξιόχειρο σύστημα συντεταγμένων σε αριστερόχειρο σύστημα, επιπλέον των μετατροπών που υποδεικνύονται από άλλα δυαδικά σημεία σημαίας. Ένα δεξιόχειρο σύστημα συντεταγμένων είναι αυτό όπου ο θετικός άξονας X περιστρέφεται αριστερόστροφα ώστε να επικαλύψει τον θετικό άξονα Y, παρόμοια με την κατεύθυνση που κυλούν τα δάχτυλα του δεξιού σας χεριού όταν κοιτάζετε την αντίχειρα. Ένα αριστερόχειρο σύστημα συντεταγμένων είναι αυτό όπου ο θετικός άξονας X περιστρέφεται δεξιόστροφα ώστε να επικαλύψει τον θετικό άξονα Y, παρόμοια με την κατεύθυνση που κυλούν τα δάχτυλα του αριστερού σας χεριού. Δεν υπάρχει μαθηματικός τρόπος να προσδιοριστεί η γωνία της αρχικής αναστροφής ή κατοπτρισμού, καθώς όλες οι γωνίες αναστροφής είναι ταυτόσες με μια κατάλληλη προσαρμοστική περιστροφή. ΣΗΜΕΙΩΣΗ: Το TypeFlip προστέθηκε μετά την κυκλοφορία του GENERAL_TRANSFORM και τα δυαδικά σημεία σημαίας δεν μπορούσαν πλέον να επανααριθμηθούν άνετα χωρίς να προκληθεί δυαδική ασυμβατότητα σε εξωτερικό κώδικα.

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


Αυτό το δυαδικό σημείο σημαίας υποδεικνύει ότι η μετατροπή που ορίζεται από αυτό το αντικείμενο εκτελεί μια περιστροφή κατά αυθαίρετη γωνία, επιπλέον των μετατροπών που υποδεικνύονται από άλλα δυαδικά σημεία σημαίας. Μια περιστροφή αλλάζει τις γωνίες των διανυσμάτων κατά το ίδιο ποσό ανεξάρτητα από την αρχική κατεύθυνση του διανύσματος και χωρίς να αλλάζει το μήκος του διανύσματος. Αυτό το δυαδικό σημείο σημαίας είναι αμοιβαία αποκλειστικό με το

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


Μια γενική κλίμακα πολλαπλασιάζει το μήκος των διανυσμάτων κατά διαφορετικά ποσά στις κατευθύνσεις x και y, χωρίς να αλλάζει τη γωνία μεταξύ κάθετων διανυσμάτων. Αυτό το δυαδικό σημείο σημαίας είναι αμοιβαία αποκλειστικό με τη σημαία TypeUniformScale.

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


Αυτή η σταθερά υποδεικνύει ότι η μετατροπή που ορίζεται από αυτό το αντικείμενο εκτελεί μια αυθαίρετη μετατροπή των συντεταγμένων εισόδου. Εάν αυτή η μετατροπή μπορεί να ταξινομηθεί από οποιαδήποτε από τις παραπάνω σταθερές, ο τύπος θα είναι είτε η σταθερά TypeIdentity είτε ένας συνδυασμός των κατάλληλων δυαδικών σημείων σημαίας για τις διάφορες μετατροπές συντεταγμένων που εκτελεί αυτή η μετατροπή.

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


Μια ταυτοτική μετατροπή είναι αυτή στην οποία οι συντεταγμένες εξόδου είναι πάντα ίδιες με τις συντεταγμένες εισόδου. Εάν αυτή η μετατροπή είναι κάτι διαφορετικό από την ταυτοτική μετατροπή, ο τύπος θα είναι είτε η σταθερά GENERAL_TRANSFORM είτε ένας συνδυασμός των κατάλληλων δυαδικών σημείων σημαίας για τις διάφορες μετατροπές συντεταγμένων που εκτελεί αυτή η μετατροπή.

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


Αυτή η σταθερά είναι μια μάσκα bit για οποιοδήποτε από τα bits σημαίας περιστροφής.

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


Αυτή η σταθερά είναι μια μάσκα bit για οποιοδήποτε από τα bits σημαίας κλιμάκωσης.

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


Αυτό το δυαδικό σημείο σημαίας υποδεικνύει ότι η μετατροπή που ορίζεται από αυτό το αντικείμενο εκτελεί μια περιστροφή τεταρτημορίου κατά κάποιο πολλαπλάσιο των 90 μοιρών, επιπλέον των μετατροπών που υποδεικνύονται από άλλα δυαδικά σημεία σημαίας. Μια περιστροφή αλλάζει τις γωνίες των διανυσμάτων κατά το ίδιο ποσό ανεξάρτητα από την αρχική κατεύθυνση του διανύσματος και χωρίς να αλλάζει το μήκος του διανύσματος. Αυτό το δυαδικό σημείο σημαίας είναι αμοιβαία αποκλειστικό με τη σημαία TypeGeneralRotation.

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


Μια μετάθεση μετακινεί τις συντεταγμένες κατά μια σταθερή τιμή στο x και y χωρίς να αλλάζει το μήκος ή τη γωνία των διανυσμάτων.

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


Μια ομοιόμορφη κλίμακα πολλαπλασιάζει το μήκος των διανυσμάτων κατά το ίδιο ποσό και στις διευθύνσεις x και y χωρίς να αλλάζει τη γωνία μεταξύ των διανυσμάτων. Αυτό το bit σημαίας είναι αμοιβαία αποκλειστικό με τη σημαία TypeGeneralScale.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν το καθορισμένο  System.Object  είναι ίσο με αυτήν την παρουσία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το  System.Object  για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  true  εάν το καθορισμένο  System.Object  είναι ίσο με αυτήν την παρουσία· διαφορετικά,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


Λαμβάνει το αντίγραφο των στοιχείων του πίνακα.

**Returns:**
float[] - Αντιγραφή στοιχείων πίνακα.
### getM11() {#getM11--}
```
public float getM11()
```


Λαμβάνει το στοιχείο του πίνακα στην πρώτη γραμμή, πρώτη στήλη. Αντιπροσωπεύει κλίμακα κατά τον άξονα X.

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


Λαμβάνει το στοιχείο του πίνακα στην πρώτη γραμμή, δεύτερη στήλη. Αντιπροσωπεύει διαστρέβλωση κατά τον άξονα Y.

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


Λαμβάνει το στοιχείο του πίνακα στη δεύτερη γραμμή, πρώτη στήλη. Αντιπροσωπεύει διαστρέβλωση κατά τον άξονα X.

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


Λαμβάνει το στοιχείο του πίνακα στη δεύτερη γραμμή, δεύτερη στήλη. Αντιπροσωπεύει κλίμακα κατά τον άξονα Y.

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


Λαμβάνει το στοιχείο του πίνακα στην τρίτη γραμμή, πρώτη στήλη. Αντιπροσωπεύει μετάθεση κατά τον άξονα X.

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


Λαμβάνει το στοιχείο του πίνακα στην τρίτη γραμμή, πρώτη στήλη. Αντιπροσωπεύει μετάθεση κατά τον άξονα Y.

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει έναν κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας κωδικός κατακερματισμού για αυτήν την παρουσία, κατάλληλος για χρήση σε αλγορίθμους κατακερματισμού και δομές δεδομένων όπως ένας πίνακας κατακερματισμού.
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


Καθορίζει εάν δύο πίνακες είναι ίσοι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | Ο πρώτος πίνακας για σύγκριση. |
| b | [Matrix](../../com.aspose.psd/matrix) | Ο δεύτερος πίνακας για σύγκριση. |

**Returns:**
boolean - Αληθές εάν οι πίνακες είναι ίσοι.
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


Επιστρέφει `true` εάν αυτό το `AffineTransform` είναι ένας ταυτοτικός μετασχηματισμός.

**Returns:**
boolean - `true` εάν αυτό το `AffineTransform` είναι μετασχηματισμός ταυτότητας· `false` διαφορετικά.
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


Πολλαπλασιάζει αυτόν τον Matrix με τον πίνακα που καθορίζεται στην παράμετρο matrix χρησιμοποιώντας τη (προεπιλεγμένη) σειρά Prepend.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Ο πίνακας με τον οποίο θα γίνει πολλαπλασιασμός. |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


Πολλαπλασιάζει αυτόν τον Matrix με τον πίνακα που καθορίζεται στην παράμετρο matrix, και με τη σειρά που καθορίζεται στην παράμετρο order.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | Το tx. Το tx. Το tx. |
| order | int | Η σειρά. Η σειρά. Η σειρά. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


Επαναφέρει αυτόν τον Matrix ώστε να έχει τα στοιχεία του ταυτοτικού πίνακα.

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή ποσού που καθορίζεται στην παράμετρο angle, γύρω από το αρχικό σημείο (μηδενικές συντεταγμένες x και y) για αυτόν τον Matrix στην προεπιλεγμένη (Prepend) σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή ποσού που καθορίζεται στην παράμετρο angle, γύρω από το αρχικό σημείο (μηδενικές συντεταγμένες x και y) για αυτόν τον Matrix στην καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |
| order | int | Η σειρά του πίνακα. |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή γύρω από το καθορισμένο σημείο σε αυτόν τον Matrix στην προεπιλεγμένη (Prepend) σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία. |
| point | [PointF](../../com.aspose.psd/pointf) | Το σημείο. |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


Εφαρμόζει μια δεξιόστροφη περιστροφή γύρω από το καθορισμένο σημείο σε αυτόν τον Matrix στην καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία. |
| point | [PointF](../../com.aspose.psd/pointf) | Το σημείο. |
| order | int | Η σειρά. |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας (scaleX και scaleY) σε αυτόν τον Matrix χρησιμοποιώντας τη (προεπιλεγμένη) σειρά Prepend.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το sx. Το sx. Το sx. |
| sy | float | Το sy. Το sy. Το sy. |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


Εφαρμόζει το καθορισμένο διάνυσμα κλίμακας (scaleX και scaleY) σε αυτόν τον Matrix χρησιμοποιώντας τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| scaleX | float | Η κλίμακα X. |
| scaleY | float | Η κλίμακα Y. |
| order | int | Η σειρά. |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.

**Returns:**
java.lang.String - Ένα  System.String  που αντιπροσωπεύει αυτήν την περίπτωση.
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


Εφαρμόζει τον γεωμετρικό μετασχηματισμό που αντιπροσωπεύεται από αυτόν τον Matrix σε έναν καθορισμένο πίνακα σημείων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Τα σημεία. |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης σε αυτή τη Μήτρα χρησιμοποιώντας την (προεπιλεγμένη) σειρά Προσθήκης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tx | float | Το tx. Το tx. Το tx. |
| ty | float | Το ty. Το ty. Το ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


Εφαρμόζει το καθορισμένο διάνυσμα μετάφρασης σε αυτή τη Μήτρα με τη καθορισμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| offsetX | float | Η offset X. |
| offsetY | float | Η offset Y. |
| order | int | Η σειρά. |

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

