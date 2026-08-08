---
title: "Point"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een geordend paar van gehele x- en y-coördinaten voor dat een punt in een tweedimensionaal vlak definieert."
type: docs
weight: 82
url: /nl/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Stelt een geordend paar van gehele x- en y-coördinaten voor dat een punt in een tweedimensionaal vlak definieert.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Point  structuur met de opgegeven coördinaten. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Point  structuur vanuit de  Aspose.Imaging.Size  structuur. |
| [Point(int dw)](#Point-int-) | Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Point  structuur met coördinaten gespecificeerd door een geheel getal. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Geeft het puntformaat weer. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Voegt de opgegeven  Aspose.Imaging.Size  toe aan het opgegeven  Aspose.Imaging.Point . |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Converteert de opgegeven  Aspose.Imaging.PointF  naar een  Aspose.Imaging.Point  door de waarden van de  Aspose.Imaging.PointF  af te ronden naar de eerstvolgende hogere gehele getallen. |
| [equals(Object obj)](#equals-java.lang.Object-) | Specificeert of dit  Aspose.Imaging.Point  dezelfde coördinaten bevat als het opgegeven  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Haalt een nieuw exemplaar op van de  Aspose.Imaging.Point  structuur waarvan  Aspose.Imaging.Point.X  en  Aspose.Imaging.Point.Y  waarden op nul zijn ingesteld. |
| [getX()](#getX--) | Haalt op of stelt de x-coördinaat van dit  Aspose.Imaging.Point  in. |
| [getY()](#getY--) | Haalt op of stelt de y-coördinaat van dit  Aspose.Imaging.Point  in. |
| [hashCode()](#hashCode--) | Retourneert een hashcode voor dit  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of dit  Aspose.Imaging.Point  leeg is. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Verschuift dit  Aspose.Imaging.Point  met het opgegeven  Aspose.Imaging.Point . |
| [offset(int dx, int dy)](#offset-int-int-) | Verschuift dit  Aspose.Imaging.Point  met de opgegeven hoeveelheid. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Verschuift een  Aspose.Imaging.Point  met een gegeven  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Vergelijkt twee  Aspose.Imaging.Point  objecten. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Vergelijkt twee  Aspose.Imaging.Point  objecten. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Verschuift een  Aspose.Imaging.Point  met het negatieve van een gegeven  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Converteert de opgegeven  Aspose.Imaging.PointF  naar een  Aspose.Imaging.Point  object door de  Aspose.Imaging.Point  waarden af te ronden naar het dichtstbijzijnde gehele getal. |
| [setX(int value)](#setX-int-) | Haalt op of stelt de x-coördinaat van dit  Aspose.Imaging.Point  in. |
| [setY(int value)](#setY-int-) | Haalt op of stelt de y-coördinaat van dit  Aspose.Imaging.Point  in. |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Retourneert het resultaat van het aftrekken van de opgegeven  Aspose.Imaging.Size  van het opgegeven  Aspose.Imaging.Point . |
| [toString()](#toString--) | Converteert dit  Aspose.Imaging.Point  naar een menselijk leesbare tekenreeks. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Converteert de opgegeven  Point  structuur naar de  PointF  structuur. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Converteert de opgegeven  Aspose.Imaging.Point  structuur naar een  Aspose.Imaging.Size  structuur. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Converteert de opgegeven  Aspose.Imaging.PointF  naar een  Aspose.Imaging.Point  door de waarden van de  Aspose.Imaging.Point  af te kappen. |
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


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Point  structuur met de opgegeven coördinaten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De horizontale positie van het punt. |
| y | int | De verticale positie van het punt. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Point  structuur vanuit de  Aspose.Imaging.Size  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Bevat de nieuwe puntcoördinaten. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initialiseert een nieuw exemplaar van de  Aspose.Imaging.Point  structuur met coördinaten gespecificeerd door een geheel getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dw | int | Een 32-bits geheel getal dat de coördinaten voor het nieuwe punt specificeert. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Geeft het puntformaat weer.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Voegt de opgegeven  Aspose.Imaging.Size  toe aan het opgegeven  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Het  Aspose.Imaging.Point  om aan toe te voegen. |
| size | [Size](../../com.aspose.psd/size) | De  Aspose.Imaging.Size  om toe te voegen aan het  punt . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Converteert de opgegeven  Aspose.Imaging.PointF  naar een  Aspose.Imaging.Point  door de waarden van de  Aspose.Imaging.PointF  af te ronden naar de eerstvolgende hogere gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | De  Aspose.Imaging.PointF  om te converteren. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Specificeert of dit  Aspose.Imaging.Point  dezelfde coördinaten bevat als het opgegeven  System.Object .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het  System.Object  om te testen. |

**Returns:**
boolean - Waar als  obj  een  Aspose.Imaging.Point  is en dezelfde coördinaten heeft als dit  Aspose.Imaging.Point .
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


Haalt een nieuw exemplaar op van de  Aspose.Imaging.Point  structuur waarvan  Aspose.Imaging.Point.X  en  Aspose.Imaging.Point.Y  waarden op nul zijn ingesteld.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Haalt op of stelt de x-coördinaat van dit  Aspose.Imaging.Point  in.

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Haalt op of stelt de y-coördinaat van dit  Aspose.Imaging.Point  in.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert een hashcode voor dit  Aspose.Imaging.Point .

**Returns:**
int - Een hashcode voor deze instantie, geschikt voor gebruik in hash-algoritmen en datastructuren zoals een hashtabel.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Haalt een waarde op die aangeeft of dit  Aspose.Imaging.Point  leeg is.

**Returns:**
boolean - Waar als zowel  Aspose.Imaging.Point.X  als  Aspose.Imaging.Point.Y  0 zijn; anders, false.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Verschuift dit  Aspose.Imaging.Point  met het opgegeven  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  Aspose.Imaging.Point  gebruikt om dit  Aspose.Imaging.Point  te verschuiven. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Verschuift dit  Aspose.Imaging.Point  met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dx | int | De hoeveelheid om de x-coördinaat te verschuiven. |
| dy | int | De hoeveelheid om de y-coördinaat te verschuiven. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Verschuift een  Aspose.Imaging.Point  met een gegeven  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  Aspose.Imaging.Point  om te vertalen. |
| size | [Size](../../com.aspose.psd/size) | Een  Aspose.Imaging.Size  die het paar getallen specificeert om toe te voegen aan de coördinaten van het  punt . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Vergelijkt twee  Aspose.Imaging.Point  objecten. Het resultaat geeft aan of de waarden van de  Aspose.Imaging.Point.X  en  Aspose.Imaging.Point.Y  eigenschappen van de twee  Aspose.Imaging.Point  objecten gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Een eerste  Aspose.Imaging.Point  om te vergelijken. |
| point2 | [Point](../../com.aspose.psd/point) | Een tweede  Aspose.Imaging.Point  om te vergelijken. |

**Returns:**
boolean - Waar als de  Aspose.Imaging.Point.X  en  Aspose.Imaging.Point.Y  waarden van  point1  en  point2  gelijk zijn; anders, false.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Vergelijkt twee  Aspose.Imaging.Point  objecten. Het resultaat geeft aan of de waarden van de  Aspose.Imaging.Point.X  of  Aspose.Imaging.Point.Y  eigenschappen van de twee  Aspose.Imaging.Point  objecten ongelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Een eerste  Aspose.Imaging.Point  om te vergelijken. |
| point2 | [Point](../../com.aspose.psd/point) | Een tweede  Aspose.Imaging.Point  om te vergelijken. |

**Returns:**
boolean - Waar als de waarden van ofwel de  Aspose.Imaging.Point.X  eigenschap of de  Aspose.Imaging.Point.Y  eigenschap van  point1  en  point2  verschillen; anders, false.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Verschuift een  Aspose.Imaging.Point  met het negatieve van een gegeven  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  Aspose.Imaging.Point  om te vertalen. |
| size | [Size](../../com.aspose.psd/size) | Een  Aspose.Imaging.Size  die het paar getallen specificeert om af te trekken van de coördinaten van het  punt . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Converteert de opgegeven  Aspose.Imaging.PointF  naar een  Aspose.Imaging.Point  object door de  Aspose.Imaging.Point  waarden af te ronden naar het dichtstbijzijnde gehele getal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | De  Aspose.Imaging.PointF  om te converteren. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Haalt op of stelt de x-coördinaat van dit  Aspose.Imaging.Point  in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Haalt op of stelt de y-coördinaat van dit  Aspose.Imaging.Point  in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Retourneert het resultaat van het aftrekken van de opgegeven  Aspose.Imaging.Size  van het opgegeven  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  Aspose.Imaging.Point  waarvan afgetrokken wordt. |
| size | [Size](../../com.aspose.psd/size) | De  Aspose.Imaging.Size  om af te trekken van het  punt . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Converteert dit  Aspose.Imaging.Point  naar een menselijk leesbare tekenreeks.

**Returns:**
java.lang.String - Een  System.String  die deze instantie vertegenwoordigt.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Converteert de opgegeven  Point  structuur naar de  PointF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  Point  om te converteren. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Converteert de opgegeven  Aspose.Imaging.Point  structuur naar een  Aspose.Imaging.Size  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  Aspose.Imaging.Point  om te converteren. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Converteert de opgegeven  Aspose.Imaging.PointF  naar een  Aspose.Imaging.Point  door de waarden van de  Aspose.Imaging.Point  af te kappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | De  Aspose.Imaging.PointF  om te converteren. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

