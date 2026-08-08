---
title: "Punkt"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan."
type: docs
weight: 82
url: /sv/java/com.aspose.psd/point/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Representerar ett ordnat par av heltals‑x‑ och y‑koordinater som definierar en punkt i ett tvådimensionellt plan.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initierar en ny instans av strukturen  Aspose.Imaging.Point  med de angivna koordinaterna. |
| [Point(Size size)](#Point-com.aspose.psd.Size-) | Initierar en ny instans av strukturen  Aspose.Imaging.Point  från strukturen  Aspose.Imaging.Size . |
| [Point(int dw)](#Point-int-) | Initierar en ny instans av strukturen  Aspose.Imaging.Point  med koordinater som anges av ett heltalsvärde. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [PointFormat_internalized](#PointFormat-internalized) | Representerar punktformatet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Point that)](#CloneTo-com.aspose.psd.Point-) |  |
| [add(Point point, Size size)](#add-com.aspose.psd.Point-com.aspose.psd.Size-) | Lägger till den angivna  Aspose.Imaging.Size  till den angivna  Aspose.Imaging.Point . |
| [ceiling(PointF point)](#ceiling-com.aspose.psd.PointF-) | Konverterar den angivna  Aspose.Imaging.PointF  till en  Aspose.Imaging.Point  genom att avrunda värdena i  Aspose.Imaging.PointF  till nästa högre heltalsvärde. |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om detta  Aspose.Imaging.Point  innehåller samma koordinater som det angivna  System.Object . |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av strukturen  Aspose.Imaging.Point  som har värdena  Aspose.Imaging.Point.X  och  Aspose.Imaging.Point.Y  satta till noll. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för detta  Aspose.Imaging.Point . |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för detta  Aspose.Imaging.Point . |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta  Aspose.Imaging.Point . |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om detta  Aspose.Imaging.Point  är tomt. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point point)](#offset-com.aspose.psd.Point-) | Översätter detta  Aspose.Imaging.Point  med den angivna  Aspose.Imaging.Point . |
| [offset(int dx, int dy)](#offset-int-int-) | Översätter detta  Aspose.Imaging.Point  med den angivna mängden. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-) | Översätter ett  Aspose.Imaging.Point  med en given  Aspose.Imaging.Size . |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-) | Jämför två  Aspose.Imaging.Point  -objekt. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-) | Jämför två  Aspose.Imaging.Point  -objekt. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-) | Översätter ett  Aspose.Imaging.Point  med den negativa av en given  Aspose.Imaging.Size . |
| [round(PointF point)](#round-com.aspose.psd.PointF-) | Konverterar den angivna  Aspose.Imaging.PointF  till ett  Aspose.Imaging.Point  -objekt genom att avrunda  Aspose.Imaging.Point  -värdena till närmaste heltal. |
| [setX(int value)](#setX-int-) | Hämtar eller anger x-koordinaten för detta  Aspose.Imaging.Point . |
| [setY(int value)](#setY-int-) | Hämtar eller anger y-koordinaten för detta  Aspose.Imaging.Point . |
| [subtract(Point point, Size size)](#subtract-com.aspose.psd.Point-com.aspose.psd.Size-) | Returnerar resultatet av att subtrahera den angivna  Aspose.Imaging.Size  från den angivna  Aspose.Imaging.Point . |
| [toString()](#toString--) | Konverterar detta  Aspose.Imaging.Point  till en människoläsbar sträng. |
| [to_PointF(Point point)](#to-PointF-com.aspose.psd.Point-) | Konverterar den angivna  Point  -strukturen till  PointF  -strukturen. |
| [to_Size(Point point)](#to-Size-com.aspose.psd.Point-) | Konverterar den angivna  Aspose.Imaging.Point  -strukturen till en  Aspose.Imaging.Size  -struktur. |
| [truncate(PointF point)](#truncate-com.aspose.psd.PointF-) | Konverterar den angivna  Aspose.Imaging.PointF  till en  Aspose.Imaging.Point  genom att trunkera värdena i  Aspose.Imaging.Point . |
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


Initierar en ny instans av strukturen  Aspose.Imaging.Point  med de angivna koordinaterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den horisontella positionen för punkten. |
| y | int | Den vertikala positionen för punkten. |

### Point(Size size) {#Point-com.aspose.psd.Size-}
```
public Point(Size size)
```


Initierar en ny instans av strukturen  Aspose.Imaging.Point  från strukturen  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Innehåller de nya punktkoordinaterna. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initierar en ny instans av strukturen  Aspose.Imaging.Point  med koordinater som anges av ett heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dw | int | Ett 32-bitars heltal som specificerar koordinaterna för den nya punkten. |

### PointFormat_internalized {#PointFormat-internalized}
```
public static final String PointFormat_internalized
```


Representerar punktformatet.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Point that) {#CloneTo-com.aspose.psd.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Point](../../com.aspose.psd/point) |  |

### add(Point point, Size size) {#add-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point add(Point point, Size size)
```


Lägger till den angivna  Aspose.Imaging.Size  till den angivna  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Aspose.Imaging.Point  att lägga till. |
| size | [Size](../../com.aspose.psd/size) | Den  Aspose.Imaging.Size  att lägga till till  punkten . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the addition operation.
### ceiling(PointF point) {#ceiling-com.aspose.psd.PointF-}
```
public static Point ceiling(PointF point)
```


Konverterar den angivna  Aspose.Imaging.PointF  till en  Aspose.Imaging.Point  genom att avrunda värdena i  Aspose.Imaging.PointF  till nästa högre heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Den  Aspose.Imaging.PointF  att konvertera. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Anger om detta  Aspose.Imaging.Point  innehåller samma koordinater som det angivna  System.Object .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet  System.Object  att testa. |

**Returns:**
boolesk - Sant om  obj  är en  Aspose.Imaging.Point  och har samma koordinater som denna  Aspose.Imaging.Point .
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


Hämtar en ny instans av strukturen  Aspose.Imaging.Point  som har värdena  Aspose.Imaging.Point.X  och  Aspose.Imaging.Point.Y  satta till noll.

**Returns:**
[Point](../../com.aspose.psd/point)
### getX() {#getX--}
```
public int getX()
```


Hämtar eller anger x-koordinaten för detta  Aspose.Imaging.Point .

**Returns:**
int
### getY() {#getY--}
```
public int getY()
```


Hämtar eller anger y-koordinaten för detta  Aspose.Imaging.Point .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta  Aspose.Imaging.Point .

**Returns:**
int - En hashkod för den här instansen, lämplig för användning i hash‑algoritmer och datastrukturer som en hashtabell.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om detta  Aspose.Imaging.Point  är tomt.

**Returns:**
boolesk - Sant om både  Aspose.Imaging.Point.X  och  Aspose.Imaging.Point.Y  är 0; annars falskt.
### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Översätter detta  Aspose.Imaging.Point  med den angivna  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Aspose.Imaging.Point  som används för att förskjuta denna  Aspose.Imaging.Point . |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Översätter detta  Aspose.Imaging.Point  med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | int | Mängden för att förskjuta x-koordinaten. |
| dy | int | Mängden för att förskjuta y-koordinaten. |

### op_Addition(Point point, Size size) {#op-Addition-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Översätter ett  Aspose.Imaging.Point  med en given  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Aspose.Imaging.Point  att översätta. |
| size | [Size](../../com.aspose.psd/size) | En  Aspose.Imaging.Size  som specificerar paret av tal att lägga till koordinaterna för  punkt . |

**Returns:**
[Point](../../com.aspose.psd/point) - The translated  Aspose.Imaging.Point .
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Jämför två  Aspose.Imaging.Point  objekt. Resultatet specificerar om värdena för  Aspose.Imaging.Point.X  och  Aspose.Imaging.Point.Y  egenskaperna hos de två  Aspose.Imaging.Point  objekten är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | En första  Aspose.Imaging.Point  att jämföra. |
| point2 | [Point](../../com.aspose.psd/point) | En andra  Aspose.Imaging.Point  att jämföra. |

**Returns:**
boolesk - Sant om  Aspose.Imaging.Point.X  och  Aspose.Imaging.Point.Y  värdena för  point1  och  point2  är lika; annars falskt.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Jämför två  Aspose.Imaging.Point  objekt. Resultatet specificerar om värdena för  Aspose.Imaging.Point.X  eller  Aspose.Imaging.Point.Y  egenskaperna hos de två  Aspose.Imaging.Point  objekten är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | En första  Aspose.Imaging.Point  att jämföra. |
| point2 | [Point](../../com.aspose.psd/point) | En andra  Aspose.Imaging.Point  att jämföra. |

**Returns:**
boolesk - Sant om värdena för antingen  Aspose.Imaging.Point.X  egenskaperna eller  Aspose.Imaging.Point.Y  egenskaperna för  point1  och  point2  skiljer sig; annars falskt.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Översätter ett  Aspose.Imaging.Point  med den negativa av en given  Aspose.Imaging.Size .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Aspose.Imaging.Point  att översätta. |
| size | [Size](../../com.aspose.psd/size) | En  Aspose.Imaging.Size  som specificerar paret av tal att subtrahera från koordinaterna för  punkt . |

**Returns:**
[Point](../../com.aspose.psd/point) - A  Aspose.Imaging.Point  structure that is translated by the negative of a given  Aspose.Imaging.Size  structure.
### round(PointF point) {#round-com.aspose.psd.PointF-}
```
public static Point round(PointF point)
```


Konverterar den angivna  Aspose.Imaging.PointF  till ett  Aspose.Imaging.Point  -objekt genom att avrunda  Aspose.Imaging.Point  -värdena till närmaste heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Den  Aspose.Imaging.PointF  att konvertera. |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  this method converts to.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Hämtar eller anger x-koordinaten för detta  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Hämtar eller anger y-koordinaten för detta  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### subtract(Point point, Size size) {#subtract-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public static Point subtract(Point point, Size size)
```


Returnerar resultatet av att subtrahera den angivna  Aspose.Imaging.Size  från den angivna  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Aspose.Imaging.Point  att subtraheras från. |
| size | [Size](../../com.aspose.psd/size) | Den  Aspose.Imaging.Size  att subtrahera från  punkten . |

**Returns:**
[Point](../../com.aspose.psd/point) - The  Aspose.Imaging.Point  that is the result of the subtraction operation.
### toString() {#toString--}
```
public String toString()
```


Konverterar detta  Aspose.Imaging.Point  till en människoläsbar sträng.

**Returns:**
java.lang.String - En  System.String  som representerar detta objekt.
### to_PointF(Point point) {#to-PointF-com.aspose.psd.Point-}
```
public static PointF to_PointF(Point point)
```


Konverterar den angivna  Point  -strukturen till  PointF  -strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Point  som ska konverteras. |

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The  PointF  that results from the conversion.
### to_Size(Point point) {#to-Size-com.aspose.psd.Point-}
```
public static Size to_Size(Point point)
```


Konverterar den angivna  Aspose.Imaging.Point  -strukturen till en  Aspose.Imaging.Size  -struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  Aspose.Imaging.Point  som ska konverteras. |

**Returns:**
[Size](../../com.aspose.psd/size) - The  Aspose.Imaging.Size  that results from the conversion.
### truncate(PointF point) {#truncate-com.aspose.psd.PointF-}
```
public static Point truncate(PointF point)
```


Konverterar den angivna  Aspose.Imaging.PointF  till en  Aspose.Imaging.Point  genom att trunkera värdena i  Aspose.Imaging.Point .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Den  Aspose.Imaging.PointF  att konvertera. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

