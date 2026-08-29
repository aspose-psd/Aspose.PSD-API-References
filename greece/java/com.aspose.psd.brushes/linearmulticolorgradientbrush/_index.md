---
title: "LinearMulticolorGradientBrush"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αντιπροσωπεύει ένα Brush με γραμμική διαβάθμιση που ορίζεται από πολλαπλά χρώματα και κατάλληλες θέσεις."
type: docs
weight: 13
url: /el/java/com.aspose.psd.brushes/linearmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearMulticolorGradientBrush extends LinearGradientBrushBase
```

Αντιπροσωπεύει ένα Brush με γραμμική διαβάθμιση που ορίζεται από πολλαπλά χρώματα και κατάλληλες θέσεις. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LinearMulticolorGradientBrush()](#LinearMulticolorGradientBrush--) | Αρχικοποιεί μια νέα παρουσία της κλάσης LinearMulticolorGradientBrush με προεπιλεγμένες παραμέτρους. |
| [LinearMulticolorGradientBrush(Point point1, Point point2)](#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush με τα καθορισμένα σημεία. |
| [LinearMulticolorGradientBrush(PointF point1, PointF point2)](#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush με τα καθορισμένα σημεία. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
| [LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
| [LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)](#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Λαμβάνει τη γωνία κλίσης. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getGammaCorrection()](#getGammaCorrection--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η διόρθωση γάμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Λαμβάνει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση. |
| [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια του πινέλου. |
| [getRectangle()](#getRectangle--) | Λαμβάνει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της κλίσης. |
| [getTransform()](#getTransform--) | Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush. |
| [hashCode()](#hashCode--) |  |
| [isAngleScalable()](#isAngleScalable--) | Λαμβάνει μια τιμή που υποδεικνύει εάν το LinearGradientBrushBase.Angle αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrushBase. |
| [isTransformChanged()](#isTransformChanged--) | Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί έχουν αλλάξει με κάποιο τρόπο. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Πολλαπλασιάζει το Aspose.Imaging.Matrix που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του LinearGradientBrush με το καθορισμένο Aspose.Imaging.Matrix, προσθέτοντας το καθορισμένο Aspose.Imaging.Matrix στην αρχή. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Πολλαπλασιάζει το Aspose.Imaging.Matrix που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του LinearGradientBrush με το καθορισμένο Aspose.Imaging.Matrix με τη συγκεκριμένη σειρά. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Επαναφέρει την ιδιότητα TransformBrush.Transform στην ταυτότητα. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με τη συγκεκριμένη σειρά. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με τη συγκεκριμένη σειρά. |
| [setAngle(float value)](#setAngle-float-) | Ορίζει τη γωνία κλίσης. |
| [setAngleScalable(boolean value)](#setAngleScalable-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν το LinearGradientBrushBase.Angle αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrushBase. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η διόρθωση γάμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Ορίζει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση. |
| [setOpacity(float value)](#setOpacity-float-) | Ορίζει τη διαφάνεια του πινέλου. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Ορίζει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της κλίσης. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearMulticolorGradientBrush() {#LinearMulticolorGradientBrush--}
```
public LinearMulticolorGradientBrush()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush με προεπιλεγμένες παραμέτρους. Το αρχικό χρώμα είναι μαύρο, το τελικό χρώμα είναι λευκό, η γωνία είναι 45 μοίρες και το ορθογώνιο βρίσκεται στο (0,0) με μέγεθος (1,1).

### LinearMulticolorGradientBrush(Point point1, Point point2) {#LinearMulticolorGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public LinearMulticolorGradientBrush(Point point1, Point point2)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Μια δομή Aspose.Imaging.Point που αντιπροσωπεύει το αρχικό σημείο της γραμμικής διαβάθμισης. |
| point2 | [Point](../../com.aspose.psd/point) | Μια δομή Aspose.Imaging.Point που αντιπροσωπεύει το τελικό σημείο της γραμμικής διαβάθμισης. |

