---
title: "Rechteck"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Speichert einen Satz von vier Ganzzahlen, die die Position und Größe eines Rechtecks darstellen."
type: docs
weight: 88
url: /de/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Speichert einen Satz von vier Ganzzahlen, die die Position und Größe eines Rechtecks darstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialisiert eine neue Instanz der  com.aspose.psd.Rectangle  Struktur mit dem angegebenen Ort und der Größe. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Initialisiert eine neue Instanz der  com.aspose.psd.Rectangle  Struktur mit dem angegebenen Ort und der Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Konvertiert die angegebene  com.aspose.psd.RectangleF  Struktur in eine  com.aspose.psd.Rectangle  Struktur, indem die  com.aspose.psd.RectangleF  Werte auf die nächsthöheren Ganzzahlen gerundet werden. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.Rectangle  Struktur enthalten ist. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Bestimmt, ob der durch  rect  dargestellte rechteckige Bereich vollständig innerhalb dieser  com.aspose.psd.Rectangle  Struktur enthalten ist. |
| [contains(int x, int y)](#contains-int-int-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.Rectangle  Struktur enthalten ist. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob  obj  eine  com.aspose.psd.Rectangle  Struktur mit demselben Ort und derselben Größe wie diese  com.aspose.psd.Rectangle  Struktur ist. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Erstellt eine  com.aspose.psd.Rectangle  Struktur mit den angegebenen Kantenpositionen. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Erstellt ein neues  Rectangle  aus zwei angegebenen Punkten. |
| [getBottom()](#getBottom--) | Liest oder setzt die y‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.Y  und  com.aspose.psd.Rectangle.Height  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Liest eine neue Instanz der  com.aspose.psd.Rectangle  Struktur, deren Werte für  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  und  com.aspose.psd.Rectangle.Height  auf Null gesetzt sind. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe dieser  com.aspose.psd.Rectangle  Struktur. |
| [getLeft()](#getLeft--) | Liest oder setzt die x‑Koordinate der linken Kante dieser  com.aspose.psd.Rectangle  Struktur. |
| [getLocation()](#getLocation--) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| [getRight()](#getRight--) | Liest oder setzt die x‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Width  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist. |
| [getSize()](#getSize--) | Liest oder setzt die Größe dieser  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Liest oder setzt die y‑Koordinate der oberen Kante dieser  com.aspose.psd.Rectangle  Struktur. |
| [getWidth()](#getWidth--) | Liest die Breite dieser  com.aspose.psd.Rectangle  Struktur. |
| [getX()](#getX--) | Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| [getY()](#getY--) | Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| [hashCode()](#hashCode--) | Gibt den Hashcode für diese  com.aspose.psd.Rectangle  Struktur zurück. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen  com.aspose.psd.Rectangle  Struktur zurück. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Bläht diese  com.aspose.psd.Rectangle  um den angegebenen Betrag auf. |
| [inflate(int width, int height)](#inflate-int-int-) | Bläht diese  com.aspose.psd.Rectangle  um den angegebenen Betrag auf. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Ersetzt diese  com.aspose.psd.Rectangle  durch die Schnittmenge von ihr selbst und der angegebenen  com.aspose.psd.Rectangle . |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Gibt eine dritte  com.aspose.psd.Rectangle  Struktur zurück, die die Schnittmenge zweier anderer  com.aspose.psd.Rectangle  Strukturen darstellt. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Bestimmt, ob dieses Rechteck mit  rect  schneidet. |
| [isEmpty()](#isEmpty--) | Liest einen Wert, der angibt, ob alle numerischen Eigenschaften dieser  com.aspose.psd.Rectangle  den Wert Null haben. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Liest einen Wert, der angibt, ob dieses  Rectangle  mindestens teilweise sichtbar ist |
| [normalize()](#normalize--) | Normalisiert das Rechteck, indem es Breite und Höhe positiv macht, links kleiner als rechts und oben kleiner als unten setzt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [offset(int x, int y)](#offset-int-int-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Testet, ob zwei  com.aspose.psd.Rectangle  Strukturen die gleiche Position und Größe haben. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Testet, ob sich zwei  com.aspose.psd.Rectangle  Strukturen in Position oder Größe unterscheiden. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Konvertiert das angegebene  com.aspose.psd.RectangleF  in ein  com.aspose.psd.Rectangle , indem die Werte von  com.aspose.psd.RectangleF  auf die nächsten Ganzzahlen gerundet werden. |
| [setBottom(int value)](#setBottom-int-) | Liest oder setzt die y‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.Y  und  com.aspose.psd.Rectangle.Height  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist. |
| [setHeight(int value)](#setHeight-int-) | Liest oder setzt die Höhe dieser  com.aspose.psd.Rectangle  Struktur. |
| [setLeft(int value)](#setLeft-int-) | Liest oder setzt die x‑Koordinate der linken Kante dieser  com.aspose.psd.Rectangle  Struktur. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| [setRight(int value)](#setRight-int-) | Liest oder setzt die x‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Width  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Liest oder setzt die Größe dieser  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Liest oder setzt die y‑Koordinate der oberen Kante dieser  com.aspose.psd.Rectangle  Struktur. |
| [setWidth(int value)](#setWidth-int-) | Setzt die Breite dieser  com.aspose.psd.Rectangle  Struktur. |
| [setX(int value)](#setX-int-) | Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| [setY(int value)](#setY-int-) | Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| [toString()](#toString--) | Konvertiert die Attribute dieser  com.aspose.psd.Rectangle  in eine menschenlesbare Zeichenkette. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Konvertiert das angegebene  com.aspose.psd.RectangleF  in ein  com.aspose.psd.Rectangle , indem die Werte von  com.aspose.psd.RectangleF  abgeschnitten werden. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Gibt eine  com.aspose.psd.Rectangle  Struktur zurück, die die Vereinigung von zwei  com.aspose.psd.Rectangle  Strukturen enthält. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initialisiert eine neue Instanz der  com.aspose.psd.Rectangle  Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Koordinate der oberen linken Ecke des Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| Breite | int | Die Breite des Rechtecks. |
| Höhe | int | Die Höhe des Rechtecks. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Initialisiert eine neue Instanz der  com.aspose.psd.Rectangle  Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Ein  com.aspose.psd.Point , der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [Size](../../com.aspose.psd/size) | Ein  com.aspose.psd.Size , der die Breite und Höhe des rechteckigen Bereichs darstellt. |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Konvertiert die angegebene  com.aspose.psd.RectangleF  Struktur in eine  com.aspose.psd.Rectangle  Struktur, indem die  com.aspose.psd.RectangleF  Werte auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Die zu konvertierende  com.aspose.psd.RectangleF  Struktur. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.Rectangle  Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der zu testende  com.aspose.psd.Point . |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch  point  dargestellte Punkt innerhalb dieser  com.aspose.psd.Rectangle  Struktur liegt; andernfalls false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bestimmt, ob der durch  rect  dargestellte rechteckige Bereich vollständig innerhalb dieser  com.aspose.psd.Rectangle  Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das zu testende  com.aspose.psd.Rectangle . |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch  rect  dargestellte rechteckige Bereich vollständig innerhalb dieser  com.aspose.psd.Rectangle  Struktur liegt; andernfalls false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.Rectangle  Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch  x  und  y  definierte Punkt innerhalb dieser  com.aspose.psd.Rectangle  Struktur liegt; andernfalls false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob  obj  eine  com.aspose.psd.Rectangle  Struktur mit demselben Ort und derselben Größe wie diese  com.aspose.psd.Rectangle  Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn  obj  eine  com.aspose.psd.Rectangle  Struktur ist und ihre Eigenschaften  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  und  com.aspose.psd.Rectangle.Height  den entsprechenden Eigenschaften dieser  com.aspose.psd.Rectangle  Struktur entsprechen; andernfalls false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Erstellt eine  com.aspose.psd.Rectangle  Struktur mit den angegebenen Kantenpositionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | int | Die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| top | int | Die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| right | int | Die x‑Koordinate der unteren rechten Ecke dieser  com.aspose.psd.Rectangle  Struktur. |
| bottom | int | Die y‑Koordinate der unteren rechten Ecke dieser  com.aspose.psd.Rectangle  Struktur. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Erstellt ein neues  Rectangle  aus zwei angegebenen Punkten. Zwei Vertikale des erstellten  Rectangle  entsprechen den übergebenen  point1  und  point2 . Diese sind typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Der erste  Point  für das neue Rechteck. |
| point2 | [Point](../../com.aspose.psd/point) | Der zweite  Point  für das neue Rechteck. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Liest oder setzt die y‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.Y  und  com.aspose.psd.Rectangle.Height  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist.

**Returns:**
int - Die y‑Koordinate, die die Summe von  com.aspose.psd.Rectangle.Y  und  com.aspose.psd.Rectangle.Height  dieses  com.aspose.psd.Rectangle  ist.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Liest eine neue Instanz der  com.aspose.psd.Rectangle  Struktur, deren Werte für  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  und  com.aspose.psd.Rectangle.Height  auf Null gesetzt sind.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Liest oder setzt die Höhe dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
int - Die Höhe dieser  com.aspose.psd.Rectangle  Struktur.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Liest oder setzt die x‑Koordinate der linken Kante dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
int - Die x‑Koordinate der linken Kante dieser  com.aspose.psd.Rectangle  Struktur.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Liest oder setzt die x‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Width  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist.

**Returns:**
int - Die x‑Koordinate, die die Summe von  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Width  dieses  com.aspose.psd.Rectangle  ist.
### getSize() {#getSize--}
```
public Size getSize()
```


Liest oder setzt die Größe dieser  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Liest oder setzt die y‑Koordinate der oberen Kante dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
int - Der y‑Koordinatenwert der oberen Kante dieser  com.aspose.psd.Rectangle  Struktur.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Liest die Breite dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
int - Die Breite dieser  com.aspose.psd.Rectangle  Struktur.
### getX() {#getX--}
```
public int getX()
```


Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
int - Der x‑Koordinatenwert der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.
### getY() {#getY--}
```
public int getY()
```


Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.

**Returns:**
int - Der y‑Koordinatenwert der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode für diese  com.aspose.psd.Rectangle  Struktur zurück.

**Returns:**
int - Ein Integer, der den Hash‑Code für dieses Rechteck darstellt.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Erstellt und gibt eine aufgeblähte Kopie der angegebenen  com.aspose.psd.Rectangle  Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Die ursprüngliche  com.aspose.psd.Rectangle  Struktur bleibt unverändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das  com.aspose.psd.Rectangle  mit dem gestartet werden soll. Dieses Rechteck wird nicht verändert. |
| x | int | Der Betrag, um den dieses  com.aspose.psd.Rectangle  horizontal aufgebläht wird. |
| y | int | Der Betrag, um den dieses  com.aspose.psd.Rectangle  vertikal aufgebläht wird. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Bläht diese  com.aspose.psd.Rectangle  um den angegebenen Betrag auf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Der Betrag, um den dieses Rechteck aufgebläht wird. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Bläht diese  com.aspose.psd.Rectangle  um den angegebenen Betrag auf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Der Betrag, um den dieses  com.aspose.psd.Rectangle  horizontal aufgebläht wird. |
| Höhe | int | Der Betrag, um den dieses  com.aspose.psd.Rectangle  vertikal aufgebläht wird. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Ersetzt diese  com.aspose.psd.Rectangle  durch die Schnittmenge von ihr selbst und der angegebenen  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das  com.aspose.psd.Rectangle  mit dem geschnitten werden soll. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Gibt eine dritte  com.aspose.psd.Rectangle  Struktur zurück, die die Schnittmenge zweier anderer  com.aspose.psd.Rectangle  Strukturen darstellt. Wenn keine Schnittmenge existiert, wird ein leeres  com.aspose.psd.Rectangle  zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Ein erstes Rechteck zum Schneiden. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Ein zweites Rechteck zum Schneiden. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bestimmt, ob dieses Rechteck mit  rect  schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Das zu testende Rechteck. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn irgendeine Schnittmenge existiert, andernfalls false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Liest einen Wert, der angibt, ob alle numerischen Eigenschaften dieser  com.aspose.psd.Rectangle  den Wert Null haben.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn die Eigenschaften  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Y  dieses  com.aspose.psd.Rectangle  alle den Wert 0 haben; andernfalls false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Liest einen Wert, der angibt, ob dieses  Rectangle  mindestens teilweise sichtbar ist

**Returns:**
boolean -  true  wenn dieses  Rectangle  zumindest teilweise sichtbar ist; andernfalls  false .
### normalize() {#normalize--}
```
public void normalize()
```


Normalisiert das Rechteck, indem es Breite und Höhe positiv macht, links kleiner als rechts und oben kleiner als unten setzt.

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point pos) {#offset-com.aspose.psd.Point-}
```
public void offset(Point pos)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Betrag, um den die Position verschoben wird. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Der horizontale Versatz. |
| y | int | Der vertikale Versatz. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Testet, ob zwei  com.aspose.psd.Rectangle  Strukturen die gleiche Position und Größe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur, die links vom Gleichheitsoperator steht. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur, die rechts vom Gleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn die beiden  com.aspose.psd.Rectangle  Strukturen gleiche  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  und  com.aspose.psd.Rectangle.Height  Eigenschaften besitzen.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Testet, ob sich zwei  com.aspose.psd.Rectangle  Strukturen in Position oder Größe unterscheiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur, die links vom Ungleichheitsoperator steht. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur, die rechts vom Ungleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn einer der Werte  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  oder  com.aspose.psd.Rectangle.Height  der beiden  com.aspose.psd.Rectangle  Strukturen ungleich ist; andernfalls false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Konvertiert das angegebene  com.aspose.psd.RectangleF  in ein  com.aspose.psd.Rectangle , indem die Werte von  com.aspose.psd.RectangleF  auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Das  com.aspose.psd.RectangleF  das konvertiert werden soll. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Liest oder setzt die y‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.Y  und  com.aspose.psd.Rectangle.Height  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der y‑Koordinatenwert, der die Summe von  com.aspose.psd.Rectangle.Y  und  com.aspose.psd.Rectangle.Height  dieses  com.aspose.psd.Rectangle  ist. |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Liest oder setzt die Höhe dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Höhe dieser  com.aspose.psd.Rectangle  Struktur. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Liest oder setzt die x‑Koordinate der linken Kante dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die x-Koordinate der linken Kante dieser  com.aspose.psd.Rectangle  Struktur. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Ein  Point  der die obere linke Ecke dieser  com.aspose.psd.Rectangle  Struktur darstellt. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Liest oder setzt die x‑Koordinate, die die Summe der  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Width  Eigenschaftswerte dieser  com.aspose.psd.Rectangle  Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die x-Koordinate, die die Summe von  com.aspose.psd.Rectangle.X  und  com.aspose.psd.Rectangle.Width  dieses  com.aspose.psd.Rectangle  ist. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Liest oder setzt die Größe dieser  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Ein  com.aspose.psd.Size  der die Breite und Höhe dieser  com.aspose.psd.Rectangle  Struktur repräsentiert. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Liest oder setzt die y‑Koordinate der oberen Kante dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die y-Koordinate der oberen Kante dieser  com.aspose.psd.Rectangle  Struktur. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Setzt die Breite dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Breite dieser  com.aspose.psd.Rectangle  Struktur. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.Rectangle  Struktur. |

### toString() {#toString--}
```
public String toString()
```


Konvertiert die Attribute dieser  com.aspose.psd.Rectangle  in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkette, die die Position, Breite und Höhe dieser  com.aspose.psd.Rectangle  Struktur enthält.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Konvertiert das angegebene  com.aspose.psd.RectangleF  in ein  com.aspose.psd.Rectangle , indem die Werte von  com.aspose.psd.RectangleF  abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Das  com.aspose.psd.RectangleF  das konvertiert werden soll. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Gibt eine  com.aspose.psd.Rectangle  Struktur zurück, die die Vereinigung von zwei  com.aspose.psd.Rectangle  Strukturen enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Ein erstes Rechteck zum Vereinigen. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Ein zweites Rechteck zum Vereinigen. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  structure that bounds the union of the two  com.aspose.psd.Rectangle  structures.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

