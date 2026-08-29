---
title: "RectangleF"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Speichert einen Satz von vier Gleitkommazahlen, die die Position und Größe eines Rechtecks darstellen."
type: docs
weight: 89
url: /de/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Speichert einen Satz von vier Gleitkommazahlen, die die Position und Größe eines Rechtecks darstellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialisiert eine neue Instanz der  com.aspose.psd.RectangleF  Struktur mit dem angegebenen Ort und der Größe. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Initialisiert eine neue Instanz der  com.aspose.psd.RectangleF  Struktur mit dem angegebenen Ort und der Größe. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Bestimmt, ob der durch  rect  dargestellte rechteckige Bereich vollständig innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist. |
| [contains(float x, float y)](#contains-float-float-) | Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Teilt die aktuellen Rechteckwerte, um die vertikalen und horizontalen Skalierungswerte der Transformationsmatrix zu transformieren, und gibt eine neue [RectangleF](../../com.aspose.psd/rectanglef) Instanz mit den Ergebniswerten zurück. |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft, ob  obj  ein  com.aspose.psd.RectangleF  mit demselben Ort und derselben Größe wie dieses  com.aspose.psd.RectangleF  ist. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Erstellt eine  com.aspose.psd.RectangleF  Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Erstellt ein neues  Rectangle  aus zwei angegebenen Punkten. |
| [getBottom()](#getBottom--) | Liest oder setzt die Y-Koordinate, die die Summe von  com.aspose.psd.RectangleF.Y  und  com.aspose.psd.RectangleF.Height  dieser  com.aspose.psd.RectangleF  Struktur ist. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Liefert eine neue Instanz der  com.aspose.psd.RectangleF  Struktur, deren  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  und  com.aspose.psd.RectangleF.Height  Werte auf Null gesetzt sind. |
| [getHeight()](#getHeight--) | Liest oder setzt die Höhe dieser  com.aspose.psd.RectangleF  Struktur. |
| [getLeft()](#getLeft--) | Liest oder setzt die X-Koordinate der linken Kante dieser  com.aspose.psd.RectangleF  Struktur. |
| [getLocation()](#getLocation--) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur. |
| [getRight()](#getRight--) | Liest oder setzt die X-Koordinate, die die Summe von  com.aspose.psd.RectangleF.X  und  com.aspose.psd.RectangleF.Width  dieser  com.aspose.psd.RectangleF  Struktur ist. |
| [getSize()](#getSize--) | Liest oder setzt die Größe dieser  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Liest oder setzt die Y-Koordinate der oberen Kante dieser  com.aspose.psd.RectangleF  Struktur. |
| [getWidth()](#getWidth--) | Liest oder setzt die Breite dieser  com.aspose.psd.RectangleF  Struktur. |
| [getX()](#getX--) | Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur. |
| [getY()](#getY--) | Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur. |
| [hashCode()](#hashCode--) | Liest den Hash‑Code für diese  com.aspose.psd.RectangleF  Struktur. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen  com.aspose.psd.RectangleF  Struktur zurück. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Bläht diese  com.aspose.psd.RectangleF  um den angegebenen Betrag auf. |
| [inflate(float x, float y)](#inflate-float-float-) | Bläht diese  com.aspose.psd.RectangleF  Struktur um den angegebenen Betrag auf. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Ersetzt diese  com.aspose.psd.RectangleF  Struktur durch die Schnittmenge von ihr selbst und der angegebenen  com.aspose.psd.RectangleF  Struktur. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Gibt eine  com.aspose.psd.RectangleF  Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Bestimmt, ob dieses Rechteck mit  rect  schneidet. |
| [isEmpty()](#isEmpty--) | Liest einen Wert, der angibt, ob die Eigenschaft  com.aspose.psd.RectangleF.Width  oder  com.aspose.psd.RectangleF.Height  dieses  com.aspose.psd.RectangleF  den Wert null hat. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Multipliziert die aktuellen Rechteckwerte, um die vertikalen und horizontalen Skalierungswerte der Transformationsmatrix zu verändern, und gibt eine neue [RectangleF](../../com.aspose.psd/rectanglef)-Instanz mit den Ergebniswerten zurück. |
| [normalize()](#normalize--) | Normalisiert das Rechteck, indem es Breite und Höhe positiv macht, links kleiner als rechts und oben kleiner als unten setzt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [offset(float x, float y)](#offset-float-float-) | Passt die Position dieses Rechtecks um den angegebenen Betrag an. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implementiert den Operator /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Prüft, ob zwei  com.aspose.psd.RectangleF  Strukturen die gleiche Position und Größe haben. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Prüft, ob sich zwei  com.aspose.psd.RectangleF  Strukturen in Position oder Größe unterscheiden. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implementiert den Operator \\*. |
| [setBottom(float value)](#setBottom-float-) | Liest oder setzt die Y-Koordinate, die die Summe von  com.aspose.psd.RectangleF.Y  und  com.aspose.psd.RectangleF.Height  dieser  com.aspose.psd.RectangleF  Struktur ist. |
| [setHeight(float value)](#setHeight-float-) | Liest oder setzt die Höhe dieser  com.aspose.psd.RectangleF  Struktur. |
| [setLeft(float value)](#setLeft-float-) | Liest oder setzt die X-Koordinate der linken Kante dieser  com.aspose.psd.RectangleF  Struktur. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur. |
| [setRight(float value)](#setRight-float-) | Liest oder setzt die X-Koordinate, die die Summe von  com.aspose.psd.RectangleF.X  und  com.aspose.psd.RectangleF.Width  dieser  com.aspose.psd.RectangleF  Struktur ist. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Liest oder setzt die Größe dieser  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Liest oder setzt die Y-Koordinate der oberen Kante dieser  com.aspose.psd.RectangleF  Struktur. |
| [setWidth(float value)](#setWidth-float-) | Liest oder setzt die Breite dieser  com.aspose.psd.RectangleF  Struktur. |
| [setX(float value)](#setX-float-) | Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur. |
| [setY(float value)](#setY-float-) | Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur. |
| [toRectangle_internalized()](#toRectangle-internalized--) | Konvertiert ein [RectangleF](../../com.aspose.psd/rectanglef) in eine [Rectangle](../../com.aspose.psd/rectangle)-Struktur mit abgeschnittenen Rechteckwerten. |
| [toString()](#toString--) | Konvertiert die Attribute dieser  com.aspose.psd.RectangleF  in eine menschenlesbare Zeichenkette. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Konvertiert die angegebene  com.aspose.psd.Rectangle  Struktur in eine  com.aspose.psd.RectangleF  Struktur. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Erstellt das kleinste mögliche dritte Rechteck, das beide der beiden Rechtecke, die eine Vereinigung bilden, enthalten kann. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initialisiert eine neue Instanz der  com.aspose.psd.RectangleF  Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x‑Koordinate der oberen linken Ecke des Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| Breite | float | Die Breite des Rechtecks. |
| Höhe | float | Die Höhe des Rechtecks. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialisiert eine neue Instanz der  com.aspose.psd.RectangleF  Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Ein  com.aspose.psd.PointF  der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [SizeF](../../com.aspose.psd/sizef) | Ein  com.aspose.psd.SizeF  der die Breite und Höhe des rechteckigen Bereichs darstellt. |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Das  com.aspose.psd.PointF  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch den  point  Parameter dargestellte Punkt innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist; andernfalls false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Bestimmt, ob der durch  rect  dargestellte rechteckige Bereich vollständig innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Das  com.aspose.psd.RectangleF  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch  rect  dargestellte rechteckige Bereich vollständig innerhalb des durch diese  com.aspose.psd.RectangleF  dargestellten rechteckigen Bereichs liegt; andernfalls false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Bestimmt, ob der angegebene Punkt innerhalb dieser  com.aspose.psd.RectangleF  Struktur enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn der durch  x  und  y  definierte Punkt innerhalb dieser  com.aspose.psd.RectangleF  Struktur liegt; andernfalls false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float |  |
| y | float |  |
| size | [SizeF](../../com.aspose.psd/sizef) |  |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### divideToTransformMatrix_internalized(double[] transformMatrix) {#divideToTransformMatrix-internalized-double---}
```
public final RectangleF divideToTransformMatrix_internalized(double[] transformMatrix)
```


Teilt die aktuellen Rechteckwerte, um die vertikalen und horizontalen Skalierungswerte der Transformationsmatrix zu transformieren, und gibt eine neue [RectangleF](../../com.aspose.psd/rectanglef) Instanz mit den Ergebniswerten zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transformMatrix | double[] | Die Ebenen-Transformationsmatrix. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Prüft, ob  obj  ein  com.aspose.psd.RectangleF  mit demselben Ort und derselben Größe wie dieses  com.aspose.psd.RectangleF  ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Testen. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn  obj  ein  com.aspose.psd.RectangleF  ist und seine X-, Y-, Width- und Height-Eigenschaften den entsprechenden Eigenschaften dieses  com.aspose.psd.RectangleF  entsprechen; andernfalls false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Erstellt eine  com.aspose.psd.RectangleF  Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | float | Die x-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| top | float | Die y-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| right | float | Die x-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |
| bottom | float | Die y-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Erstellt ein neues  Rectangle  aus zwei angegebenen Punkten. Zwei Eckpunkte des erstellten  Rectangle  entsprechen den übergebenen  point1  und  point2 . Diese wären typischerweise die gegenüberliegenden Scheitelpunkte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Der erste  Point  für das neue Rechteck. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Der zweite  Point  für das neue Rechteck. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Liest oder setzt die Y-Koordinate, die die Summe von  com.aspose.psd.RectangleF.Y  und  com.aspose.psd.RectangleF.Height  dieser  com.aspose.psd.RectangleF  Struktur ist.

**Returns:**
float - Die y-Koordinate, die die Summe von  com.aspose.psd.RectangleF.Y  und  com.aspose.psd.RectangleF.Height  dieser  com.aspose.psd.RectangleF  Struktur ist.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Liefert eine neue Instanz der  com.aspose.psd.RectangleF  Struktur, deren  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  und  com.aspose.psd.RectangleF.Height  Werte auf Null gesetzt sind.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Liest oder setzt die Höhe dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
float - Die Höhe dieser  com.aspose.psd.RectangleF  Struktur.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Liest oder setzt die X-Koordinate der linken Kante dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
float - Die x-Koordinate der linken Kante dieser  com.aspose.psd.RectangleF  Struktur.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Liest oder setzt die X-Koordinate, die die Summe von  com.aspose.psd.RectangleF.X  und  com.aspose.psd.RectangleF.Width  dieser  com.aspose.psd.RectangleF  Struktur ist.

**Returns:**
float - Die x-Koordinate, die die Summe von  com.aspose.psd.RectangleF.X  und  com.aspose.psd.RectangleF.Width  dieses  com.aspose.psd.RectangleF  Struktur ist.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Liest oder setzt die Größe dieser  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Liest oder setzt die Y-Koordinate der oberen Kante dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
float - Die y-Koordinate der oberen Kante dieser  com.aspose.psd.RectangleF  Struktur.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Liest oder setzt die Breite dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
float - Die Breite dieser  com.aspose.psd.RectangleF  Struktur.
### getX() {#getX--}
```
public float getX()
```


Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
float - Die x-Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.
### getY() {#getY--}
```
public float getY()
```


Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.

**Returns:**
float - Die y-Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Liest den Hash‑Code für diese  com.aspose.psd.RectangleF  Struktur.

**Returns:**
int - Der Hashcode für dieses  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Erstellt und gibt eine aufgeblähte Kopie der angegebenen  com.aspose.psd.RectangleF  Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Das ursprüngliche Rechteck bleibt unverändert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Das  com.aspose.psd.RectangleF  zum Kopieren. Dieses Rechteck wird nicht verändert. |
| x | float | Der Betrag, um den die Kopie des Rechtecks horizontal aufgebläht wird. |
| y | float | Der Betrag, um den die Kopie des Rechtecks vertikal aufgebläht wird. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Bläht diese  com.aspose.psd.RectangleF  um den angegebenen Betrag auf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Der Betrag, um den dieses Rechteck aufgebläht wird. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Bläht diese  com.aspose.psd.RectangleF  Struktur um den angegebenen Betrag auf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Der Betrag, um den diese  com.aspose.psd.RectangleF  Struktur horizontal aufgebläht wird. |
| y | float | Der Betrag, um den diese  com.aspose.psd.RectangleF  Struktur vertikal aufgebläht wird. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Ersetzt diese  com.aspose.psd.RectangleF  Struktur durch die Schnittmenge von ihr selbst und der angegebenen  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Das Rechteck zum Schneiden. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Gibt eine  com.aspose.psd.RectangleF  Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn keine Schnittmenge existiert, wird ein leeres  com.aspose.psd.RectangleF  zurückgegeben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Ein erstes Rechteck zum Schneiden. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Ein zweites Rechteck zum Schneiden. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bestimmt, ob dieses Rechteck mit  rect  schneidet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Das zu testende Rechteck. |

**Returns:**
boolean - Diese Methode gibt true zurück, wenn irgendeine Schnittmenge existiert.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Liest einen Wert, der angibt, ob die Eigenschaft  com.aspose.psd.RectangleF.Width  oder  com.aspose.psd.RectangleF.Height  dieses  com.aspose.psd.RectangleF  den Wert null hat.

**Returns:**
boolean - Diese Eigenschaft gibt true zurück, wenn die  com.aspose.psd.RectangleF.Width  oder  com.aspose.psd.RectangleF.Height  Eigenschaft dieses  com.aspose.psd.RectangleF  den Wert 0 hat; andernfalls false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Multipliziert die aktuellen Rechteckwerte, um die vertikalen und horizontalen Skalierungswerte der Transformationsmatrix zu verändern, und gibt eine neue [RectangleF](../../com.aspose.psd/rectanglef)-Instanz mit den Ergebniswerten zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| transformMatrix | double[] | Die Ebenen-Transformationsmatrix. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
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




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Der Betrag, um den die Position verschoben wird. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Passt die Position dieses Rechtecks um den angegebenen Betrag an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Der Betrag, um den die Position horizontal verschoben wird. |
| y | float | Der Betrag, um den die Position vertikal verschoben wird. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementiert den Operator /.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das Rechteck. |
| Trennlinie | float | Die Trennlinie. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Prüft, ob zwei  com.aspose.psd.RectangleF  Strukturen die gleiche Position und Größe haben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur, die links vom Gleichheitsoperator steht. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur, die rechts vom Gleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn die beiden angegebenen  com.aspose.psd.RectangleF  Strukturen gleiche  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  und  com.aspose.psd.RectangleF.Height  Eigenschaften haben.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Prüft, ob sich zwei  com.aspose.psd.RectangleF  Strukturen in Position oder Größe unterscheiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur, die links vom Ungleichheitsoperator steht. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Die  com.aspose.psd.RectangleF  Struktur, die rechts vom Ungleichheitsoperator steht. |

**Returns:**
boolean - Dieser Operator gibt true zurück, wenn eine der  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  oder  com.aspose.psd.RectangleF.Height  Eigenschaften der beiden  com.aspose.psd.RectangleF  Strukturen ungleich ist; andernfalls false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementiert den Operator \\*.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Das Rechteck. |
| Multiplikator | float | Der Multiplikator. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Liest oder setzt die Y-Koordinate, die die Summe von  com.aspose.psd.RectangleF.Y  und  com.aspose.psd.RectangleF.Height  dieser  com.aspose.psd.RectangleF  Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Liest oder setzt die Höhe dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Liest oder setzt die X-Koordinate der linken Kante dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Liest oder setzt die Koordinaten der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Liest oder setzt die X-Koordinate, die die Summe von  com.aspose.psd.RectangleF.X  und  com.aspose.psd.RectangleF.Width  dieser  com.aspose.psd.RectangleF  Struktur ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Liest oder setzt die Größe dieser  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Liest oder setzt die Y-Koordinate der oberen Kante dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Liest oder setzt die Breite dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Konvertiert ein [RectangleF](../../com.aspose.psd/rectanglef) in eine [Rectangle](../../com.aspose.psd/rectangle)-Struktur mit abgeschnittenen Rechteckwerten.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Konvertiert die Attribute dieser  com.aspose.psd.RectangleF  in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Eine Zeichenkette, die die Position, Breite und Höhe dieser  com.aspose.psd.RectangleF  Struktur enthält.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Konvertiert die angegebene  com.aspose.psd.Rectangle  Struktur in eine  com.aspose.psd.RectangleF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Die  com.aspose.psd.Rectangle  Struktur, die konvertiert werden soll. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Erstellt das kleinste mögliche dritte Rechteck, das beide der beiden Rechtecke, die eine Vereinigung bilden, enthalten kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Ein erstes Rechteck zum Vereinigen. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Ein zweites Rechteck zum Vereinigen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure that contains both of the two rectangles that form the union.
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