### LinearMulticolorGradientBrush(PointF point1, PointF point2) {#LinearMulticolorGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public LinearMulticolorGradientBrush(PointF point1, PointF point2)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Μια δομή Aspose.Imaging.PointF που αντιπροσωπεύει το αρχικό σημείο της γραμμικής διαβάθμισης. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Μια δομή Aspose.Imaging.PointF που αντιπροσωπεύει το τελικό σημείο της γραμμικής διαβάθμισης. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |

### LinearMulticolorGradientBrush(RectangleF rect, float angle) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |

### LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.Rectangle-float-boolean-}
```
public LinearMulticolorGradientBrush(Rectangle rect, float angle, boolean isAngleScalable)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |
| isAngleScalable | boolean | εάν οριστεί σε true η γωνία αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearMulticolorGradientBrush . |

### LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable) {#LinearMulticolorGradientBrush-com.aspose.psd.RectangleF-float-boolean-}
```
public LinearMulticolorGradientBrush(RectangleF rect, float angle, boolean isAngleScalable)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης LinearMulticolorGradientBrush βασισμένο σε ένα ορθογώνιο και μια γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |
| isAngleScalable | boolean | εάν οριστεί σε true η γωνία αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearMulticolorGradientBrush . |

### close() {#close--}
```
public void close()
```


Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. Αυτή η μέθοδος απλώς καλεί τη μέθοδο dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
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
### getAngle() {#getAngle--}
```
public float getAngle()
```


Λαμβάνει τη γωνία κλίσης.

**Returns:**
float - Η γωνία της διαβάθμισης.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί.

**Returns:**
boolean -  true  εάν διαγραφεί· διαφορετικά,  false .
### getGammaCorrection() {#getGammaCorrection--}
```
public boolean getGammaCorrection()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η διόρθωση γάμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase.

**Returns:**
boolean - Η τιμή είναι true εάν η διόρθωση γάμμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase ; διαφορετικά, false.
### getInterpolationColors() {#getInterpolationColors--}
```
public ColorBlend getInterpolationColors()
```


Λαμβάνει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend) - A  com.aspose.psd.ColorBlend  that defines a multicolor linear gradient.
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Λαμβάνει τη διαφάνεια του πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές.

**Returns:**
float - Η τιμή διαφάνειας του πινέλου.
### getRectangle() {#getRectangle--}
```
public RectangleF getRectangle()
```


Λαμβάνει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της κλίσης.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A  com.aspose.psd.RectangleF  structure that specifies the starting and ending points of the gradient.
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush.

**Returns:**
int - Ένα Aspose.Imaging.WrapMode που καθορίζει πώς γεμίσματα σχεδιασμένα με αυτό το TransformBrush επαναλαμβάνονται.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAngleScalable() {#isAngleScalable--}
```
public boolean isAngleScalable()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν το LinearGradientBrushBase.Angle αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrushBase.

**Returns:**
boolean - true εάν το LinearGradientBrushBase.Angle αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrushBase ; διαφορετικά, false .
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν οι μετασχηματισμοί έχουν αλλάξει με κάποιο τρόπο. Για παράδειγμα, ορίζοντας τον πίνακα μετασχηματισμού ή καλώντας οποιαδήποτε από τις μεθόδους που τροποποιούν τον πίνακα μετασχηματισμού. Η ιδιότητα εισάγεται για συμβατότητα με παλαιότερες εκδόσεις του GDI+.

