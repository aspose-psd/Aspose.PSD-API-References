---
title: "GraphicsPath"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Αναπαριστά μια σειρά συνδεδεμένων γραμμών και καμπυλών"
type: docs
weight: 50
url: /el/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Αναπαριστά μια σειρά συνδεδεμένων γραμμών και καμπυλών. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath . |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath . |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath . |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Προσθέτει ένα νέο σχήμα. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Προσθέτει νέα σχήματα. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Προσθέτει στο τέλος το καθορισμένο  com.aspose.psd.GraphicsPath  σε αυτή τη διαδρομή. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Προσθέτει στο τέλος το καθορισμένο  com.aspose.psd.GraphicsPath  σε αυτή τη διαδρομή. |
| [deepClone()](#deepClone--) | Εκτελεί ένα βαθύ κλώνο αυτής της διαδρομής γραφικών. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Μετατρέπει κάθε καμπύλη σε αυτή τη διαδρομή σε μια σειρά συνδεδεμένων τμημάτων γραμμής. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό το  com.aspose.psd.GraphicsPath  σε μια σειρά συνδεδεμένων τμημάτων γραμμής. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Μετατρέπει κάθε καμπύλη σε αυτό το  com.aspose.psd.GraphicsPath  σε μια σειρά συνδεδεμένων τμημάτων γραμμής. |
| [getBounds()](#getBounds--) | Λαμβάνει ή ορίζει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Λαμβάνει τα όρια του αντικειμένου. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Αποκτά τα σχήματα της διαδρομής. |
| [getFillMode()](#getFillMode--) | Αποκτά μια απαρίθμηση  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτό το  com.aspose.psd.GraphicsPath . |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen . |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen . |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen . |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen . |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath . |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath . |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath . |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y)](#isVisible-float-float-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath . |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath  στην ορατή περιοχή αποκοπής του καθορισμένου  com.aspose.psd.graphics . |
| [isVisible(int x, int y)](#isVisible-int-int-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath . |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath , χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Αφαιρεί ένα σχήμα. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Αφαιρεί σχήματα. |
| [reset()](#reset--) | Αδειάζει τη διαδρομή γραφικών και ορίζει το  com.aspose.psd.FillMode  σε  F:com.aspose.psd.fillMode.alternate . |
| [reverse()](#reverse--) | Αντιστρέφει τη σειρά των σχημάτων, μορφών και σημείων σε κάθε μορφή αυτής της  com.aspose.psd.graphicsPath . |
| [setFillMode(int value)](#setFillMode-int-) | Ορίζει μια απαρίθμηση  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτή τη  com.aspose.psd.GraphicsPath . |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath . |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath . |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Προσθέτει ένα επιπλέον περίγραμμα στη διαδρομή. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Προσθέτει ένα επιπλέον περίγραμμα στο  com.aspose.psd.graphicsPath . |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Αντικαθιστά αυτό το  com.aspose.psd.GraphicsPath  με καμπύλες που περικλείουν την περιοχή που γεμίζει όταν αυτή η διαδρομή σχεδιάζεται με το καθορισμένο στυλό. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath .

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Τα σχήματα από τα οποία θα γίνει αρχικοποίηση. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Τα σχήματα από τα οποία θα γίνει αρχικοποίηση. |
| fillMode | int | Η λειτουργία γεμίσματος. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  GraphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillMode | int | Η λειτουργία γεμίσματος. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Προσθέτει ένα νέο σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Το σχήμα προς προσθήκη. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Προσθέτει νέα σχήματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Τα σχήματα προς προσθήκη. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Προσθέτει στο τέλος το καθορισμένο  com.aspose.psd.GraphicsPath  σε αυτή τη διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το  com.aspose.psd.GraphicsPath  προς προσθήκη. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Προσθέτει στο τέλος το καθορισμένο  com.aspose.psd.GraphicsPath  σε αυτή τη διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το  com.aspose.psd.GraphicsPath  προς προσθήκη. |
| connect | boolean | Μια λογική τιμή που καθορίζει εάν το πρώτο σχήμα στην προστιθέμενη διαδρομή αποτελεί μέρος του τελευταίου σχήματος σε αυτή τη διαδρομή. Μια τιμή true υποδεικνύει ότι το πρώτο σχήμα στην προστιθέμενη διαδρομή αποτελεί μέρος του τελευταίου σχήματος σε αυτή τη διαδρομή. Μια τιμή false υποδεικνύει ότι το πρώτο σχήμα στην προστιθέμενη διαδρομή είναι ξεχωριστό από το τελευταίο σχήμα σε αυτή τη διαδρομή. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Εκτελεί ένα βαθύ κλώνο αυτής της διαδρομής γραφικών.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
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
### flatten() {#flatten--}
```
public void flatten()
```


Μετατρέπει κάθε καμπύλη σε αυτή τη διαδρομή σε μια σειρά συνδεδεμένων τμημάτων γραμμής.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Εφαρμόζει τον καθορισμένο μετασχηματισμό και στη συνέχεια μετατρέπει κάθε καμπύλη σε αυτό το  com.aspose.psd.GraphicsPath  σε μια σειρά συνδεδεμένων τμημάτων γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  με τον οποίο θα μετασχηματιστεί αυτό το  com.aspose.psd.GraphicsPath  πριν την εξομάλυνση. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Μετατρέπει κάθε καμπύλη σε αυτό το  com.aspose.psd.GraphicsPath  σε μια σειρά συνδεδεμένων τμημάτων γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  με τον οποίο θα μετασχηματιστεί αυτό το  com.aspose.psd.GraphicsPath  πριν την εξομάλυνση. |
| flatness | float | Καθορίζει το μέγιστο επιτρεπόμενο σφάλμα μεταξύ της καμπύλης και της εξομαλυνμένης προσέγγισής της. Μια τιμή 0,25 είναι η προεπιλογή. Η μείωση της τιμής flatness θα αυξήσει τον αριθμό των τμημάτων γραμμής στην προσέγγιση. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Λαμβάνει ή ορίζει τα όρια του αντικειμένου.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η μήτρα που θα εφαρμοστεί πριν υπολογιστούν τα όρια. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Λαμβάνει τα όρια του αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η μήτρα που θα εφαρμοστεί πριν υπολογιστούν τα όρια. |
| pen | [Pen](../../com.aspose.psd/pen) | Το στυλό που θα χρησιμοποιηθεί για το αντικείμενο. Αυτό μπορεί να επηρεάσει το μέγεθος των ορίων του αντικειμένου. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Αποκτά τα σχήματα της διαδρομής.

**Returns:**
com.aspose.psd.Figure[] - Τα σχήματα της διαδρομής.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Αποκτά μια απαρίθμηση  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτό το  com.aspose.psd.GraphicsPath .

**Returns:**
int - Η λειτουργία γεμίσματος. Μια απαρίθμηση  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτή τη  com.aspose.psd.GraphicsPath .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Ένα  com.aspose.psd.Point  που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Ένα  com.aspose.psd.Point  που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όπως σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Ένα  com.aspose.psd.PointF  που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Ένα  com.aspose.psd.PointF  που καθορίζει τη θέση για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) από το περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όπως σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) από το περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όπως σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.pen .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα (κάτω) στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όταν σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen  και χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| pen | [Pen](../../com.aspose.psd/pen) | Το  com.aspose.psd.Pen  για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα στο περίγραμμα αυτού του  com.aspose.psd.GraphicsPath  όπως σχεδιάζεται με το καθορισμένο  com.aspose.psd.Pen· διαφορετικά, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Ένα  com.aspose.psd.Point  που αντιπροσωπεύει το σημείο για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Ένα  com.aspose.psd.Point  που αντιπροσωπεύει το σημείο για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Ένα  com.aspose.psd.PointF  που αντιπροσωπεύει το σημείο για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Ένα  com.aspose.psd.PointF  που αντιπροσωπεύει το σημείο για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό· διαφορετικά, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath  στην ορατή περιοχή αποκοπής του καθορισμένου  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Δείχνει εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath , χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | Το  com.aspose.psd.Graphics  για το οποίο θα δοκιμαστεί η ορατότητα. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true εάν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το  com.aspose.psd.GraphicsPath· διαφορετικά, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Αφαιρεί ένα σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Το σχήμα για αφαίρεση. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Αφαιρεί σχήματα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Τα σχήματα για αφαίρεση. |

### reset() {#reset--}
```
public void reset()
```


Αδειάζει τη διαδρομή γραφικών και ορίζει το  com.aspose.psd.FillMode  σε  F:com.aspose.psd.fillMode.alternate .

### reverse() {#reverse--}
```
public void reverse()
```


Αντιστρέφει τη σειρά των σχημάτων, μορφών και σημείων σε κάθε μορφή αυτής της  com.aspose.psd.graphicsPath .

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Ορίζει μια απαρίθμηση  com.aspose.psd.FillMode  που καθορίζει πώς γεμίζουν τα εσωτερικά των σχημάτων σε αυτή τη  com.aspose.psd.GraphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Η λειτουργία γεμίσματος. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Εφαρμόζει τον καθορισμένο μετασχηματισμό στο σχήμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Η μετατροπή που θα εφαρμοστεί. |

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

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  com.aspose.psd.PointF  που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από το  srcRect. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ένα  com.aspose.psd.RectangleF  που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από το  destPoints . |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  com.aspose.psd.PointF  που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από το  srcRect. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ένα  com.aspose.psd.RectangleF  που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από το  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  που καθορίζει έναν γεωμετρικό μετασχηματισμό προς εφαρμογή στο μονοπάτι. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  com.aspose.psd.PointF  που ορίζει ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από το  srcRect. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ένα  com.aspose.psd.RectangleF  που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από το  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  που καθορίζει έναν γεωμετρικό μετασχηματισμό προς εφαρμογή στο μονοπάτι. |
| warpMode | int | Μια απαρίθμηση  com.aspose.psd.WarpMode  που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμική λειτουργία. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Εφαρμόζει μια παραμόρφωση, ορισμένη από ένα ορθογώνιο και ένα παραλληλόγραμμο, σε αυτή τη  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Ένας πίνακας δομών  com.aspose.psd.PointF  που ορίζουν ένα παραλληλόγραμμο στο οποίο μετασχηματίζεται το ορθογώνιο που ορίζεται από το  srcRect. Ο πίνακας μπορεί να περιέχει τρία ή τέσσερα στοιχεία. Εάν ο πίνακας περιέχει τρία στοιχεία, η κάτω-δεξιά γωνία του παραλληλογράμμου υπονοείται από τα πρώτα τρία σημεία. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Ένα  com.aspose.psd.RectangleF  που αντιπροσωπεύει το ορθογώνιο που μετασχηματίζεται στο παραλληλόγραμμο που ορίζεται από το  destPoints . |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  που καθορίζει έναν γεωμετρικό μετασχηματισμό προς εφαρμογή στο μονοπάτι. |
| warpMode | int | Μια απαρίθμηση  com.aspose.psd.WarpMode  που καθορίζει εάν αυτή η λειτουργία παραμόρφωσης χρησιμοποιεί προοπτική ή διγραμμική λειτουργία. |
| flatness | float | Μια τιμή από 0 έως 1 που καθορίζει πόσο επίπεδο είναι το τελικό μονοπάτι. Για περισσότερες πληροφορίες, δείτε τις μεθόδους  com.aspose.psd.GraphicsPath.flatten . |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Προσθέτει ένα επιπλέον περίγραμμα στη διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ένα  com.aspose.psd.Pen  που καθορίζει το πλάτος μεταξύ του αρχικού περιγράμματος του μονοπατιού και του νέου περιγράμματος που δημιουργεί αυτή η μέθοδος. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Προσθέτει ένα επιπλέον περίγραμμα στο  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ένα  com.aspose.psd.Pen  που καθορίζει το πλάτος μεταξύ του αρχικού περιγράμματος του μονοπατιού και του νέου περιγράμματος που δημιουργεί αυτή η μέθοδος. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  που καθορίζει έναν μετασχηματισμό προς εφαρμογή στο μονοπάτι πριν το διευρύνει. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Αντικαθιστά αυτό το  com.aspose.psd.GraphicsPath  με καμπύλες που περικλείουν την περιοχή που γεμίζει όταν αυτή η διαδρομή σχεδιάζεται με το καθορισμένο στυλό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Ένα  com.aspose.psd.Pen  που καθορίζει το πλάτος μεταξύ του αρχικού περιγράμματος του μονοπατιού και του νέου περιγράμματος που δημιουργεί αυτή η μέθοδος. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Ένας  com.aspose.psd.Matrix  που καθορίζει έναν μετασχηματισμό προς εφαρμογή στο μονοπάτι πριν το διευρύνει. |
| flatness | float | Μια τιμή που καθορίζει την ομαλότητα των καμπυλών. |

