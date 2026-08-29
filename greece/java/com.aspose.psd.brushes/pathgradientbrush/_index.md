---
title: "PathGradientBrush"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιλαμβάνει ένα αντικείμενο Aspose.Imaging.Brush με μια κλίση."
type: docs
weight: 14
url: /el/java/com.aspose.psd.brushes/pathgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathGradientBrush extends PathGradientBrushBase
```

Περιλαμβάνει ένα  Aspose.Imaging.Brush  αντικείμενο με μια κλίση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.

Το κεντρικό χρώμα είναι λευκό από προεπιλογή. Ένας χρήστης μπορεί να αλλάξει αυτή την τιμή ανά πάσα στιγμή.

Ο πίνακας περιμετρικών χρωμάτων αρχικοποιείται με ένα μόνο στοιχείο που περιέχει λευκό χρώμα από προεπιλογή. Τα περιμετρικά χρώματα μπορούν να αλλάξουν αργότερα, ωστόσο απαιτείται τουλάχιστον ένα στοιχείο όταν ορίζονται τα περιμετρικά χρώματα.

Δείτε το Blend για περισσότερες λεπτομέρειες σχετικά με την αρχικοποίησή του.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PathGradientBrush(PointF[] points)](#PathGradientBrush-com.aspose.psd.PointF---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία. |
| [PathGradientBrush(PointF[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.PointF---int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathGradientBrush(Point[] points)](#PathGradientBrush-com.aspose.psd.Point---) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία. |
| [PathGradientBrush(Point[] points, int wrapMode)](#PathGradientBrush-com.aspose.psd.Point---int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathGradientBrush(GraphicsPath path)](#PathGradientBrush-com.aspose.psd.GraphicsPath-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  PathGradientBrush  με το καθορισμένο μονοπάτι. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlend()](#getBlend--) | Λαμβάνει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση. |
| [getCenterColor()](#getCenterColor--) | Λαμβάνει το χρώμα στο κέντρο της διαβάθμισης διαδρομής. |
| [getCenterPoint()](#getCenterPoint--) | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFocusScales()](#getFocusScales--) | Λαμβάνει το σημείο εστίασης για την εξασθένιση της διαβάθμισης. |
| [getGraphicsPath()](#getGraphicsPath--) | Λαμβάνει τη διαδρομή γραφικών πάνω στην οποία δημιουργήθηκε αυτό το πινέλο. |
| [getInterpolationColors()](#getInterpolationColors--) | Λαμβάνει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση. |
| [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια του πινέλου. |
| [getPathPoints()](#getPathPoints--) | Λαμβάνει τα σημεία διαδρομής πάνω στα οποία δημιουργήθηκε αυτό το πινέλο. |
| [getSurroundColors()](#getSurroundColors--) | Λαμβάνει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το  PathGradientBrush . |
| [getTransform()](#getTransform--) | Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush. |
| [hashCode()](#hashCode--) |  |
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
| [setBlend(Blend value)](#setBlend-com.aspose.psd.Blend-) | Ορίζει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση. |
| [setBlendTriangularShape(float focus)](#setBlendTriangularShape-float-) | Δημιουργεί μια διαβάθμιση με χρώμα στο κέντρο και γραμμική ελάττωση προς ένα περιβάλλον χρώμα. |
| [setBlendTriangularShape(float focus, float scale)](#setBlendTriangularShape-float-float-) | Δημιουργεί μια διαβάθμιση με χρώμα στο κέντρο και γραμμική ελάττωση προς κάθε περιβάλλον χρώμα. |
| [setCenterColor(Color value)](#setCenterColor-com.aspose.psd.Color-) | Ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής. |
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Λαμβάνει ή ορίζει το σημείο εστίασης για την εξασθένιση κλίσης. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Ορίζει ένα com.aspose.psd.ColorBlend που ορίζει μια πολυχρωματική γραμμική κλίση. |
| [setOpacity(float value)](#setOpacity-float-) | Ορίζει τη διαφάνεια του πινέλου. |
| [setSigmaBellShape(float focus)](#setSigmaBellShape-float-) | Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. |
| [setSigmaBellShape(float focus, float scale)](#setSigmaBellShape-float-float-) | Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. |
| [setSurroundColors(Color[] value)](#setSurroundColors-com.aspose.psd.Color---) | Ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το  PathGradientBrush . |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathGradientBrush(PointF[] points) {#PathGradientBrush-com.aspose.psd.PointF---}
```
public PathGradientBrush(PointF[] points)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  Aspose.Imaging.PointF  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### PathGradientBrush(PointF[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.PointF---int-}
```
public PathGradientBrush(PointF[] points, int wrapMode)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  Aspose.Imaging.PointF  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrapMode | int | Ένα  Aspose.Imaging.WrapMode  που καθορίζει πώς τα γέμισματα που σχεδιάζονται με αυτό το  PathGradientBrush  τοποθετούνται σε πλακίδια. |

### PathGradientBrush(Point[] points) {#PathGradientBrush-com.aspose.psd.Point---}
```
public PathGradientBrush(Point[] points)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Ένας πίνακας δομών  Aspose.Imaging.Point  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### PathGradientBrush(Point[] points, int wrapMode) {#PathGradientBrush-com.aspose.psd.Point---int-}
```
public PathGradientBrush(Point[] points, int wrapMode)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PathGradientBrush με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Ένας πίνακας δομών  Aspose.Imaging.Point  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrapMode | int | Ένα  Aspose.Imaging.WrapMode  που καθορίζει πώς τα γέμισματα που σχεδιάζονται με αυτό το  PathGradientBrush  τοποθετούνται σε πλακίδια. |

### PathGradientBrush(GraphicsPath path) {#PathGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathGradientBrush(GraphicsPath path)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  PathGradientBrush  με το καθορισμένο μονοπάτι.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το  GraphicsPath  που ορίζει την περιοχή που γεμίζει αυτό το  PathGradientBrush . |

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
### getBlend() {#getBlend--}
```
public Blend getBlend()
```


Λαμβάνει ένα  Aspose.Imaging.Blend  που καθορίζει θέσεις και παράγοντες που ορίζουν προσαρμοσμένη ελάττωση για τη διαβάθμιση.

**Returns:**
[Blend](../../com.aspose.psd/blend) - A  Aspose.Imaging.Blend  that represents a custom falloff for the gradient.
### getCenterColor() {#getCenterColor--}
```
public Color getCenterColor()
```


Λαμβάνει το χρώμα στο κέντρο της διαβάθμισης διαδρομής.

**Returns:**
[Color](../../com.aspose.psd/color) - A  com.aspose.psd.Color  that represents the color at the center of the path gradient.
### getCenterPoint() {#getCenterPoint--}
```
public PointF getCenterPoint()
```


Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the center point of the path gradient.
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
### getFocusScales() {#getFocusScales--}
```
public PointF getFocusScales()
```


Λαμβάνει το σημείο εστίασης για την εξασθένιση της διαβάθμισης.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  Aspose.Imaging.PointF  that represents the focus point for the gradient falloff.
### getGraphicsPath() {#getGraphicsPath--}
```
public GraphicsPath getGraphicsPath()
```


Λαμβάνει τη διαδρομή γραφικών πάνω στην οποία δημιουργήθηκε αυτό το πινέλο.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The graphics path.
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
### getPathPoints() {#getPathPoints--}
```
public PointF[] getPathPoints()
```


Λαμβάνει τα σημεία διαδρομής πάνω στα οποία δημιουργήθηκε αυτό το πινέλο.

**Returns:**
com.aspose.psd.PointF[] - Τα σημεία διαδρομής.
### getSurroundColors() {#getSurroundColors--}
```
public Color[] getSurroundColors()
```


Λαμβάνει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το  PathGradientBrush .

**Returns:**
com.aspose.psd.Color[] - Ένας πίνακας δομών  com.aspose.psd.Color  που αντιπροσωπεύει τα χρώματα που σχετίζονται με κάθε σημείο της διαδρομής που γεμίζει αυτό το  PathGradientBrush .
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


Δημιουργεί μια διαβάθμιση με χρώμα στο κέντρο και γραμμική ελάττωση προς ένα περιβάλλον χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής γραμμής από το κέντρο της διαδρομής μέχρι το όριο της διαδρομής, το κεντρικό χρώμα θα είναι στη μέγιστη έντασή του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |

### setBlendTriangularShape(float focus, float scale) {#setBlendTriangularShape-float-float-}
```
public void setBlendTriangularShape(float focus, float scale)
```


Δημιουργεί μια διαβάθμιση με χρώμα στο κέντρο και γραμμική ελάττωση προς κάθε περιβάλλον χρώμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής γραμμής από το κέντρο της διαδρομής μέχρι το όριο της διαδρομής, το κεντρικό χρώμα θα είναι στη μέγιστη έντασή του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει τη μέγιστη ένταση του κεντρικού χρώματος που αναμειγνύεται με το χρώμα του ορίου. Μια τιμή 1 προκαλεί τη μέγιστη δυνατή ένταση του κεντρικού χρώματος και είναι η προεπιλεγμένη τιμή. |

### setCenterColor(Color value) {#setCenterColor-com.aspose.psd.Color-}
```
public void setCenterColor(Color value)
```


Ορίζει το χρώμα στο κέντρο της διαβάθμισης διαδρομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Ένα  com.aspose.psd.Color  που αντιπροσωπεύει το χρώμα στο κέντρο της διαβάθμισης διαδρομής. |

### setCenterPoint(PointF value) {#setCenterPoint-com.aspose.psd.PointF-}
```
public void setCenterPoint(PointF value)
```


Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Ένα  Aspose.Imaging.PointF  που αντιπροσωπεύει το κεντρικό σημείο της κλίσης διαδρομής. |

### setFocusScales(PointF value) {#setFocusScales-com.aspose.psd.PointF-}
```
public void setFocusScales(PointF value)
```


Λαμβάνει ή ορίζει το σημείο εστίασης για την εξασθένιση κλίσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) | Ένα  Aspose.Imaging.PointF  που αντιπροσωπεύει το σημείο εστίασης για την εξασθένιση κλίσης. |

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

### setSigmaBellShape(float focus) {#setSigmaBellShape-float-}
```
public void setSigmaBellShape(float focus)
```


Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής γραμμής από το κέντρο της διαδρομής μέχρι το όριο της διαδρομής, το κεντρικό χρώμα θα είναι στη μέγιστη έντασή του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |

### setSigmaBellShape(float focus, float scale) {#setSigmaBellShape-float-float-}
```
public void setSigmaBellShape(float focus, float scale)
```


Δημιουργεί ένα πινέλο διαβάθμισης που αλλάζει χρώμα ξεκινώντας από το κέντρο της διαδρομής προς τα έξω μέχρι το όριο της διαδρομής. Η μετάβαση από ένα χρώμα στο άλλο βασίζεται σε καμπύλη σχήματος καμπάνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εστίαση | float | Μια τιμή από 0 έως 1 που καθορίζει πού, κατά μήκος οποιασδήποτε ακτινικής γραμμής από το κέντρο της διαδρομής μέχρι το όριο της διαδρομής, το κεντρικό χρώμα θα είναι στη μέγιστη έντασή του. Μια τιμή 1 (η προεπιλογή) τοποθετεί τη μέγιστη ένταση στο κέντρο της διαδρομής. |
| κλίμακα | float | Μια τιμή από 0 έως 1 που καθορίζει τη μέγιστη ένταση του κεντρικού χρώματος που αναμειγνύεται με το χρώμα του ορίου. Μια τιμή 1 προκαλεί τη μέγιστη δυνατή ένταση του κεντρικού χρώματος και είναι η προεπιλεγμένη τιμή. |

### setSurroundColors(Color[] value) {#setSurroundColors-com.aspose.psd.Color---}
```
public void setSurroundColors(Color[] value)
```


Ορίζει έναν πίνακα χρωμάτων που αντιστοιχούν στα σημεία της διαδρομής που γεμίζει αυτό το  PathGradientBrush .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.psd/color) | Ένας πίνακας δομών  com.aspose.psd.Color  που αντιπροσωπεύει τα χρώματα που σχετίζονται με κάθε σημείο της διαδρομής που γεμίζει αυτό το  PathGradientBrush . |

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

