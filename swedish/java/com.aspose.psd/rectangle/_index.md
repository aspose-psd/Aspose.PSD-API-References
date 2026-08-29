---
title: "Rektangel"
second_title: "Aspose.PSD för Java API-referens"
description: "Lagrar en uppsättning av fyra heltal som representerar positionen och storleken på en rektangel."
type: docs
weight: 88
url: /sv/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Lagrar en uppsättning av fyra heltal som representerar positionen och storleken på en rektangel.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initierar en ny instans av strukturen  com.aspose.psd.Rectangle  med den angivna platsen och storleken. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Initierar en ny instans av strukturen  com.aspose.psd.Rectangle  med den angivna platsen och storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Konverterar den angivna  com.aspose.psd.RectangleF  strukturen till en  com.aspose.psd.Rectangle  struktur genom att avrunda  com.aspose.psd.RectangleF  värdena till nästa högre heltalsvärde. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Avgör om den angivna punkten finns inom denna  com.aspose.psd.Rectangle  struktur. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Avgör om det rektangulära området som representeras av  rect  är helt innehållet inom denna  com.aspose.psd.Rectangle  struktur. |
| [contains(int x, int y)](#contains-int-int-) | Avgör om den angivna punkten finns inom denna  com.aspose.psd.Rectangle  struktur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om  obj  är en  com.aspose.psd.Rectangle  struktur med samma plats och storlek som denna  com.aspose.psd.Rectangle  struktur. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Skapar en  com.aspose.psd.Rectangle  struktur med de angivna kantpositionerna. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Skapar en ny  Rectangle  från två angivna punkter. |
| [getBottom()](#getBottom--) | Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.Rectangle.Y  och  com.aspose.psd.Rectangle.Height  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av  com.aspose.psd.Rectangle  strukturen som har  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  och  com.aspose.psd.Rectangle.Height  värdena satta till noll. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden på denna  com.aspose.psd.Rectangle  struktur. |
| [getLeft()](#getLeft--) | Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.Rectangle  struktur. |
| [getLocation()](#getLocation--) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| [getRight()](#getRight--) | Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Width  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur. |
| [getSize()](#getSize--) | Hämtar eller anger storleken på denna  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Hämtar eller anger y-koordinaten för den övre kanten av denna  com.aspose.psd.Rectangle  struktur. |
| [getWidth()](#getWidth--) | Hämtar bredden på denna  com.aspose.psd.Rectangle  struktur. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| [hashCode()](#hashCode--) | Returnerar hash‑koden för denna  com.aspose.psd.Rectangle  struktur. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Skapar och returnerar en uppblåst kopia av den angivna  com.aspose.psd.Rectangle  strukturen. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Uppblåser denna  com.aspose.psd.Rectangle  med den angivna mängden. |
| [inflate(int width, int height)](#inflate-int-int-) | Uppblåser denna  com.aspose.psd.Rectangle  med den angivna mängden. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Ersätter denna  com.aspose.psd.Rectangle  med skärningspunkten mellan den själv och den angivna  com.aspose.psd.Rectangle . |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Returnerar en tredje  com.aspose.psd.Rectangle  struktur som representerar skärningspunkten mellan två andra  com.aspose.psd.Rectangle  strukturer. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Bestämmer om denna rektangel skär med  rect . |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om alla numeriska egenskaper för denna  com.aspose.psd.Rectangle  har värdena noll. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Hämtar ett värde som indikerar om denna  Rectangle  är åtminstone delvis synlig |
| [normalize()](#normalize--) | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Justerar placeringen av denna rektangel med det angivna beloppet. |
| [offset(int x, int y)](#offset-int-int-) | Justerar placeringen av denna rektangel med det angivna beloppet. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Testar om två  com.aspose.psd.Rectangle  strukturer har samma plats och storlek. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Testar om två  com.aspose.psd.Rectangle  strukturer skiljer sig i plats eller storlek. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Konverterar den angivna  com.aspose.psd.RectangleF  till en  com.aspose.psd.Rectangle  genom att avrunda  com.aspose.psd.RectangleF‑värdena till närmaste heltalsvärden. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.Rectangle.Y  och  com.aspose.psd.Rectangle.Height  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger höjden på denna  com.aspose.psd.Rectangle  struktur. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.Rectangle  struktur. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| [setRight(int value)](#setRight-int-) | Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Width  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Hämtar eller anger storleken på denna  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger y-koordinaten för den övre kanten av denna  com.aspose.psd.Rectangle  struktur. |
| [setWidth(int value)](#setWidth-int-) | Ställer in bredden på denna  com.aspose.psd.Rectangle  struktur. |
| [setX(int value)](#setX-int-) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| [setY(int value)](#setY-int-) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| [toString()](#toString--) | Konverterar attributen för denna  com.aspose.psd.Rectangle  till en människoläsbar sträng. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Konverterar den angivna  com.aspose.psd.RectangleF  till en  com.aspose.psd.Rectangle  genom att trunkera  com.aspose.psd.RectangleF‑värdena. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Hämtar en  com.aspose.psd.Rectangle  struktur som innehåller unionen av två  com.aspose.psd.Rectangle  strukturer. |
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


Initierar en ny instans av strukturen  com.aspose.psd.Rectangle  med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den x-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | int | Den y-koordinaten för det övre vänstra hörnet av rektangeln. |
| bredd | int | Bredden på rektangeln. |
| höjd | int | Höjden på rektangeln. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Initierar en ny instans av strukturen  com.aspose.psd.Rectangle  med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | En  com.aspose.psd.Point  som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [Size](../../com.aspose.psd/size) | En  com.aspose.psd.Size  som representerar bredden och höjden på det rektangulära området. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Konverterar den angivna  com.aspose.psd.RectangleF  strukturen till en  com.aspose.psd.Rectangle  struktur genom att avrunda  com.aspose.psd.RectangleF  värdena till nästa högre heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  struktur som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Avgör om den angivna punkten finns inom denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Den  com.aspose.psd.Point  som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om punkten som representeras av  point  finns inom denna  com.aspose.psd.Rectangle  struktur; annars false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Avgör om det rektangulära området som representeras av  rect  är helt innehållet inom denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om det rektangulära området som representeras av  rect  är helt innehållet i denna  com.aspose.psd.Rectangle  struktur; annars false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Avgör om den angivna punkten finns inom denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten att testa. |
| y | int | Y-koordinaten för punkten att testa. |

**Returns:**
boolean - Denna metod returnerar true om punkten definierad av  x  och  y  finns inom denna  com.aspose.psd.Rectangle  struktur; annars false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om  obj  är en  com.aspose.psd.Rectangle  struktur med samma plats och storlek som denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet  System.Object  att testa. |

**Returns:**
boolean - Denna metod returnerar true om  obj  är en  com.aspose.psd.Rectangle  struktur och dess  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  och  com.aspose.psd.Rectangle.Height  egenskaper är lika med motsvarande egenskaper i denna  com.aspose.psd.Rectangle  struktur; annars false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Skapar en  com.aspose.psd.Rectangle  struktur med de angivna kantpositionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int | X‑koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| överkant | int | Y‑koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| höger | int | X‑koordinaten för det nedre högra hörnet av denna  com.aspose.psd.Rectangle  struktur. |
| nedre | int | Y‑koordinaten för det nedre högra hörnet av denna  com.aspose.psd.Rectangle  struktur. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Skapar en ny  Rectangle  från två angivna punkter. De två vertikalerna i den skapade  Rectangle  kommer att vara lika med de angivna  point1  och  point2 . Dessa är vanligtvis de motsatta hörnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Den första  Point  för den nya rektangeln. |
| point2 | [Point](../../com.aspose.psd/point) | Den andra  punkten  för den nya rektangeln. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.Rectangle.Y  och  com.aspose.psd.Rectangle.Height  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - Y‑koordinaten som är summan av  com.aspose.psd.Rectangle.Y  och  com.aspose.psd.Rectangle.Height  för denna  com.aspose.psd.Rectangle .
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


Hämtar en ny instans av  com.aspose.psd.Rectangle  strukturen som har  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  och  com.aspose.psd.Rectangle.Height  värdena satta till noll.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger höjden på denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - Höjden på denna  com.aspose.psd.Rectangle  struktur.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - X‑koordinaten för den vänstra kanten av denna  com.aspose.psd.Rectangle  struktur.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Width  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - X‑koordinaten som är summan av  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Width  för denna  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Hämtar eller anger storleken på denna  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Hämtar eller anger y-koordinaten för den övre kanten av denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - Y-koordinaten för den övre kanten av denna  com.aspose.psd.Rectangle  struktur.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bredden på denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - Bredden på denna  com.aspose.psd.Rectangle  struktur.
### getX() {#getX--}
```
public int getX()
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - X-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.
### getY() {#getY--}
```
public int getY()
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - Y-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hash‑koden för denna  com.aspose.psd.Rectangle  struktur.

**Returns:**
int - Ett heltal som representerar hash‑koden för denna rektangel.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Skapar och returnerar en uppblåst kopia av den angivna  com.aspose.psd.Rectangle  strukturen. Kopian uppblåses med den angivna mängden. Den ursprungliga  com.aspose.psd.Rectangle  strukturen förblir oförändrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  att börja med. Denna rektangel modifieras inte. |
| x | int | Mängden att uppblåsa denna  com.aspose.psd.Rectangle  horisontellt. |
| y | int | Mängden att uppblåsa denna  com.aspose.psd.Rectangle  vertikalt. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Uppblåser denna  com.aspose.psd.Rectangle  med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | Mängden för att blåsa upp denna rektangel. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Uppblåser denna  com.aspose.psd.Rectangle  med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Mängden att uppblåsa denna  com.aspose.psd.Rectangle  horisontellt. |
| höjd | int | Mängden att uppblåsa denna  com.aspose.psd.Rectangle  vertikalt. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Ersätter denna  com.aspose.psd.Rectangle  med skärningspunkten mellan den själv och den angivna  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  att skära med. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Returnerar en tredje  com.aspose.psd.Rectangle  struktur som representerar skärningen av två andra  com.aspose.psd.Rectangle  strukturer. Om det inte finns någon skärning returneras en tom  com.aspose.psd.Rectangle.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | En första rektangel att skära av. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | En andra rektangel att skära av. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bestämmer om denna rektangel skär med  rect .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Rektangeln att testa. |

**Returns:**
boolean - Denna metod returnerar true om det finns någon skärning, annars false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om alla numeriska egenskaper för denna  com.aspose.psd.Rectangle  har värdena noll.

**Returns:**
boolean - Denna egenskap returnerar true om egenskaperna  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Y  för denna  com.aspose.psd.Rectangle  alla har värdet noll; annars false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Hämtar ett värde som indikerar om denna  Rectangle  är åtminstone delvis synlig

**Returns:**
boolean -  true  om denna  Rectangle  är åtminstone delvis synlig; annars  false .
### normalize() {#normalize--}
```
public void normalize()
```


Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten.

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


Justerar placeringen av denna rektangel med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Mängd för att förskjuta platsen. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Justerar placeringen av denna rektangel med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den horisontella förskjutningen. |
| y | int | Den vertikala förskjutningen. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Testar om två  com.aspose.psd.Rectangle  strukturer har samma plats och storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  struktur som är till vänster om likhetsoperatorn. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  struktur som är till höger om likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om de två  com.aspose.psd.Rectangle  strukturerna har lika  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  och  com.aspose.psd.Rectangle.Height  egenskaper.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Testar om två  com.aspose.psd.Rectangle  strukturer skiljer sig i plats eller storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  struktur som är till vänster om olikhetsoperatorn. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | Den  com.aspose.psd.Rectangle  struktur som är till höger om olikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om någon av egenskaperna  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  eller  com.aspose.psd.Rectangle.Height  för de två  com.aspose.psd.Rectangle  strukturerna är olika; annars false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Konverterar den angivna  com.aspose.psd.RectangleF  till en  com.aspose.psd.Rectangle  genom att avrunda  com.aspose.psd.RectangleF‑värdena till närmaste heltalsvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.Rectangle.Y  och  com.aspose.psd.Rectangle.Height  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Y-koordinaten som är summan av  com.aspose.psd.Rectangle.Y  och  com.aspose.psd.Rectangle.Height  för denna  com.aspose.psd.Rectangle . |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger höjden på denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Höjden på detta  com.aspose.psd.Rectangle  struktur. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | X-koordinaten för den vänstra kanten av detta  com.aspose.psd.Rectangle  struktur. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | En  Point  som representerar det övre vänstra hörnet av detta  com.aspose.psd.Rectangle  struktur. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Width  egenskapsvärdena för denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | X-koordinaten som är summan av  com.aspose.psd.Rectangle.X  och  com.aspose.psd.Rectangle.Width  för detta  com.aspose.psd.Rectangle . |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Hämtar eller anger storleken på denna  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | En  com.aspose.psd.Size  som representerar bredden och höjden på detta  com.aspose.psd.Rectangle  struktur. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Hämtar eller anger y-koordinaten för den övre kanten av denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Y-koordinaten för den övre kanten av detta  com.aspose.psd.Rectangle  struktur. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ställer in bredden på denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Bredden på detta  com.aspose.psd.Rectangle  struktur. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | X‑koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Y‑koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.Rectangle  struktur. |

### toString() {#toString--}
```
public String toString()
```


Konverterar attributen för denna  com.aspose.psd.Rectangle  till en människoläsbar sträng.

**Returns:**
java.lang.String - En sträng som innehåller positionen, bredden och höjden för detta  com.aspose.psd.Rectangle  struktur.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Konverterar den angivna  com.aspose.psd.RectangleF  till en  com.aspose.psd.Rectangle  genom att trunkera  com.aspose.psd.RectangleF‑värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Hämtar en  com.aspose.psd.Rectangle  struktur som innehåller unionen av två  com.aspose.psd.Rectangle  strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Den första rektangeln för förening. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Den andra rektangeln för förening. |

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