Τιμή: True εάν ο μετασχηματισμός άλλαξε· διαφορετικά, false .

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Πολλαπλασιάζει το Aspose.Imaging.Matrix που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του LinearGradientBrush με το καθορισμένο Aspose.Imaging.Matrix, προσθέτοντας το καθορισμένο Aspose.Imaging.Matrix στην αρχή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η Aspose.Imaging.Matrix με την οποία θα πολλαπλασιαστεί ο γεωμετρικός μετασχηματισμός. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Πολλαπλασιάζει το Aspose.Imaging.Matrix που αντιπροσωπεύει τον τοπικό γεωμετρικό μετασχηματισμό αυτού του LinearGradientBrush με το καθορισμένο Aspose.Imaging.Matrix με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η Aspose.Imaging.Matrix με την οποία θα πολλαπλασιαστεί ο γεωμετρικός μετασχηματισμός. |
| order | int | Ένα Aspose.Imaging.MatrixOrder που καθορίζει με ποια σειρά θα πολλαπλασιαστούν οι δύο πίνακες. |

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


Επαναφέρει την ιδιότητα TransformBrush.Transform στην ταυτότητα.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Περιστρέφει τη τοπική γεωμετρική μετατροπή κατά το καθορισμένο ποσό. Αυτή η μέθοδος προσθέτει την περιστροφή στην αρχή του μετασχηματισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Περιστρέφει τον τοπικό γεωμετρικό μετασχηματισμό κατά το καθορισμένο ποσό με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| angle | float | Η γωνία περιστροφής. |
| order | int | Ένα Aspose.Imaging.MatrixOrder που καθορίζει εάν θα προσαρτηθεί ή θα προστεθεί στην αρχή ο πίνακας περιστροφής. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Κλιμακώνει τη τοπική γεωμετρική μετατροπή με τα καθορισμένα ποσά. Αυτή η μέθοδος προσθέτει στην αρχή τον πίνακα κλιμάκωσης στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Κλιμακώνει τον τοπικό γεωμετρικό μετασχηματισμό κατά τα καθορισμένα ποσά με τη συγκεκριμένη σειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sx | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα x. |
| sy | float | Το ποσό κατά το οποίο κλιμακώνεται ο μετασχηματισμός στην κατεύθυνση του άξονα y. |
| order | int | Ένα  Aspose.Imaging.MatrixOrder  που καθορίζει εάν θα προσαρτηθεί ή θα προταθεί (προσθέσει στην αρχή) ο πίνακας κλιμάκωσης. |

### setAngle(float value) {#setAngle-float-}
```
public void setAngle(float value)
```


Ορίζει τη γωνία κλίσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η γωνία του διαβάθμισης. |

### setAngleScalable(boolean value) {#setAngleScalable-boolean-}
```
public void setAngleScalable(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν το LinearGradientBrushBase.Angle αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrushBase.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | αληθές εάν το LinearGradientBrushBase.Angle αλλάξει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrushBase· διαφορετικά, ψευδές. |

### setGammaCorrection(boolean value) {#setGammaCorrection-boolean-}
```
public void setGammaCorrection(boolean value)
```


Ορίζει μια τιμή που υποδεικνύει εάν η διόρθωση γάμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Η τιμή είναι αληθής εάν η διόρθωση γάμμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase· διαφορετικά, ψευδής. |

### setInterpolationColors(ColorBlend value) {#setInterpolationColors-com.aspose.psd.ColorBlend-}
```
public void setInterpolationColors(ColorBlend value)
```


Ορίζει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) | Ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολυχρωματική γραμμική διαβάθμιση. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ορίζει τη διαφάνεια της πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η τιμή διαφάνειας του πινέλου. |

### setRectangle(RectangleF value) {#setRectangle-com.aspose.psd.RectangleF-}
```
public void setRectangle(RectangleF value)
```


Ορίζει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της κλίσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή  com.aspose.psd.RectangleF  που καθορίζει τα αρχικά και τελικά σημεία της διαβάθμισης. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

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


Μεταφράζει τη τοπική γεωμετρική μετατροπή με τις καθορισμένες διαστάσεις. Αυτή η μέθοδος προσθέτει στην αρχή τη μετάφραση στον μετασχηματισμό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Η τιμή της μετάφρασης στον άξονα x. |
| dy | float | Η τιμή της μετάφρασης στον άξονα y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά.

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

