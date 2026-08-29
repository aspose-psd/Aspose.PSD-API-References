---
title: "LinearGradientBrush"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιλαμβάνει ένα Aspose.Imaging.Brush με γραμμική διαβάθμιση."
type: docs
weight: 11
url: /el/java/com.aspose.psd.brushes/lineargradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.LinearGradientBrushBase](../../com.aspose.psd.brushes/lineargradientbrushbase)
```
public final class LinearGradientBrush extends LinearGradientBrushBase
```

Περιλαμβάνει ένα  Aspose.Imaging.Brush  με γραμμική διαβάθμιση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [LinearGradientBrush()](#LinearGradientBrush--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  με προεπιλεγμένες παραμέτρους. |
| [LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)](#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  με τα καθορισμένα σημεία και χρώματα. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
| [LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
| [LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)](#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Λαμβάνει τη γωνία κλίσης. |
| [getBlend()](#getBlend--) | Λαμβάνει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getEndColor()](#getEndColor--) | Λαμβάνει το τελικό χρώμα της διαβάθμισης. |
| [getGammaCorrection()](#getGammaCorrection--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η διόρθωση γάμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase. |
| [getInterpolationColors()](#getInterpolationColors--) | Λαμβάνει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση. |
| [getLinearColors()](#getLinearColors--) | Λαμβάνει τα αρχικά και τελικά χρώματα της διαβάθμισης. |
| [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια του πινέλου. |
| [getRectangle()](#getRectangle--) | Λαμβάνει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της κλίσης. |
| [getStartColor()](#getStartColor--) | Λαμβάνει το αρχικό χρώμα της διαβάθμισης. |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Ορίζει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς ένα ενιαίο χρώμα και στις δύο άκρες. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς ένα ενιαίο χρώμα και στις δύο άκρες. |
| [setEndColor(Color value)](#setEndColor-com.aspose.psd.Color-) | Ορίζει το τελικό χρώμα της διαβάθμισης. |
| [setGammaCorrection(boolean value)](#setGammaCorrection-boolean-) | Ορίζει μια τιμή που υποδεικνύει εάν η διόρθωση γάμα είναι ενεργοποιημένη για αυτό το LinearGradientBrushBase. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Ορίζει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση. |
| [setLinearColors(Color[] value)](#setLinearColors-com.aspose.psd.Color---) | Ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης. |
| [setOpacity(float value)](#setOpacity-float-) | Ορίζει τη διαφάνεια του πινέλου. |
| [setRectangle(RectangleF value)](#setRectangle-com.aspose.psd.RectangleF-) | Ορίζει μια ορθογώνια περιοχή που ορίζει τα αρχικά και τελικά σημεία της κλίσης. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Δημιουργεί ελάττωση διαβάθμισης βασισμένη σε καμπύλη σχήματος καμπάνας. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Δημιουργεί ελάττωση διαβάθμισης βασισμένη σε καμπύλη σχήματος καμπάνας. |
| [setStartColor(Color value)](#setStartColor-com.aspose.psd.Color-) | Ορίζει το αρχικό χρώμα της διαβάθμισης. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης LinearGradientBrush με προεπιλεγμένες παραμέτρους. Το αρχικό χρώμα είναι μαύρο, το τελικό χρώμα είναι λευκό, η γωνία είναι 45 μοίρες και το ορθογώνιο βρίσκεται στο (0,0) με μέγεθος (1,1).

### LinearGradientBrush(Point point1, Point point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  με τα καθορισμένα σημεία και χρώματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Μια δομή Aspose.Imaging.Point που αντιπροσωπεύει το αρχικό σημείο της γραμμικής διαβάθμισης. |
| point2 | [Point](../../com.aspose.psd/point) | Μια δομή Aspose.Imaging.Point που αντιπροσωπεύει το τελικό σημείο της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το αρχικό χρώμα του γραμμικού gradient. |
| color2 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το τελικό χρώμα του γραμμικού gradient. |

### LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2) {#LinearGradientBrush-com.aspose.psd.PointF-com.aspose.psd.PointF-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  με τα καθορισμένα σημεία και χρώματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Μια δομή Aspose.Imaging.PointF που αντιπροσωπεύει το αρχικό σημείο της γραμμικής διαβάθμισης. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Μια δομή Aspose.Imaging.PointF που αντιπροσωπεύει το τελικό σημείο της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το αρχικό χρώμα του γραμμικού gradient. |
| color2 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το τελικό χρώμα του γραμμικού gradient. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το αρχικό χρώμα για το gradient. |
| color2 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το τελικό χρώμα για το gradient. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το αρχικό χρώμα για το gradient. |
| color2 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το τελικό χρώμα για το gradient. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |

### LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.Rectangle-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το αρχικό χρώμα για το gradient. |
| color2 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το τελικό χρώμα για το gradient. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |
| isAngleScalable | boolean | εάν οριστεί σε true, η γωνία αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrush. |

### LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable) {#LinearGradientBrush-com.aspose.psd.RectangleF-com.aspose.psd.Color-com.aspose.psd.Color-float-boolean-}
```
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, boolean isAngleScalable)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  LinearGradientBrush  βασισμένη σε ένα ορθογώνιο, αρχικά και τελικά χρώματα, και γωνία προσανατολισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή Aspose.Imaging.RectangleF που καθορίζει τα όρια της γραμμικής διαβάθμισης. |
| color1 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το αρχικό χρώμα για το gradient. |
| color2 | [Color](../../com.aspose.psd/color) | Μια δομή com.aspose.psd.Color που αντιπροσωπεύει το τελικό χρώμα για το gradient. |
| angle | float | Η γωνία, μετρημένη σε μοίρες δεξιόστροφα από τον άξονα x, της γραμμής προσανατολισμού της διαβάθμισης. |
| isAngleScalable | boolean | εάν οριστεί σε true, η γωνία αλλάζει κατά τις μετασχηματισμούς με αυτό το LinearGradientBrush. |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Λαμβάνει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
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
### getEndColor() {#getEndColor--}
```
public Color getEndColor()
```


Λαμβάνει το τελικό χρώμα της διαβάθμισης.

**Returns:**
[Color](../../com.aspose.psd/color) - The ending gradient color.
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
### getLinearColors() {#getLinearColors--}
```
public Color[] getLinearColors()
```


Λαμβάνει τα αρχικά και τελικά χρώματα της διαβάθμισης.

**Returns:**
com.aspose.psd.Color[] - Ένας πίνακας από δύο δομές Color που αντιπροσωπεύει τα αρχικά και τελικά χρώματα του gradient.
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
### getStartColor() {#getStartColor--}
```
public Color getStartColor()
```


Λαμβάνει το αρχικό χρώμα της διαβάθμισης.

**Returns:**
[Color](../../com.aspose.psd/color) - The starting gradient color.
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

### setBlend(Blend value) {#setBlend-com.aspose.psd.Blend-}
```
public void setBlend(Blend value)
```


Ορίζει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Blend](../../com.aspose.psd/blend) | Μια Aspose.Imaging.Blend που αντιπροσωπεύει μια προσαρμοσμένη πτώση για το gradient. |

### setBlendTriangularShape(float focus) {#setBlendTriangularShape-float-}
```
public void setBlendTriangularShape(float focus)
```


Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς ένα ενιαίο χρώμα και στις δύο άκρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο του gradient (το σημείο όπου το gradient αποτελείται μόνο από το τελικό χρώμα). |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Δημιουργεί μια γραμμική διαβάθμιση με κεντρικό χρώμα και γραμμική ελάττωση προς ένα ενιαίο χρώμα και στις δύο άκρες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο του gradient (το σημείο όπου το gradient αποτελείται μόνο από το τελικό χρώμα). |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο γρήγορα τα χρώματα μειώνονται από το αρχικό χρώμα προς την εστίαση (τελικό χρώμα). |

### setEndColor(Color value) {#setEndColor-com.aspose.psd.Color-}
```
public void setEndColor(Color value)
```


Ορίζει το τελικό χρώμα της διαβάθμισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Το τελικό χρώμα του gradient. |

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

### setLinearColors(Color[] value) {#setLinearColors-com.aspose.psd.Color---}
```
public void setLinearColors(Color[] value)
```


Ορίζει τα αρχικά και τελικά χρώματα της διαβάθμισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Ένας πίνακας από δύο δομές Color που αντιπροσωπεύει τα αρχικά και τελικά χρώματα του gradient. |

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

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Δημιουργεί ελάττωση διαβάθμισης βασισμένη σε καμπύλη σχήματος καμπάνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο του gradient (το σημείο όπου το αρχικό και το τελικό χρώμα αναμειγνύονται εξίσου). |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Δημιουργεί ελάττωση διαβάθμισης βασισμένη σε καμπύλη σχήματος καμπάνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει το κέντρο του gradient (το σημείο όπου το gradient αποτελείται μόνο από το τελικό χρώμα). |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο γρήγορα τα χρώματα μειώνονται από την εστίαση. |

### setStartColor(Color value) {#setStartColor-com.aspose.psd.Color-}
```
public void setStartColor(Color value)
```


Ορίζει το αρχικό χρώμα της διαβάθμισης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Το αρχικό χρώμα του gradient. |

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

