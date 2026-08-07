---
title: "Punkt"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert."
type: docs
weight: 82
url: /de/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Stellt ein geordnetes Paar von ganzzahligen x‑ und y‑Koordinaten dar, das einen Punkt in einer zweidimensionalen Ebene definiert.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Point  Struktur mit den angegebenen Koordinaten. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Point  Struktur aus der  Aspose.Imaging.Size  Struktur. |
| [Point(int dw)](#Point-int-) | Initialisiert eine neue Instanz der  Aspose.Imaging.Point  Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Stellt das Punktformat dar. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Addiert die angegebene  Aspose.Imaging.Size  zu dem angegebenen  Aspose.Imaging.Point . |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Konvertiert das angegebene  Aspose.Imaging.PointF  in ein  Aspose.Imaging.Point , indem die Werte des  Aspose.Imaging.PointF  auf die nächsthöheren Ganzzahlen gerundet werden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Gibt an, ob dieses  Aspose.Imaging.Point  die gleichen Koordinaten wie das angegebene  System.Object  enthält. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Erhält eine neue Instanz der  Aspose.Imaging.Point  Struktur, deren Werte für  Aspose.Imaging.Point.X  und  Aspose.Imaging.Point.Y  auf Null gesetzt sind. |
| [getX()](#getX--) | Liest oder setzt die x-Koordinate dieses  Aspose.Imaging.Point . |
| [getY()](#getY--) | Liest oder setzt die y-Koordinate dieses  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Gibt einen Hashcode für dieses  Aspose.Imaging.Point  zurück. |
| [isEmpty()](#isEmpty--) | Erhält einen Wert, der angibt, ob dieses  Aspose.Imaging.Point  leer ist. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Verschiebt dieses  Aspose.Imaging.Point  um den angegebenen  Aspose.Imaging.Point . |
| [offset(int dx, int dy)](#offset-int-int-) | Verschiebt dieses  Aspose.Imaging.Point  um den angegebenen Betrag. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Verschiebt ein  Aspose.Imaging.Point  um eine gegebene  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Vergleicht zwei  Aspose.Imaging.Point  Objekte. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Vergleicht zwei  Aspose.Imaging.Point  Objekte. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Verschiebt ein  Aspose.Imaging.Point  um das Negative einer gegebenen  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Konvertiert das angegebene  Aspose.Imaging.PointF  in ein  Aspose.Imaging.Point  Objekt, indem die Werte des  Aspose.Imaging.Point  auf die nächste ganze Zahl gerundet werden. |
| [setX(int value)](#setX-int-) | Liest oder setzt die x-Koordinate dieses  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Liest oder setzt die y-Koordinate dieses  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Gibt das Ergebnis der Subtraktion der angegebenen  Aspose.Imaging.Size  von dem angegebenen  Aspose.Imaging.Point  zurück. |
| [toString()](#toString--) | Konvertiert dieses  Aspose.Imaging.Point  in eine menschenlesbare Zeichenkette. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Konvertiert die angegebene  Point  Struktur in die  PointF  Struktur. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Konvertiert die angegebene  Aspose.Imaging.Point  Struktur in eine  Aspose.Imaging.Size  Struktur. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Konvertiert das angegebene  Aspose.Imaging.PointF  in ein  Aspose.Imaging.Point , indem die Werte des  Aspose.Imaging.Point  abgeschnitten werden. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Point  Struktur mit den angegebenen Koordinaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die horizontale Position des Punktes. |
| y | int | Die vertikale Position des Punktes. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Point  Struktur aus der  Aspose.Imaging.Size  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Enthält die neuen Punktkoordinaten. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialisiert eine neue Instanz der  Aspose.Imaging.Point  Struktur unter Verwendung von Koordinaten, die durch einen ganzzahligen Wert angegeben werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dw | int | Ein 32‑Bit‑Integer, der die Koordinaten für den neuen Punkt angibt. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Stellt das Punktformat dar.

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.psd/point)
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Addiert die angegebene  Aspose.Imaging.Size  zu dem angegebenen  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, zu dem hinzugefügt wird. |
| size | [Size](../../com.aspose.psd/size) | Die Aspose.Imaging.Size, die zum Punkt hinzugefügt wird. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Konvertiert das angegebene  Aspose.Imaging.PointF  in ein  Aspose.Imaging.Point , indem die Werte des  Aspose.Imaging.PointF  auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Der Aspose.Imaging.PointF, der konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Gibt an, ob dieses  Aspose.Imaging.Point  die gleichen Koordinaten wie das angegebene  System.Object  enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das  System.Object  zum Testen. |

**Returns:**
boolean - Wahr, wenn obj ein Aspose.Imaging.Point ist und dieselben Koordinaten wie dieses Aspose.Imaging.Point hat.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Erhält eine neue Instanz der  Aspose.Imaging.Point  Struktur, deren Werte für  Aspose.Imaging.Point.X  und  Aspose.Imaging.Point.Y  auf Null gesetzt sind.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Liest oder setzt die x-Koordinate dieses  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Liest oder setzt die y-Koordinate dieses  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt einen Hashcode für dieses  Aspose.Imaging.Point  zurück.

**Returns:**
int - Ein Hashcode für diese Instanz, geeignet für die Verwendung in Hash‑Algorithmen und Datenstrukturen wie einer Hashtabelle.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Erhält einen Wert, der angibt, ob dieses  Aspose.Imaging.Point  leer ist.

**Returns:**
boolean - Wahr, wenn sowohl Aspose.Imaging.Point.X als auch Aspose.Imaging.Point.Y 0 sind; andernfalls falsch.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.psd/point) |  |
| obj2 | [Point](../../com.aspose.psd/point) |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### offset(Point point) {#offset-com.aspose.psd.Point-}
```
public void offset(Point point)
```


Verschiebt dieses  Aspose.Imaging.Point  um den angegebenen  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, der verwendet wird, um diesen Aspose.Imaging.Point zu versetzen. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Verschiebt dieses  Aspose.Imaging.Point  um den angegebenen Betrag.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dx | int | Der Betrag, um den die x‑Koordinate zu versetzen ist. |
| dy | int | Der Betrag, um den die y‑Koordinate zu versetzen ist. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Verschiebt ein  Aspose.Imaging.Point  um eine gegebene  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, der übersetzt werden soll. |
| size | [Size](../../com.aspose.psd/size) | Eine Aspose.Imaging.Size, die das Zahlenpaar angibt, das zu den Koordinaten des Punktes hinzugefügt wird. |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Vergleicht zwei Aspose.Imaging.Point‑Objekte. Das Ergebnis gibt an, ob die Werte der Eigenschaften Aspose.Imaging.Point.X und Aspose.Imaging.Point.Y der beiden Aspose.Imaging.Point‑Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Ein erstes Aspose.Imaging.Point zum Vergleichen. |
| point2 | [Point](../../com.aspose.psd/point) | Ein zweites Aspose.Imaging.Point zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn die Werte von Aspose.Imaging.Point.X und Aspose.Imaging.Point.Y von point1 und point2 gleich sind; andernfalls falsch.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Vergleicht zwei Aspose.Imaging.Point‑Objekte. Das Ergebnis gibt an, ob die Werte der Eigenschaften Aspose.Imaging.Point.X oder Aspose.Imaging.Point.Y der beiden Aspose.Imaging.Point‑Objekte ungleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Ein erstes Aspose.Imaging.Point zum Vergleichen. |
| point2 | [Point](../../com.aspose.psd/point) | Ein zweites Aspose.Imaging.Point zum Vergleichen. |

**Returns:**
boolean - Wahr, wenn die Werte entweder der Aspose.Imaging.Point.X‑Eigenschaften oder der Aspose.Imaging.Point.Y‑Eigenschaften von point1 und point2 unterschiedlich sind; andernfalls falsch.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Verschiebt ein  Aspose.Imaging.Point  um das Negative einer gegebenen  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, der übersetzt werden soll. |
| size | [Size](../../com.aspose.psd/size) | Eine Aspose.Imaging.Size, die das Zahlenpaar angibt, das von den Koordinaten des Punktes subtrahiert wird. |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Konvertiert das angegebene  Aspose.Imaging.PointF  in ein  Aspose.Imaging.Point  Objekt, indem die Werte des  Aspose.Imaging.Point  auf die nächste ganze Zahl gerundet werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Der Aspose.Imaging.PointF, der konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Liest oder setzt die x-Koordinate dieses  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Liest oder setzt die y-Koordinate dieses  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Gibt das Ergebnis der Subtraktion der angegebenen  Aspose.Imaging.Size  von dem angegebenen  Aspose.Imaging.Point  zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, von dem subtrahiert wird. |
| size | [Size](../../com.aspose.psd/size) | Die Aspose.Imaging.Size, die vom Punkt subtrahiert wird. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Konvertiert dieses  Aspose.Imaging.Point  in eine menschenlesbare Zeichenkette.

**Returns:**
java.lang.String - Ein  System.String  der diese Instanz darstellt.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Konvertiert die angegebene  Point  Struktur in die  PointF  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Point, der konvertiert werden soll. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Konvertiert die angegebene  Aspose.Imaging.Point  Struktur in eine  Aspose.Imaging.Size  Struktur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Der Aspose.Imaging.Point, der konvertiert werden soll. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Konvertiert das angegebene  Aspose.Imaging.PointF  in ein  Aspose.Imaging.Point , indem die Werte des  Aspose.Imaging.Point  abgeschnitten werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Der Aspose.Imaging.PointF, der konvertiert werden soll. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
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

