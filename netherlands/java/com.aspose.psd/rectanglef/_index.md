---
title: "RectangleF"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Slaat een set van vier zwevende-komma getallen op die de locatie en grootte van een rechthoek weergeven."
type: docs
weight: 89
url: /nl/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Slaat een set van vier zwevende-komma getallen op die de locatie en grootte van een rechthoek weergeven.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initialiseert een nieuw exemplaar van de  com.aspose.psd.RectangleF  structuur met de opgegeven locatie en grootte. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Initialiseert een nieuw exemplaar van de  com.aspose.psd.RectangleF  structuur met de opgegeven locatie en grootte. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Bepaalt of het opgegeven punt zich bevindt binnen deze  com.aspose.psd.RectangleF  structuur. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Bepaalt of het rechthoekige gebied dat wordt weergegeven door  rect  volledig binnen deze  com.aspose.psd.RectangleF  structuur ligt. |
| [contains(float x, float y)](#contains-float-float-) | Bepaalt of het opgegeven punt zich bevindt binnen deze  com.aspose.psd.RectangleF  structuur. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Deelt de huidige rechthoekwaarden om de verticale en horizontale schaalwaarden van de transformatiematrix te transformeren en retourneert een nieuw [RectangleF](../../com.aspose.psd/rectanglef) exemplaar met de resulterende waarden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Test of  obj  een  com.aspose.psd.RectangleF  is met dezelfde locatie en grootte als deze  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Maakt een  com.aspose.psd.RectangleF  structuur met de linkerbovenhoek en rechteronderhoek op de opgegeven locaties. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Maakt een nieuwe  Rectangle  van twee opgegeven punten. |
| [getBottom()](#getBottom--) | Haalt op of stelt de y-coördinaat in die de som is van  com.aspose.psd.RectangleF.Y  en  com.aspose.psd.RectangleF.Height  van deze  com.aspose.psd.RectangleF  structuur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Haalt een nieuw exemplaar op van de  com.aspose.psd.RectangleF  structuur waarbij  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  en  com.aspose.psd.RectangleF.Height  waarden op nul zijn gezet. |
| [getHeight()](#getHeight--) | Haalt op of stelt de hoogte in van deze  com.aspose.psd.RectangleF  structuur. |
| [getLeft()](#getLeft--) | Haalt op of stelt de x-coördinaat in van de linkerrand van deze  com.aspose.psd.RectangleF  structuur. |
| [getLocation()](#getLocation--) | Haalt op of stelt de coördinaten in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur. |
| [getRight()](#getRight--) | Haalt de x-coördinaat op of stelt deze in, die de som is van  com.aspose.psd.RectangleF.X  en  com.aspose.psd.RectangleF.Width  van deze  com.aspose.psd.RectangleF  structuur. |
| [getSize()](#getSize--) | Haalt de grootte op of stelt deze in van deze  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Haalt de y-coördinaat op of stelt deze in van de bovenrand van deze  com.aspose.psd.RectangleF  structuur. |
| [getWidth()](#getWidth--) | Haalt de breedte op of stelt deze in van deze  com.aspose.psd.RectangleF  structuur. |
| [getX()](#getX--) | Haalt de x-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur. |
| [getY()](#getY--) | Haalt de y-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur. |
| [hashCode()](#hashCode--) | Haalt de hashcode op voor deze  com.aspose.psd.RectangleF  structuur. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Maakt en retourneert een opgeblazen kopie van de opgegeven  com.aspose.psd.RectangleF  structuur. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Vergroot dit  com.aspose.psd.RectangleF  met de opgegeven hoeveelheid. |
| [inflate(float x, float y)](#inflate-float-float-) | Vergroot deze  com.aspose.psd.RectangleF  structuur met de opgegeven hoeveelheid. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Vervangt deze  com.aspose.psd.RectangleF  structuur door de doorsnede van zichzelf en de opgegeven  com.aspose.psd.RectangleF  structuur. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Retourneert een  com.aspose.psd.RectangleF  structuur die de doorsnede van twee rechthoeken weergeeft. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Bepaalt of deze rechthoek intersecteert met  rect . |
| [isEmpty()](#isEmpty--) | Haalt een waarde op die aangeeft of de  com.aspose.psd.RectangleF.Width  of  com.aspose.psd.RectangleF.Height  eigenschap van deze  com.aspose.psd.RectangleF  een waarde van nul heeft. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Vermenigvuldigt de huidige rechthoekwaarden om de verticale en horizontale schaalwaarden van de transformatiematrix te transformeren en retourneert een nieuw [RectangleF](../../com.aspose.psd/rectanglef) exemplaar met de resultaatwaarden. |
| [normalize()](#normalize--) | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [offset(float x, float y)](#offset-float-float-) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implementeert de operator /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Test of twee  com.aspose.psd.RectangleF  structuren gelijke locatie en grootte hebben. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Test of twee  com.aspose.psd.RectangleF  structuren verschillen in locatie of grootte. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implementeert de operator \*. |
| [setBottom(float value)](#setBottom-float-) | Haalt op of stelt de y-coördinaat in die de som is van  com.aspose.psd.RectangleF.Y  en  com.aspose.psd.RectangleF.Height  van deze  com.aspose.psd.RectangleF  structuur. |
| [setHeight(float value)](#setHeight-float-) | Haalt op of stelt de hoogte in van deze  com.aspose.psd.RectangleF  structuur. |
| [setLeft(float value)](#setLeft-float-) | Haalt op of stelt de x-coördinaat in van de linkerrand van deze  com.aspose.psd.RectangleF  structuur. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Haalt op of stelt de coördinaten in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur. |
| [setRight(float value)](#setRight-float-) | Haalt de x-coördinaat op of stelt deze in, die de som is van  com.aspose.psd.RectangleF.X  en  com.aspose.psd.RectangleF.Width  van deze  com.aspose.psd.RectangleF  structuur. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Haalt de grootte op of stelt deze in van deze  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Haalt de y-coördinaat op of stelt deze in van de bovenrand van deze  com.aspose.psd.RectangleF  structuur. |
| [setWidth(float value)](#setWidth-float-) | Haalt de breedte op of stelt deze in van deze  com.aspose.psd.RectangleF  structuur. |
| [setX(float value)](#setX-float-) | Haalt de x-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur. |
| [setY(float value)](#setY-float-) | Haalt de y-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur. |
| [toRectangle_internalized()](#toRectangle-internalized--) | Converteert een [RectangleF](../../com.aspose.psd/rectanglef) naar een [Rectangle](../../com.aspose.psd/rectangle) structuur met afgekorte rechthoekwaarden. |
| [toString()](#toString--) | Converteert de attributen van deze  com.aspose.psd.RectangleF  naar een leesbare tekenreeks. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Converteert de opgegeven  com.aspose.psd.Rectangle  structuur naar een  com.aspose.psd.RectangleF  structuur. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Maakt de kleinste mogelijke derde rechthoek die zowel de twee rechthoeken die een unie vormen, kan bevatten. |
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


Initialiseert een nieuw exemplaar van de  com.aspose.psd.RectangleF  structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van de linkerbovenhoek van de rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de rechthoek. |
| breedte | float | De breedte van de rechthoek. |
| hoogte | float | De hoogte van de rechthoek. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initialiseert een nieuw exemplaar van de  com.aspose.psd.RectangleF  structuur met de opgegeven locatie en grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | Een  com.aspose.psd.PointF  die de linkerbovenhoek van het rechthoekige gebied vertegenwoordigt. |
| size | [SizeF](../../com.aspose.psd/sizef) | Een  com.aspose.psd.SizeF  die de breedte en hoogte van het rechthoekige gebied vertegenwoordigt. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Bepaalt of het opgegeven punt zich bevindt binnen deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | De  com.aspose.psd.PointF  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het punt dat wordt vertegenwoordigd door de  point  parameter zich binnen deze  com.aspose.psd.RectangleF  structuur bevindt; anders false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Bepaalt of het rechthoekige gebied dat wordt weergegeven door  rect  volledig binnen deze  com.aspose.psd.RectangleF  structuur ligt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het rechthoekige gebied dat wordt vertegenwoordigd door  rect  volledig binnen het rechthoekige gebied dat door deze  com.aspose.psd.RectangleF  wordt vertegenwoordigd, ligt; anders false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Bepaalt of het opgegeven punt zich bevindt binnen deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De x-coördinaat van het punt om te testen. |
| y | float | De y-coördinaat van het punt om te testen. |

**Returns:**
boolean - Deze methode retourneert true als het punt gedefinieerd door  x  en  y  zich binnen deze  com.aspose.psd.RectangleF  structuur bevindt; anders false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Deelt de huidige rechthoekwaarden om de verticale en horizontale schaalwaarden van de transformatiematrix te transformeren en retourneert een nieuw [RectangleF](../../com.aspose.psd/rectanglef) exemplaar met de resulterende waarden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| transformMatrix | double[] | De transformatiematrix van de laag. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Test of  obj  een  com.aspose.psd.RectangleF  is met dezelfde locatie en grootte als deze  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het  System.Object  om te testen. |

**Returns:**
boolean - Deze methode retourneert true als  obj  een  com.aspose.psd.RectangleF  is en zijn X-, Y-, Width- en Height-eigenschappen gelijk zijn aan de overeenkomstige eigenschappen van deze  com.aspose.psd.RectangleF ; anders, false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Maakt een  com.aspose.psd.RectangleF  structuur met de linkerbovenhoek en rechteronderhoek op de opgegeven locaties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | float | De x-coördinaat van de linkerbovenhoek van het rechthoekige gebied. |
| boven | float | De y-coördinaat van de linkerbovenhoek van het rechthoekige gebied. |
| rechts | float | De x-coördinaat van de rechteronderhoek van het rechthoekige gebied. |
| onder | float | De y-coördinaat van de rechteronderhoek van het rechthoekige gebied. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Maakt een nieuwe  Rectangle  aan van twee opgegeven punten. Twee hoekpunten van de gemaakte  Rectangle  zullen gelijk zijn aan de meegegeven  point1  en  point2 . Deze zullen doorgaans de tegenovergestelde hoekpunten zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Het eerste  Point  voor de nieuwe rechthoek. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Het tweede  Point  voor de nieuwe rechthoek. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Haalt op of stelt de y-coördinaat in die de som is van  com.aspose.psd.RectangleF.Y  en  com.aspose.psd.RectangleF.Height  van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De y-coördinaat die de som is van  com.aspose.psd.RectangleF.Y  en  com.aspose.psd.RectangleF.Height  van deze  com.aspose.psd.RectangleF  structuur.
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


Haalt een nieuw exemplaar op van de  com.aspose.psd.RectangleF  structuur waarbij  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  en  com.aspose.psd.RectangleF.Height  waarden op nul zijn gezet.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Haalt op of stelt de hoogte in van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De hoogte van deze  com.aspose.psd.RectangleF  structuur.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Haalt op of stelt de x-coördinaat in van de linkerrand van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De x-coördinaat van de linkerrand van deze  com.aspose.psd.RectangleF  structuur.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Haalt op of stelt de coördinaten in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Haalt de x-coördinaat op of stelt deze in, die de som is van  com.aspose.psd.RectangleF.X  en  com.aspose.psd.RectangleF.Width  van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De x-coördinaat die de som is van  com.aspose.psd.RectangleF.X  en  com.aspose.psd.RectangleF.Width  van deze  com.aspose.psd.RectangleF  structuur.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Haalt de grootte op of stelt deze in van deze  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Haalt de y-coördinaat op of stelt deze in van de bovenrand van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De y-coördinaat van de bovenzijde van deze  com.aspose.psd.RectangleF  structuur.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Haalt de breedte op of stelt deze in van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De breedte van deze  com.aspose.psd.RectangleF  structuur.
### getX() {#getX--}
```
public float getX()
```


Haalt de x-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De x-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.
### getY() {#getY--}
```
public float getY()
```


Haalt de y-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
float - De y-coördinaat van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Haalt de hashcode op voor deze  com.aspose.psd.RectangleF  structuur.

**Returns:**
int - De hashcode voor deze  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Maakt en retourneert een opgeblazen kopie van de opgegeven  com.aspose.psd.RectangleF  structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke rechthoek blijft ongewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De  com.aspose.psd.RectangleF  die gekopieerd moet worden. Deze rechthoek wordt niet gewijzigd. |
| x | float | De hoeveelheid om de kopie van de rechthoek horizontaal op te blazen. |
| y | float | De hoeveelheid om de kopie van de rechthoek verticaal op te blazen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Vergroot dit  com.aspose.psd.RectangleF  met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | De hoeveelheid om deze rechthoek op te blazen. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Vergroot deze  com.aspose.psd.RectangleF  structuur met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De hoeveelheid om deze  com.aspose.psd.RectangleF  structuur horizontaal op te blazen. |
| y | float | De hoeveelheid om deze  com.aspose.psd.RectangleF  structuur verticaal op te blazen. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Vervangt deze  com.aspose.psd.RectangleF  structuur door de doorsnede van zichzelf en de opgegeven  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De rechthoek om mee te snijden. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Retourneert een  com.aspose.psd.RectangleF  structuur die de intersectie van twee rechthoeken vertegenwoordigt. Als er geen intersectie is, wordt een lege  com.aspose.psd.RectangleF  geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Een eerste rechthoek om mee te snijden. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Een tweede rechthoek om mee te snijden. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bepaalt of deze rechthoek intersecteert met  rect .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | De rechthoek om te testen. |

**Returns:**
boolean - Deze methode retourneert true als er enige intersectie is.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Haalt een waarde op die aangeeft of de  com.aspose.psd.RectangleF.Width  of  com.aspose.psd.RectangleF.Height  eigenschap van deze  com.aspose.psd.RectangleF  een waarde van nul heeft.

**Returns:**
boolean - Deze eigenschap geeft true terug als de com.aspose.psd.RectangleF.Width of com.aspose.psd.RectangleF.Height eigenschap van deze com.aspose.psd.RectangleF een waarde van nul heeft; anders false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Vermenigvuldigt de huidige rechthoekwaarden om de verticale en horizontale schaalwaarden van de transformatiematrix te transformeren en retourneert een nieuw [RectangleF](../../com.aspose.psd/rectanglef) exemplaar met de resultaatwaarden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| transformMatrix | double[] | De transformatiematrix van de laag. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
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




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | De hoeveelheid om de locatie te verschuiven. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | De hoeveelheid om de locatie horizontaal te verschuiven. |
| y | float | De hoeveelheid om de locatie verticaal te verschuiven. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementeert de operator /.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | De rechthoek. |
| scheidingslijn | float | De scheidingslijn. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Test of twee  com.aspose.psd.RectangleF  structuren gelijke locatie en grootte hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | De com.aspose.psd.RectangleF structuur die zich links van de gelijkheidsoperator bevindt. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | De com.aspose.psd.RectangleF structuur die zich rechts van de gelijkheidsoperator bevindt. |

**Returns:**
boolean - Deze operator geeft true terug als de twee opgegeven com.aspose.psd.RectangleF structuren gelijke com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width en com.aspose.psd.RectangleF.Height eigenschappen hebben.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Test of twee  com.aspose.psd.RectangleF  structuren verschillen in locatie of grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | De com.aspose.psd.RectangleF structuur die zich links van de ongelijkheidsoperator bevindt. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | De com.aspose.psd.RectangleF structuur die zich rechts van de ongelijkheidsoperator bevindt. |

**Returns:**
boolean - Deze operator geeft true terug als een van de com.aspose.psd.RectangleF.X, com.aspose.psd.RectangleF.Y, com.aspose.psd.RectangleF.Width of com.aspose.psd.RectangleF.Height eigenschappen van de twee com.aspose.psd.RectangleF structuren ongelijk zijn; anders false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementeert de operator \*.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | De rechthoek. |
| vermenigvuldiger | float | De vermenigvuldiger. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Haalt op of stelt de y-coördinaat in die de som is van  com.aspose.psd.RectangleF.Y  en  com.aspose.psd.RectangleF.Height  van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Haalt op of stelt de hoogte in van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Haalt op of stelt de x-coördinaat in van de linkerrand van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Haalt op of stelt de coördinaten in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Haalt de x-coördinaat op of stelt deze in, die de som is van  com.aspose.psd.RectangleF.X  en  com.aspose.psd.RectangleF.Width  van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Haalt de grootte op of stelt deze in van deze  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Haalt de y-coördinaat op of stelt deze in van de bovenrand van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Haalt de breedte op of stelt deze in van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Haalt de x-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Haalt de y-coördinaat op of stelt deze in van de linkerbovenhoek van deze  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Converteert een [RectangleF](../../com.aspose.psd/rectanglef) naar een [Rectangle](../../com.aspose.psd/rectangle) structuur met afgekorte rechthoekwaarden.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Converteert de attributen van deze  com.aspose.psd.RectangleF  naar een leesbare tekenreeks.

**Returns:**
java.lang.String - Een string die de positie, breedte en hoogte van deze com.aspose.psd.RectangleF structuur bevat.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Converteert de opgegeven  com.aspose.psd.Rectangle  structuur naar een  com.aspose.psd.RectangleF  structuur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | De com.aspose.psd.Rectangle structuur om te converteren. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Maakt de kleinste mogelijke derde rechthoek die zowel de twee rechthoeken die een unie vormen, kan bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Een eerste rechthoek om te combineren. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Een tweede rechthoek om te combineren. |

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

