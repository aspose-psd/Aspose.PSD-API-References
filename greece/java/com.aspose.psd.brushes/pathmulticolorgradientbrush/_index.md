---
title: "PathMulticolorGradientBrush"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιλαμβάνει ένα αντικείμενο Aspose.Imaging.Brush με μια κλίση."
type: docs
weight: 16
url: /el/java/com.aspose.psd.brushes/pathmulticolorgradientbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush), [com.aspose.psd.brushes.TransformBrush](../../com.aspose.psd.brushes/transformbrush), [com.aspose.psd.brushes.PathGradientBrushBase](../../com.aspose.psd.brushes/pathgradientbrushbase)
```
public final class PathMulticolorGradientBrush extends PathGradientBrushBase
```

Περιλαμβάνει ένα  Aspose.Imaging.Brush  αντικείμενο με μια κλίση. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PathMulticolorGradientBrush(PointF[] points)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---) | Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία. |
| [PathMulticolorGradientBrush(PointF[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathMulticolorGradientBrush(Point[] points)](#PathMulticolorGradientBrush-com.aspose.psd.Point---) | Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία. |
| [PathMulticolorGradientBrush(Point[] points, int wrapMode)](#PathMulticolorGradientBrush-com.aspose.psd.Point---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης. |
| [PathMulticolorGradientBrush(GraphicsPath path)](#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τη καθορισμένη διαδρομή. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Υλοποιεί το interface Closable και μπορεί να χρησιμοποιηθεί στη δήλωση try-with-resources από το JDK 1.7. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα νέο βαθύ κλώνο του τρέχοντος Brush. |
| [dispose()](#dispose--) | Αποδεσμεύει την τρέχουσα παρουσία. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCenterPoint()](#getCenterPoint--) | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει διαγραφεί. |
| [getFocusScales()](#getFocusScales--) | Λαμβάνει το σημείο εστίασης για την εξασθένιση της διαβάθμισης. |
| [getGraphicsPath()](#getGraphicsPath--) | Λαμβάνει τη διαδρομή γραφικών πάνω στην οποία δημιουργήθηκε αυτό το πινέλο. |
| [getInterpolationColors()](#getInterpolationColors--) | Λαμβάνει ή ορίζει ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολύχρωμη γραμμική κλίση. |
| [getOpacity()](#getOpacity--) | Λαμβάνει τη διαφάνεια του πινέλου. |
| [getPathPoints()](#getPathPoints--) | Λαμβάνει τα σημεία διαδρομής πάνω στα οποία δημιουργήθηκε αυτό το πινέλο. |
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
| [setCenterPoint(PointF value)](#setCenterPoint-com.aspose.psd.PointF-) | Λαμβάνει ή ορίζει το κεντρικό σημείο της διαβάθμισης διαδρομής. |
| [setFocusScales(PointF value)](#setFocusScales-com.aspose.psd.PointF-) | Λαμβάνει ή ορίζει το σημείο εστίασης για την εξασθένιση κλίσης. |
| [setInterpolationColors(ColorBlend value)](#setInterpolationColors-com.aspose.psd.ColorBlend-) | Λαμβάνει ή ορίζει ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολύχρωμη γραμμική κλίση. |
| [setOpacity(float value)](#setOpacity-float-) | Ορίζει τη διαφάνεια του πινέλου. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Λαμβάνει ή ορίζει ένα αντίγραφο του Aspose.Imaging.Matrix που ορίζει έναν τοπικό γεωμετρικό μετασχηματισμό για αυτό το TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Λαμβάνει ή ορίζει μια απαρίθμηση Aspose.Imaging.WrapMode που υποδεικνύει τη λειτουργία περιτύλιξης για αυτό το TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Μετατοπίζει τη τοπική γεωμετρική μετατροπή κατά τις καθορισμένες διαστάσεις με τη καθορισμένη σειρά. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PathMulticolorGradientBrush(PointF[] points) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---}
```
public PathMulticolorGradientBrush(PointF[] points)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  Aspose.Imaging.PointF  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### PathMulticolorGradientBrush(PointF[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.PointF---int-}
```
public PathMulticolorGradientBrush(PointF[] points, int wrapMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  Aspose.Imaging.PointF  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrapMode | int | Ένα  Aspose.Imaging.WrapMode  που καθορίζει πώς τα γεμίσματα που σχεδιάζονται με αυτό το  PathMulticolorGradientBrush  τοποθετούνται σε πλακίδια. |

### PathMulticolorGradientBrush(Point[] points) {#PathMulticolorGradientBrush-com.aspose.psd.Point---}
```
public PathMulticolorGradientBrush(Point[] points)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Ένας πίνακας δομών  Aspose.Imaging.Point  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |

### PathMulticolorGradientBrush(Point[] points, int wrapMode) {#PathMulticolorGradientBrush-com.aspose.psd.Point---int-}
```
public PathMulticolorGradientBrush(Point[] points, int wrapMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τα καθορισμένα σημεία και τη λειτουργία περιτύλιξης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| points | [Point\[\]](../../com.aspose.psd/point) | Ένας πίνακας δομών  Aspose.Imaging.Point  που αντιπροσωπεύει τα σημεία που σχηματίζουν τις κορυφές της διαδρομής. |
| wrapMode | int | Ένα  Aspose.Imaging.WrapMode  που καθορίζει πώς τα γεμίσματα που σχεδιάζονται με αυτό το  PathMulticolorGradientBrush  τοποθετούνται σε πλακίδια. |

### PathMulticolorGradientBrush(GraphicsPath path) {#PathMulticolorGradientBrush-com.aspose.psd.GraphicsPath-}
```
public PathMulticolorGradientBrush(GraphicsPath path)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  PathMulticolorGradientBrush  με τη καθορισμένη διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Η  GraphicsPath  που ορίζει την περιοχή που γεμίζει αυτό το  PathMulticolorGradientBrush . |

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


Λαμβάνει ή ορίζει ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολύχρωμη γραμμική κλίση.

Τιμή: Ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολύχρωμη γραμμική κλίση.

**Returns:**
[ColorBlend](../../com.aspose.psd/colorblend)
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


Λαμβάνει ή ορίζει ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολύχρωμη γραμμική κλίση.

Τιμή: Ένα  com.aspose.psd.ColorBlend  που ορίζει μια πολύχρωμη γραμμική κλίση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ColorBlend](../../com.aspose.psd/colorblend) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Ορίζει τη διαφάνεια της πινέλου. Η τιμή πρέπει να είναι μεταξύ 0 και 1. Τιμή 0 σημαίνει ότι το πινέλο είναι πλήρως ορατό, τιμή 1 σημαίνει ότι το πινέλο είναι πλήρως αδιαφανές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float | Η τιμή διαφάνειας του πινέλου. |

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

