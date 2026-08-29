---
title: "Rechthoek"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek weergeven."
type: docs
weight: 88
url: /nl/java/com.aspose.psd/rectangle/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Slaat een set van vier gehele getallen op die de locatie en grootte van een rechthoek weergeven.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initialiseert een nieuw exemplaar van de  com.aspose.psd.Rectangle  structuur met de opgegeven locatie en grootte. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-) | Initialiseert een nieuw exemplaar van de  com.aspose.psd.Rectangle  structuur met de opgegeven locatie en grootte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.psd.Rectangle-) |  |
| [ceiling(RectangleF value)](#ceiling-com.aspose.psd.RectangleF-) | Converteert de opgegeven  com.aspose.psd.RectangleF  structuur naar een  com.aspose.psd.Rectangle  structuur door de  com.aspose.psd.RectangleF  waarden af te ronden naar de eerstvolgende hogere gehele getallen. |
| [contains(Point point)](#contains-com.aspose.psd.Point-) | Bepaalt of het opgegeven punt zich binnen deze  com.aspose.psd.Rectangle  structuur bevindt. |
| [contains(Rectangle rect)](#contains-com.aspose.psd.Rectangle-) | Bepaalt of het rechthoekige gebied dat wordt weergegeven door  rect  volledig binnen deze  com.aspose.psd.Rectangle  structuur zit. |
| [contains(int x, int y)](#contains-int-int-) | Bepaalt of het opgegeven punt zich binnen deze  com.aspose.psd.Rectangle  structuur bevindt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of  obj  een  com.aspose.psd.Rectangle  structuur is met dezelfde locatie en grootte als deze  com.aspose.psd.Rectangle  structuur. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Maakt een  com.aspose.psd.Rectangle  structuur met de opgegeven randlocaties. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-) | Maakt een nieuwe  Rectangle  van twee opgegeven punten. |
| [getBottom()](#getBottom--) | Haalt op of stelt de y-coördinaat in die de som is van de  com.aspose.psd.Rectangle.Y  en  com.aspose.psd.Rectangle.Height  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Haalt een nieuw exemplaar op van de  com.aspose.psd.Rectangle  structuur waarvan de  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  en  com.aspose.psd.Rectangle.Height  waarden op nul zijn gezet. |
| [getHeight()](#getHeight--) | Haalt op of stelt de hoogte van deze  com.aspose.psd.Rectangle  structuur in. |
| [getLeft()](#getLeft--) | Haalt op of stelt de x-coördinaat van de linkerrand van deze  com.aspose.psd.Rectangle  structuur in. |
| [getLocation()](#getLocation--) | Haalt op of stelt de coördinaten van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in. |
| [getRight()](#getRight--) | Haalt op of stelt de x-coördinaat in die de som is van de  com.aspose.psd.Rectangle.X  en  com.aspose.psd.Rectangle.Width  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur. |
| [getSize()](#getSize--) | Haalt op of stelt de grootte van deze  com.aspose.psd.Rectangle . |
| [getTop()](#getTop--) | Haalt op of stelt de y-coördinaat van de bovenzijde van deze  com.aspose.psd.Rectangle  structuur in. |
| [getWidth()](#getWidth--) | Haalt de breedte van deze  com.aspose.psd.Rectangle  structuur op. |
| [getX()](#getX--) | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in. |
| [getY()](#getY--) | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor deze  com.aspose.psd.Rectangle  structuur. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.psd.Rectangle-int-int-) | Maakt en retourneert een opgeblazen kopie van de opgegeven  com.aspose.psd.Rectangle  structuur. |
| [inflate(Size size)](#inflate-com.aspose.psd.Size-) | Blaast deze  com.aspose.psd.Rectangle  op met de opgegeven hoeveelheid. |
| [inflate(int width, int height)](#inflate-int-int-) | Blaast deze  com.aspose.psd.Rectangle  op met de opgegeven hoeveelheid. |
| [intersect(Rectangle rect)](#intersect-com.aspose.psd.Rectangle-) | Vervangt deze  com.aspose.psd.Rectangle  door de intersectie van zichzelf en de opgegeven  com.aspose.psd.Rectangle . |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Retourneert een derde  com.aspose.psd.Rectangle  structuur die de intersectie van twee andere  com.aspose.psd.Rectangle  structuren weergeeft. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.psd.Rectangle-) | Bepaalt of deze rechthoek intersecteert met  rect . |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of alle numerieke eigenschappen van deze  com.aspose.psd.Rectangle  nulwaarden hebben. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) |  |
| [isVisible_internalized()](#isVisible-internalized--) | Haalt een waarde op die aangeeft of deze  Rectangle  ten minste gedeeltelijk zichtbaar is |
| [normalize()](#normalize--) | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(Point pos)](#offset-com.aspose.psd.Point-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [offset(int x, int y)](#offset-int-int-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Test of twee  com.aspose.psd.Rectangle  structuren dezelfde locatie en grootte hebben. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Test of twee  com.aspose.psd.Rectangle  structuren verschillen in locatie of grootte. |
| [round(RectangleF value)](#round-com.aspose.psd.RectangleF-) | Converteert de opgegeven  com.aspose.psd.RectangleF  naar een  com.aspose.psd.Rectangle  door de  com.aspose.psd.RectangleF  waarden af te ronden op de dichtstbijzijnde gehele getallen. |
| [setBottom(int value)](#setBottom-int-) | Haalt op of stelt de y-coördinaat in die de som is van de  com.aspose.psd.Rectangle.Y  en  com.aspose.psd.Rectangle.Height  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur. |
| [setHeight(int value)](#setHeight-int-) | Haalt op of stelt de hoogte van deze  com.aspose.psd.Rectangle  structuur in. |
| [setLeft(int value)](#setLeft-int-) | Haalt op of stelt de x-coördinaat van de linkerrand van deze  com.aspose.psd.Rectangle  structuur in. |
| [setLocation(Point value)](#setLocation-com.aspose.psd.Point-) | Haalt op of stelt de coördinaten van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in. |
| [setRight(int value)](#setRight-int-) | Haalt op of stelt de x-coördinaat in die de som is van de  com.aspose.psd.Rectangle.X  en  com.aspose.psd.Rectangle.Width  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur. |
| [setSize(Size value)](#setSize-com.aspose.psd.Size-) | Haalt op of stelt de grootte van deze  com.aspose.psd.Rectangle . |
| [setTop(int value)](#setTop-int-) | Haalt op of stelt de y-coördinaat van de bovenzijde van deze  com.aspose.psd.Rectangle  structuur in. |
| [setWidth(int value)](#setWidth-int-) | Stelt de breedte van deze  com.aspose.psd.Rectangle  structuur in. |
| [setX(int value)](#setX-int-) | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in. |
| [setY(int value)](#setY-int-) | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in. |
| [toString()](#toString--) | Converteert de attributen van deze  com.aspose.psd.Rectangle  naar een leesbare tekenreeks. |
| [truncate(RectangleF value)](#truncate-com.aspose.psd.RectangleF-) | Converteert de opgegeven  com.aspose.psd.RectangleF  naar een  com.aspose.psd.Rectangle  door de  com.aspose.psd.RectangleF  waarden af te kappen. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Haalt een  com.aspose.psd.Rectangle  structuur op die de unie bevat van twee  com.aspose.psd.Rectangle  structuren. |
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


Initialiseert een nieuw exemplaar van de  com.aspose.psd.Rectangle  structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van de linkerbovenhoek van de rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de rechthoek. |
| breedte | int | De breedte van de rechthoek. |
| hoogte | int | De hoogte van de rechthoek. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.psd.Point-com.aspose.psd.Size-}
```
public Rectangle(Point location, Size size)
```


Initialiseert een nieuw exemplaar van de  com.aspose.psd.Rectangle  structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | Een  com.aspose.psd.Point  die de linkerbovenhoek van het rechthoekige gebied vertegenwoordigt. |
| size | [Size](../../com.aspose.psd/size) | Een  com.aspose.psd.Size  die de breedte en hoogte van het rechthoekige gebied vertegenwoordigt. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(Rectangle that) {#CloneTo-com.aspose.psd.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.psd/rectangle) |  |

### ceiling(RectangleF value) {#ceiling-com.aspose.psd.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Converteert de opgegeven  com.aspose.psd.RectangleF  structuur naar een  com.aspose.psd.Rectangle  structuur door de  com.aspose.psd.RectangleF  waarden af te ronden naar de eerstvolgende hogere gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  structuur die moet worden geconverteerd. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a  com.aspose.psd.Rectangle .
### contains(Point point) {#contains-com.aspose.psd.Point-}
```
public boolean contains(Point point)
```


Bepaalt of het opgegeven punt zich binnen deze  com.aspose.psd.Rectangle  structuur bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | De  com.aspose.psd.Point  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het punt vertegenwoordigd door  point  zich binnen deze  com.aspose.psd.Rectangle  structuur bevindt; anders false.
### contains(Rectangle rect) {#contains-com.aspose.psd.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bepaalt of het rechthoekige gebied dat wordt weergegeven door  rect  volledig binnen deze  com.aspose.psd.Rectangle  structuur zit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het rechthoekige gebied vertegenwoordigd door  rect  volledig binnen deze  com.aspose.psd.Rectangle  structuur ligt; anders false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bepaalt of het opgegeven punt zich binnen deze  com.aspose.psd.Rectangle  structuur bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De x-coördinaat van het punt om te testen. |
| y | int | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het punt gedefinieerd door  x  en  y  zich binnen deze  com.aspose.psd.Rectangle  structuur bevindt; anders false.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of  obj  een  com.aspose.psd.Rectangle  structuur is met dezelfde locatie en grootte als deze  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het  System.Object  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als  obj  een  com.aspose.psd.Rectangle  structuur is en zijn  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , en  com.aspose.psd.Rectangle.Height  eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze  com.aspose.psd.Rectangle  structuur; anders false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Maakt een  com.aspose.psd.Rectangle  structuur met de opgegeven randlocaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | int | De x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur. |
| boven | int | De y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur. |
| rechts | int | De x-coördinaat van de rechteronderhoek van deze  com.aspose.psd.Rectangle  structuur. |
| onder | int | De y-coördinaat van de rechteronderhoek van deze  com.aspose.psd.Rectangle  structuur. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The new  com.aspose.psd.Rectangle  that this method creates.
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.psd.Point-com.aspose.psd.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Maakt een nieuwe  Rectangle  aan op basis van twee opgegeven punten. Twee verticale zijden van de gemaakte  Rectangle  zullen gelijk zijn aan de meegegeven  point1  en  point2 . Deze zijn doorgaans de tegenovergestelde hoekpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.psd/point) | Het eerste  Point  voor de nieuwe rechthoek. |
| point2 | [Point](../../com.aspose.psd/point) | Het tweede  Point  voor de nieuwe rechthoek. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public int getBottom()
```


Haalt op of stelt de y-coördinaat in die de som is van de  com.aspose.psd.Rectangle.Y  en  com.aspose.psd.Rectangle.Height  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur.

**Returns:**
int - De y-coördinaat die de som is van  com.aspose.psd.Rectangle.Y  en  com.aspose.psd.Rectangle.Height  van deze  com.aspose.psd.Rectangle .
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


Haalt een nieuw exemplaar op van de  com.aspose.psd.Rectangle  structuur waarvan de  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  en  com.aspose.psd.Rectangle.Height  waarden op nul zijn gezet.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Haalt op of stelt de hoogte van deze  com.aspose.psd.Rectangle  structuur in.

**Returns:**
int - De hoogte van deze  com.aspose.psd.Rectangle  structuur.
### getLeft() {#getLeft--}
```
public int getLeft()
```


Haalt op of stelt de x-coördinaat van de linkerrand van deze  com.aspose.psd.Rectangle  structuur in.

**Returns:**
int - De x-coördinaat van de linkerkant van deze  com.aspose.psd.Rectangle  structuur.
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Haalt op of stelt de coördinaten van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in.

**Returns:**
[Point](../../com.aspose.psd/point) - A  com.aspose.psd.Point  that represents the upper-left corner of this  com.aspose.psd.Rectangle  structure.
### getRight() {#getRight--}
```
public int getRight()
```


Haalt op of stelt de x-coördinaat in die de som is van de  com.aspose.psd.Rectangle.X  en  com.aspose.psd.Rectangle.Width  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur.

**Returns:**
int - De x-coördinaat die de som is van  com.aspose.psd.Rectangle.X  en  com.aspose.psd.Rectangle.Width  van deze  com.aspose.psd.Rectangle .
### getSize() {#getSize--}
```
public Size getSize()
```


Haalt op of stelt de grootte van deze  com.aspose.psd.Rectangle .

**Returns:**
[Size](../../com.aspose.psd/size) - A  com.aspose.psd.Size  that represents the width and height of this  com.aspose.psd.Rectangle  structure.
### getTop() {#getTop--}
```
public int getTop()
```


Haalt op of stelt de y-coördinaat van de bovenzijde van deze  com.aspose.psd.Rectangle  structuur in.

**Returns:**
int - De y-coördinaat van de bovenkant van deze  com.aspose.psd.Rectangle  structuur.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Haalt de breedte van deze  com.aspose.psd.Rectangle  structuur op.

**Returns:**
int - De breedte van deze  com.aspose.psd.Rectangle  structuur.
### getX() {#getX--}
```
public int getX()
```


Haalt op of stelt de x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in.

**Returns:**
int - De x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur.
### getY() {#getY--}
```
public int getY()
```


Haalt op of stelt de y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in.

**Returns:**
int - De y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor deze  com.aspose.psd.Rectangle  structuur.

**Returns:**
int - Een geheel getal dat de hashcode voor deze rechthoek vertegenwoordigt.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Maakt en retourneert een opgeblazen kopie van de opgegeven  com.aspose.psd.Rectangle  structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke  com.aspose.psd.Rectangle  structuur blijft ongewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  waarmee gestart moet worden. Deze rechthoek wordt niet gewijzigd. |
| x | int | De hoeveelheid om deze  com.aspose.psd.Rectangle  horizontaal op te blazen. |
| y | int | De hoeveelheid om deze  com.aspose.psd.Rectangle  verticaal op te blazen. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The inflated  com.aspose.psd.Rectangle .
### inflate(Size size) {#inflate-com.aspose.psd.Size-}
```
public void inflate(Size size)
```


Blaast deze  com.aspose.psd.Rectangle  op met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [Size](../../com.aspose.psd/size) | De hoeveelheid om deze rechthoek op te blazen. |

### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Blaast deze  com.aspose.psd.Rectangle  op met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| breedte | int | De hoeveelheid om deze  com.aspose.psd.Rectangle  horizontaal op te blazen. |
| hoogte | int | De hoeveelheid om deze  com.aspose.psd.Rectangle  verticaal op te blazen. |

### intersect(Rectangle rect) {#intersect-com.aspose.psd.Rectangle-}
```
public void intersect(Rectangle rect)
```


Vervangt deze  com.aspose.psd.Rectangle  door de intersectie van zichzelf en de opgegeven  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  waarmee intersectie moet worden uitgevoerd. |

### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Retourneert een derde  com.aspose.psd.Rectangle  structuur die de intersectie van twee andere  com.aspose.psd.Rectangle  structuren weergeeft. Als er geen intersectie is, wordt een lege  com.aspose.psd.Rectangle  geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Een eerste rechthoek om mee te snijden. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Een tweede rechthoek om mee te snijden. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A  com.aspose.psd.Rectangle  that represents the intersection of  a  and  b .
### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.psd.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bepaalt of deze rechthoek intersecteert met  rect .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De rechthoek om te testen. |

**Returns:**
boolean - Deze methode retourneert true als er een intersectie is, anders false.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Haalt een waarde op die aangeeft of alle numerieke eigenschappen van deze  com.aspose.psd.Rectangle  nulwaarden hebben.

**Returns:**
boolean - Deze eigenschap retourneert true als de  com.aspose.psd.Rectangle.Width ,  com.aspose.psd.Rectangle.Height ,  com.aspose.psd.Rectangle.X , en  com.aspose.psd.Rectangle.Y  eigenschappen van deze  com.aspose.psd.Rectangle  allemaal de waarde nul hebben; anders false.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.psd/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.psd/rectangle) |  |

**Returns:**
boolean
### isVisible_internalized() {#isVisible-internalized--}
```
public boolean isVisible_internalized()
```


Haalt een waarde op die aangeeft of deze  Rectangle  ten minste gedeeltelijk zichtbaar is

**Returns:**
boolean -  true  als deze  Rectangle  ten minste gedeeltelijk zichtbaar is; anders  false .
### normalize() {#normalize--}
```
public void normalize()
```


Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder.

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


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pos | [Point](../../com.aspose.psd/point) | Hoeveelheid om de locatie te verschuiven. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | int | De horizontale offset. |
| y | int | De verticale offset. |

### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Test of twee  com.aspose.psd.Rectangle  structuren dezelfde locatie en grootte hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur die links van de gelijkheidsoperator staat. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur die rechts van de gelijkheidsoperator staat. |

**Returns:**
boolean - Deze operator retourneert true als de twee  com.aspose.psd.Rectangle  structuren gelijke  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width , en  com.aspose.psd.Rectangle.Height  eigenschappen hebben.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Test of twee  com.aspose.psd.Rectangle  structuren verschillen in locatie of grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur die links van de ongelijkheidsoperator staat. |
| right | [Rectangle](../../com.aspose.psd/rectangle) | De  com.aspose.psd.Rectangle  structuur die rechts van de ongelijkheidsoperator staat. |

**Returns:**
boolean - Deze operator retourneert true als een van de  com.aspose.psd.Rectangle.X ,  com.aspose.psd.Rectangle.Y ,  com.aspose.psd.Rectangle.Width  of  com.aspose.psd.Rectangle.Height  eigenschappen van de twee  com.aspose.psd.Rectangle  structuren ongelijk zijn; anders false.
### round(RectangleF value) {#round-com.aspose.psd.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Converteert de opgegeven  com.aspose.psd.RectangleF  naar een  com.aspose.psd.Rectangle  door de  com.aspose.psd.RectangleF  waarden af te ronden op de dichtstbijzijnde gehele getallen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  die geconverteerd moet worden. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Haalt op of stelt de y-coördinaat in die de som is van de  com.aspose.psd.Rectangle.Y  en  com.aspose.psd.Rectangle.Height  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De y-coördinaat die de som is van  com.aspose.psd.Rectangle.Y  en  com.aspose.psd.Rectangle.Height  van deze  com.aspose.psd.Rectangle . |

### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Haalt op of stelt de hoogte van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De hoogte van deze  com.aspose.psd.Rectangle  structuur. |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Haalt op of stelt de x-coördinaat van de linkerrand van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De x-coördinaat van de linkerrand van deze com.aspose.psd.Rectangle-structuur. |

### setLocation(Point value) {#setLocation-com.aspose.psd.Point-}
```
public void setLocation(Point value)
```


Haalt op of stelt de coördinaten van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Point](../../com.aspose.psd/point) | Een Point die de linkerbovenhoek van deze com.aspose.psd.Rectangle-structuur vertegenwoordigt. |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Haalt op of stelt de x-coördinaat in die de som is van de  com.aspose.psd.Rectangle.X  en  com.aspose.psd.Rectangle.Width  eigenschapswaarden van deze  com.aspose.psd.Rectangle  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De x-coördinaat die de som is van com.aspose.psd.Rectangle.X en com.aspose.psd.Rectangle.Width van deze com.aspose.psd.Rectangle. |

### setSize(Size value) {#setSize-com.aspose.psd.Size-}
```
public void setSize(Size value)
```


Haalt op of stelt de grootte van deze  com.aspose.psd.Rectangle .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) | Een com.aspose.psd.Size die de breedte en hoogte van deze com.aspose.psd.Rectangle-structuur vertegenwoordigt. |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Haalt op of stelt de y-coördinaat van de bovenzijde van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De y-coördinaat van de bovenzijde van deze com.aspose.psd.Rectangle-structuur. |

### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Stelt de breedte van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De breedte van deze com.aspose.psd.Rectangle-structuur. |

### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Haalt op of stelt de x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur. |

### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Haalt op of stelt de y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | De y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.Rectangle  structuur. |

### toString() {#toString--}
```
public String toString()
```


Converteert de attributen van deze  com.aspose.psd.Rectangle  naar een leesbare tekenreeks.

**Returns:**
java.lang.String - Een string die de positie, breedte en hoogte van deze com.aspose.psd.Rectangle-structuur bevat.
### truncate(RectangleF value) {#truncate-com.aspose.psd.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Converteert de opgegeven  com.aspose.psd.RectangleF  naar een  com.aspose.psd.Rectangle  door de  com.aspose.psd.RectangleF  waarden af te kappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  die geconverteerd moet worden. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - A new  com.aspose.psd.Rectangle .
### union(Rectangle a, Rectangle b) {#union-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Haalt een  com.aspose.psd.Rectangle  structuur op die de unie bevat van twee  com.aspose.psd.Rectangle  structuren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.psd/rectangle) | Een eerste rechthoek om te combineren. |
| b | [Rectangle](../../com.aspose.psd/rectangle) | Een tweede rechthoek om te combineren. |

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

