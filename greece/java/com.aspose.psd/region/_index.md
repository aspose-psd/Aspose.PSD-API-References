---
title: "Region"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Περιγράφει το εσωτερικό ενός γραφικού σχήματος που αποτελείται από ορθογώνια και διαδρομές."
type: docs
weight: 90
url: /el/java/com.aspose.psd/region/
---

**Inheritance:**
java.lang.Object
```
public final class Region
```

Περιγράφει το εσωτερικό ενός γραφικού σχήματος που αποτελείται από ορθογώνια και διαδρομές. Αυτή η κλάση δεν μπορεί να κληρονομηθεί.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Region()](#Region--) | Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region . |
| [Region(RectangleF rect)](#Region-com.aspose.psd.RectangleF-) | Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region  από τη συγκεκριμένη  T:Aspose.Imaging.RectangleF  δομή. |
| [Region(Rectangle rect)](#Region-com.aspose.psd.Rectangle-) | Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region  από τη συγκεκριμένη  T:Aspose.Imaging.Rectangle  δομή. |
| [Region(GraphicsPath path)](#Region-com.aspose.psd.GraphicsPath-) | Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region  με το συγκεκριμένο  T:Aspose.Imaging.GraphicsPath . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [complement(GraphicsPath path)](#complement-com.aspose.psd.GraphicsPath-) | Ενημερώνει αυτό το  com.aspose.psd.Region  ώστε να περιέχει το τμήμα του συγκεκριμένου  com.aspose.psd.GraphicsPath  που δεν τέμνει αυτό το  com.aspose.psd.region . |
| [complement(Rectangle rect)](#complement-com.aspose.psd.Rectangle-) | Ενημερώνει αυτό το  com.aspose.psd.Region  ώστε να περιέχει το τμήμα της συγκεκριμένης  com.aspose.psd.Rectangle  δομής που δεν τέμνει αυτό το  com.aspose.psd.region . |
| [complement(RectangleF rect)](#complement-com.aspose.psd.RectangleF-) | Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει το τμήμα της καθορισμένης δομής com.aspose.psd.RectangleF που δεν τέμνει αυτό το com.aspose.psd.region. |
| [complement(Region region)](#complement-com.aspose.psd.Region-) | Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει το τμήμα του καθορισμένου com.aspose.psd.Region που δεν τέμνει αυτό το com.aspose.psd.region. |
| [deepClone()](#deepClone--) | Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του com.aspose.psd.region. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exclude(GraphicsPath path)](#exclude-com.aspose.psd.GraphicsPath-) | Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο com.aspose.psd.graphicsPath. |
| [exclude(Rectangle rect)](#exclude-com.aspose.psd.Rectangle-) | Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή com.aspose.psd.Rectangle. |
| [exclude(RectangleF rect)](#exclude-com.aspose.psd.RectangleF-) | Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή com.aspose.psd.RectangleF. |
| [exclude(Region region)](#exclude-com.aspose.psd.Region-) | Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο com.aspose.psd.region. |
| [getActions_internalized()](#getActions-internalized--) | Λαμβάνει τις ενέργειες της περιοχής. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [intersect(GraphicsPath path)](#intersect-com.aspose.psd.GraphicsPath-) | Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με το καθορισμένο com.aspose.psd.graphicsPath. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με τη καθορισμένη δομή com.aspose.psd.Rectangle. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με τη καθορισμένη δομή com.aspose.psd.RectangleF. |
| [intersect(Region region)](#intersect-com.aspose.psd.Region-) | Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με το καθορισμένο com.aspose.psd.region. |
| [isEmpty(Graphics g)](#isEmpty-com.aspose.psd.Graphics-) | Δοκιμάζει αν αυτό το com.aspose.psd.Region έχει κενό εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης. |
| [isEquals(Region region, Graphics g)](#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-) | Δοκιμάζει αν το καθορισμένο com.aspose.psd.Region είναι ταυτόσιο με αυτό το com.aspose.psd.Region στην καθορισμένη επιφάνεια σχεδίασης. |
| [isInfinite(Graphics g)](#isInfinite-com.aspose.psd.Graphics-) | Δοκιμάζει αν αυτό το com.aspose.psd.Region έχει άπειρο εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.Point περιέχεται σε αυτό το com.aspose.psd.region. |
| [isVisible(Point point, Graphics g)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.Point περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.PointF περιέχεται σε αυτό το com.aspose.psd.region. |
| [isVisible(PointF point, Graphics g)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.PointF περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics. |
| [isVisible(Rectangle rect)](#isVisible-com.aspose.psd.Rectangle-) | Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.Rectangle περιέχεται σε αυτό το com.aspose.psd.region. |
| [isVisible(Rectangle rect, Graphics g)](#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-) | Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.Rectangle περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics. |
| [isVisible(RectangleF rect)](#isVisible-com.aspose.psd.RectangleF-) | Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.RectangleF περιέχεται σε αυτό το com.aspose.psd.region. |
| [isVisible(RectangleF rect, Graphics g)](#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-) | Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.RectangleF περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Δοκιμάζει αν το καθορισμένο σημείο περιέχεται σε αυτό το com.aspose.psd.region. |
| [isVisible(float x, float y, Graphics g)](#isVisible-float-float-com.aspose.psd.Graphics-) | Δοκιμάζει αν το καθορισμένο σημείο περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics. |
| [isVisible(float x, float y, float width, float height)](#isVisible-float-float-float-float-) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.region . |
| [isVisible(float x, float y, float width, float height, Graphics g)](#isVisible-float-float-float-float-com.aspose.psd.Graphics-) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.Region  όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [isVisible(int x, int y, Graphics g)](#isVisible-int-int-com.aspose.psd.Graphics-) | Δοκιμάζει εάν το καθορισμένο σημείο περιέχεται εντός αυτού του αντικειμένου  com.aspose.psd.Region  όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο αντικείμενο  com.aspose.psd.Graphics . |
| [isVisible(int x, int y, int width, int height)](#isVisible-int-int-int-int-) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.region . |
| [isVisible(int x, int y, int width, int height, Graphics g)](#isVisible-int-int-int-int-com.aspose.psd.Graphics-) | Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.Region  όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics . |
| [makeEmpty()](#makeEmpty--) | Αρχικοποιεί αυτό το  com.aspose.psd.Region  με κενό εσωτερικό. |
| [makeInfinite()](#makeInfinite--) | Αρχικοποιεί αυτό το αντικείμενο  com.aspose.psd.Region  με άπειρο εσωτερικό. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOnChangeRegion_internalized(ChangeActionList value)](#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-) | Αποκτά ή ορίζει την περιοχή κατά την αλλαγή. |
| [toString()](#toString--) |  |
| [transform(Matrix matrix)](#transform-com.aspose.psd.Matrix-) | Μετασχηματίζει αυτό το  com.aspose.psd.Region  με τον καθορισμένο  com.aspose.psd.matrix . |
| [translate(float dx, float dy)](#translate-float-float-) | Μετατοπίζει τις συντεταγμένες αυτού του  com.aspose.psd.Region  κατά το καθορισμένο ποσό. |
| [translate(int dx, int dy)](#translate-int-int-) | Μετατοπίζει τις συντεταγμένες αυτού του  com.aspose.psd.Region  κατά το καθορισμένο ποσό. |
| [union(GraphicsPath path)](#union-com.aspose.psd.GraphicsPath-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με τον καθορισμένο  com.aspose.psd.graphicsPath . |
| [union(Rectangle rect)](#union-com.aspose.psd.Rectangle-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με τη δομή  com.aspose.psd.Rectangle  που καθορίζεται. |
| [union(RectangleF rect)](#union-com.aspose.psd.RectangleF-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με τη δομή  com.aspose.psd.RectangleF  που καθορίζεται. |
| [union(Region region)](#union-com.aspose.psd.Region-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με το καθορισμένο  com.aspose.psd.region . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [xor(GraphicsPath path)](#xor-com.aspose.psd.GraphicsPath-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με το καθορισμένο  com.aspose.psd.graphicsPath . |
| [xor(Rectangle rect)](#xor-com.aspose.psd.Rectangle-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με τη δομή  com.aspose.psd.Rectangle  που καθορίζεται. |
| [xor(RectangleF rect)](#xor-com.aspose.psd.RectangleF-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με τη δομή  com.aspose.psd.RectangleF  που καθορίζεται. |
| [xor(Region region)](#xor-com.aspose.psd.Region-) | Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με το καθορισμένο  com.aspose.psd.region . |
### Region() {#Region--}
```
public Region()
```


Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region .

### Region(RectangleF rect) {#Region-com.aspose.psd.RectangleF-}
```
public Region(RectangleF rect)
```


Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region  από τη συγκεκριμένη  T:Aspose.Imaging.RectangleF  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Μια δομή  T:Aspose.Imaging.RectangleF  που ορίζει το εσωτερικό του νέου  T:Aspose.Imaging.Region . |

### Region(Rectangle rect) {#Region-com.aspose.psd.Rectangle-}
```
public Region(Rectangle rect)
```


Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region  από τη συγκεκριμένη  T:Aspose.Imaging.Rectangle  δομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Μια δομή  T:Aspose.Imaging.Rectangle  που ορίζει το εσωτερικό του νέου  T:Aspose.Imaging.Region . |

### Region(GraphicsPath path) {#Region-com.aspose.psd.GraphicsPath-}
```
public Region(GraphicsPath path)
```


Αρχικοποιεί ένα νέο  T:Aspose.Imaging.Region  με το συγκεκριμένο  T:Aspose.Imaging.GraphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Μια  T:Aspose.Imaging.GraphicsPath  που ορίζει το νέο  T:Aspose.Imaging.Region . |

### complement(GraphicsPath path) {#complement-com.aspose.psd.GraphicsPath-}
```
public void complement(GraphicsPath path)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  ώστε να περιέχει το τμήμα του συγκεκριμένου  com.aspose.psd.GraphicsPath  που δεν τέμνει αυτό το  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το  com.aspose.psd.GraphicsPath  για συμπλήρωση αυτού του  com.aspose.psd.region . |

### complement(Rectangle rect) {#complement-com.aspose.psd.Rectangle-}
```
public void complement(Rectangle rect)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  ώστε να περιέχει το τμήμα της συγκεκριμένης  com.aspose.psd.Rectangle  δομής που δεν τέμνει αυτό το  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η δομή  com.aspose.psd.Rectangle  για συμπλήρωση αυτού του  com.aspose.psd.region . |

### complement(RectangleF rect) {#complement-com.aspose.psd.RectangleF-}
```
public void complement(RectangleF rect)
```


Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει το τμήμα της καθορισμένης δομής com.aspose.psd.RectangleF που δεν τέμνει αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή  com.aspose.psd.RectangleF  για συμπλήρωση αυτού του  com.aspose.psd.region . |

### complement(Region region) {#complement-com.aspose.psd.Region-}
```
public void complement(Region region)
```


Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει το τμήμα του καθορισμένου com.aspose.psd.Region που δεν τέμνει αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Το αντικείμενο  com.aspose.psd.Region  για συμπλήρωση αυτού του αντικειμένου  com.aspose.psd.Region . |

### deepClone() {#deepClone--}
```
public Region deepClone()
```


Δημιουργεί ένα ακριβές βαθύ αντίγραφο αυτού του com.aspose.psd.region.

**Returns:**
[Region](../../com.aspose.psd/region) - The  com.aspose.psd.Region  that this method creates.
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
### exclude(GraphicsPath path) {#exclude-com.aspose.psd.GraphicsPath-}
```
public void exclude(GraphicsPath path)
```


Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο com.aspose.psd.graphicsPath.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το  com.aspose.psd.GraphicsPath  για εξαίρεση από αυτό το  com.aspose.psd.region . |

### exclude(Rectangle rect) {#exclude-com.aspose.psd.Rectangle-}
```
public void exclude(Rectangle rect)
```


Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή com.aspose.psd.Rectangle.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η δομή  com.aspose.psd.Rectangle  για εξαίρεση από αυτό το  com.aspose.psd.region . |

### exclude(RectangleF rect) {#exclude-com.aspose.psd.RectangleF-}
```
public void exclude(RectangleF rect)
```


Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει τη καθορισμένη δομή com.aspose.psd.RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF για εξαίρεση από αυτήν την com.aspose.psd.region. |

### exclude(Region region) {#exclude-com.aspose.psd.Region-}
```
public void exclude(Region region)
```


Ενημερώνει αυτό το com.aspose.psd.Region ώστε να περιέχει μόνο το τμήμα του εσωτερικού του που δεν τέμνει το καθορισμένο com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Η com.aspose.psd.Region για εξαίρεση από αυτήν την com.aspose.psd.region. |

### getActions_internalized() {#getActions-internalized--}
```
public RegionAction[] getActions_internalized()
```


Λαμβάνει τις ενέργειες της περιοχής.

**Returns:**
com.aspose.internal.RegionAction[] - Οι ενέργειες περιοχής.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intersect(GraphicsPath path) {#intersect-com.aspose.psd.GraphicsPath-}
```
public void intersect(GraphicsPath path)
```


Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με το καθορισμένο com.aspose.psd.graphicsPath.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Η com.aspose.psd.GraphicsPath για τομή με αυτήν την com.aspose.psd.region. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με τη καθορισμένη δομή com.aspose.psd.Rectangle.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η δομή com.aspose.psd.Rectangle για τομή με αυτήν την com.aspose.psd.region. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με τη καθορισμένη δομή com.aspose.psd.RectangleF.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF για τομή με αυτήν την com.aspose.psd.region. |

### intersect(Region region) {#intersect-com.aspose.psd.Region-}
```
public void intersect(Region region)
```


Ενημερώνει αυτό το com.aspose.psd.Region στην τομή του με το καθορισμένο com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Η com.aspose.psd.Region για τομή με αυτήν την com.aspose.psd.region. |

### isEmpty(Graphics g) {#isEmpty-com.aspose.psd.Graphics-}
```
public boolean isEmpty(Graphics g)
```


Δοκιμάζει αν αυτό το com.aspose.psd.Region έχει κενό εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει μια επιφάνεια σχεδίασης. |

**Returns:**
boolean - true αν το εσωτερικό αυτής της com.aspose.psd.Region είναι κενό όταν εφαρμόζεται η μετασχηματισμός που σχετίζεται με το g· διαφορετικά, false.
### isEquals(Region region, Graphics g) {#isEquals-com.aspose.psd.Region-com.aspose.psd.Graphics-}
```
public boolean isEquals(Region region, Graphics g)
```


Δοκιμάζει αν το καθορισμένο com.aspose.psd.Region είναι ταυτόσιο με αυτό το com.aspose.psd.Region στην καθορισμένη επιφάνεια σχεδίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Η com.aspose.psd.Region για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει μια επιφάνεια σχεδίασης. |

**Returns:**
boolean - True αν το εσωτερικό της περιοχής είναι ταυτόσημο με το εσωτερικό αυτής της περιοχής όταν εφαρμόζεται η μετασχηματισμός που σχετίζεται με την παράμετρο g· διαφορετικά, false.
### isInfinite(Graphics g) {#isInfinite-com.aspose.psd.Graphics-}
```
public boolean isInfinite(Graphics g)
```


Δοκιμάζει αν αυτό το com.aspose.psd.Region έχει άπειρο εσωτερικό στην καθορισμένη επιφάνεια σχεδίασης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει μια επιφάνεια σχεδίασης. |

**Returns:**
boolean - true αν το εσωτερικό αυτής της com.aspose.psd.Region είναι άπειρο όταν εφαρμόζεται η μετασχηματισμός που σχετίζεται με το g· διαφορετικά, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.Point περιέχεται σε αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Η δομή com.aspose.psd.Point για δοκιμή. |

**Returns:**
boolean - true όταν το point περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(Point point, Graphics g) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point point, Graphics g)
```


Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.Point περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Η δομή com.aspose.psd.Point για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν το point περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.PointF περιέχεται σε αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Η δομή com.aspose.psd.PointF για δοκιμή. |

**Returns:**
boolean - true όταν το point περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(PointF point, Graphics g) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF point, Graphics g)
```


Δοκιμάζει αν η καθορισμένη δομή com.aspose.psd.PointF περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Η δομή com.aspose.psd.PointF για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν το point περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(Rectangle rect) {#isVisible-com.aspose.psd.Rectangle-}
```
public boolean isVisible(Rectangle rect)
```


Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.Rectangle περιέχεται σε αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η δομή com.aspose.psd.Rectangle για δοκιμή. |

**Returns:**
boolean - Αυτή η μέθοδος επιστρέφει true όταν οποιοδήποτε τμήμα του rect περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(Rectangle rect, Graphics g) {#isVisible-com.aspose.psd.Rectangle-com.aspose.psd.Graphics-}
```
public boolean isVisible(Rectangle rect, Graphics g)
```


Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.Rectangle περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η δομή com.aspose.psd.Rectangle για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του rect περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(RectangleF rect) {#isVisible-com.aspose.psd.RectangleF-}
```
public boolean isVisible(RectangleF rect)
```


Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.RectangleF περιέχεται σε αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF για δοκιμή. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του rect περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(RectangleF rect, Graphics g) {#isVisible-com.aspose.psd.RectangleF-com.aspose.psd.Graphics-}
```
public boolean isVisible(RectangleF rect, Graphics g)
```


Δοκιμάζει αν οποιοδήποτε τμήμα της καθορισμένης δομής com.aspose.psd.RectangleF περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η δομή com.aspose.psd.RectangleF για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν το rect περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Δοκιμάζει αν το καθορισμένο σημείο περιέχεται σε αυτό το com.aspose.psd.region.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |

**Returns:**
boolean - True όταν το καθορισμένο σημείο περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(float x, float y, Graphics g) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics g)
```


Δοκιμάζει αν το καθορισμένο σημείο περιέχεται σε αυτό το com.aspose.psd.Region όταν σχεδιάζεται με το καθορισμένο com.aspose.psd.graphics.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | float | Η συντεταγμένη y του σημείου για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - True όταν το καθορισμένο σημείο περιέχεται μέσα σε αυτήν την com.aspose.psd.Region· διαφορετικά, false.
### isVisible(float x, float y, float width, float height) {#isVisible-float-float-float-float-}
```
public boolean isVisible(float x, float y, float width, float height)
```


Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| πλάτος | float | Το πλάτος του ορθογωνίου για δοκιμή. |
| ύψος | float | Το ύψος του ορθογωνίου για δοκιμή. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το αντικείμενο com.aspose.psd.Region; διαφορετικά, false.
### isVisible(float x, float y, float width, float height, Graphics g) {#isVisible-float-float-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, float width, float height, Graphics g)
```


Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.Region  όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | float | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| y | float | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| πλάτος | float | Το πλάτος του ορθογωνίου για δοκιμή. |
| ύψος | float | Το ύψος του ορθογωνίου για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το com.aspose.psd.Region; διαφορετικά, false.
### isVisible(int x, int y, Graphics g) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics g)
```


Δοκιμάζει εάν το καθορισμένο σημείο περιέχεται εντός αυτού του αντικειμένου  com.aspose.psd.Region  όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο αντικείμενο  com.aspose.psd.Graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x του σημείου για δοκιμή. |
| y | int | Η συντεταγμένη y του σημείου για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν το καθορισμένο σημείο περιέχεται μέσα σε αυτό το com.aspose.psd.Region; διαφορετικά, false.
### isVisible(int x, int y, int width, int height) {#isVisible-int-int-int-int-}
```
public boolean isVisible(int x, int y, int width, int height)
```


Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| πλάτος | int | Το πλάτος του ορθογωνίου για δοκιμή. |
| ύψος | int | Το ύψος του ορθογωνίου για δοκιμή. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το com.aspose.psd.Region; διαφορετικά, false.
### isVisible(int x, int y, int width, int height, Graphics g) {#isVisible-int-int-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, int width, int height, Graphics g)
```


Δοκιμάζει εάν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται εντός αυτού του  com.aspose.psd.Region  όταν σχεδιάζεται χρησιμοποιώντας το καθορισμένο  com.aspose.psd.graphics .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη x της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| y | int | Η συντεταγμένη y της επάνω αριστερής γωνίας του ορθογωνίου για δοκιμή. |
| πλάτος | int | Το πλάτος του ορθογωνίου για δοκιμή. |
| ύψος | int | Το ύψος του ορθογωνίου για δοκιμή. |
| g | [Graphics](../../com.aspose.psd/graphics) | Ένα com.aspose.psd.Graphics που αντιπροσωπεύει ένα πλαίσιο γραφικών. |

**Returns:**
boolean - true όταν οποιοδήποτε τμήμα του καθορισμένου ορθογωνίου περιέχεται μέσα σε αυτό το com.aspose.psd.Region; διαφορετικά, false.
### makeEmpty() {#makeEmpty--}
```
public void makeEmpty()
```


Αρχικοποιεί αυτό το  com.aspose.psd.Region  με κενό εσωτερικό.

### makeInfinite() {#makeInfinite--}
```
public void makeInfinite()
```


Αρχικοποιεί αυτό το αντικείμενο  com.aspose.psd.Region  με άπειρο εσωτερικό.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setOnChangeRegion_internalized(ChangeActionList value) {#setOnChangeRegion-internalized-com.aspose.internal.ChangeActionList-}
```
public final void setOnChangeRegion_internalized(ChangeActionList value)
```


Αποκτά ή ορίζει την περιοχή κατά την αλλαγή.

Τιμή: Η περιοχή κατά την αλλαγή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | com.aspose.internal.ChangeActionList |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix matrix) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix matrix)
```


Μετασχηματίζει αυτό το  com.aspose.psd.Region  με τον καθορισμένο  com.aspose.psd.matrix .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Η com.aspose.psd.Matrix με την οποία θα μετασχηματιστεί αυτό το com.aspose.psd.region. |

### translate(float dx, float dy) {#translate-float-float-}
```
public void translate(float dx, float dy)
```


Μετατοπίζει τις συντεταγμένες αυτού του  com.aspose.psd.Region  κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | float | Το ποσό για οριζόντια μετατόπιση αυτού του com.aspose.psd.Region. |
| dy | float | Το ποσό για κάθετη μετατόπιση αυτού του com.aspose.psd.Region. |

### translate(int dx, int dy) {#translate-int-int-}
```
public void translate(int dx, int dy)
```


Μετατοπίζει τις συντεταγμένες αυτού του  com.aspose.psd.Region  κατά το καθορισμένο ποσό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dx | int | Το ποσό για οριζόντια μετατόπιση αυτού του com.aspose.psd.Region. |
| dy | int | Το ποσό για κάθετη μετατόπιση αυτού του com.aspose.psd.Region. |

### union(GraphicsPath path) {#union-com.aspose.psd.GraphicsPath-}
```
public void union(GraphicsPath path)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με τον καθορισμένο  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το com.aspose.psd.GraphicsPath για ένωση με αυτό το com.aspose.psd.region. |

### union(Rectangle rect) {#union-com.aspose.psd.Rectangle-}
```
public void union(Rectangle rect)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με τη δομή  com.aspose.psd.Rectangle  που καθορίζεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η com.aspose.psd.Rectangle δομή για ένωση με αυτό το com.aspose.psd.region. |

### union(RectangleF rect) {#union-com.aspose.psd.RectangleF-}
```
public void union(RectangleF rect)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με τη δομή  com.aspose.psd.RectangleF  που καθορίζεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η com.aspose.psd.RectangleF δομή για ένωση με αυτό το com.aspose.psd.region. |

### union(Region region) {#union-com.aspose.psd.Region-}
```
public void union(Region region)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση του με το καθορισμένο  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Το com.aspose.psd.Region για ένωση με αυτό το com.aspose.psd.region. |

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

### xor(GraphicsPath path) {#xor-com.aspose.psd.GraphicsPath-}
```
public void xor(GraphicsPath path)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με το καθορισμένο  com.aspose.psd.graphicsPath .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | [GraphicsPath](../../com.aspose.psd/graphicspath) | Το com.aspose.psd.GraphicsPath για XOR με αυτό το com.aspose.psd.region. |

### xor(Rectangle rect) {#xor-com.aspose.psd.Rectangle-}
```
public void xor(Rectangle rect)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με τη δομή  com.aspose.psd.Rectangle  που καθορίζεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Η com.aspose.psd.Rectangle δομή για XOR με αυτό το com.aspose.psd.region. |

### xor(RectangleF rect) {#xor-com.aspose.psd.RectangleF-}
```
public void xor(RectangleF rect)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με τη δομή  com.aspose.psd.RectangleF  που καθορίζεται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Η com.aspose.psd.RectangleF δομή για XOR με αυτό το com.aspose.psd.region. |

### xor(Region region) {#xor-com.aspose.psd.Region-}
```
public void xor(Region region)
```


Ενημερώνει αυτό το  com.aspose.psd.Region  στην ένωση μείον τη διασταύρωση του με το καθορισμένο  com.aspose.psd.region .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| region | [Region](../../com.aspose.psd/region) | Το com.aspose.psd.Region για XOR με αυτό το com.aspose.psd.region. |

