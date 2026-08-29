---
title: "RectangleF"
second_title: "Aspose.PSD för Java API-referens"
description: "Lagrar en uppsättning av fyra flyttal som representerar positionen och storleken på en rektangel."
type: docs
weight: 89
url: /sv/java/com.aspose.psd/rectanglef/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Lagrar en uppsättning av fyra flyttal som representerar positionen och storleken på en rektangel.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initierar en ny instans av strukturen  com.aspose.psd.RectangleF  med den angivna platsen och storleken. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-) | Initierar en ny instans av strukturen  com.aspose.psd.RectangleF  med den angivna platsen och storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.psd.RectangleF-) |  |
| [contains(PointF point)](#contains-com.aspose.psd.PointF-) | Bestämmer om den angivna punkten finns inom denna  com.aspose.psd.RectangleF  struktur. |
| [contains(RectangleF rect)](#contains-com.aspose.psd.RectangleF-) | Bestämmer om det rektangulära området som representeras av  rect  är helt innehållet i denna  com.aspose.psd.RectangleF  struktur. |
| [contains(float x, float y)](#contains-float-float-) | Bestämmer om den angivna punkten finns inom denna  com.aspose.psd.RectangleF  struktur. |
| [create_internalized(float x, float y, SizeF size)](#create-internalized-float-float-com.aspose.psd.SizeF-) |  |
| [divideToTransformMatrix_internalized(double[] transformMatrix)](#divideToTransformMatrix-internalized-double---) | Dividerar de aktuella rektangelvärdena för att transformera matrisens vertikala och horisontella skalvärden och returnerar en ny [RectangleF](../../com.aspose.psd/rectanglef) instans med resultatvärdena. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om  obj  är en  com.aspose.psd.RectangleF  med samma plats och storlek som denna  com.aspose.psd.RectangleF . |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Skapar en  com.aspose.psd.RectangleF  struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-) | Skapar en ny  Rectangle  från två angivna punkter. |
| [getBottom()](#getBottom--) | Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.RectangleF.Y  och  com.aspose.psd.RectangleF.Height  för denna  com.aspose.psd.RectangleF  struktur. |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av strukturen  com.aspose.psd.RectangleF  som har värdena  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  och  com.aspose.psd.RectangleF.Height  satta till noll. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden på denna  com.aspose.psd.RectangleF  struktur. |
| [getLeft()](#getLeft--) | Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.RectangleF  struktur. |
| [getLocation()](#getLocation--) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.RectangleF  struktur. |
| [getRight()](#getRight--) | Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.RectangleF.X  och  com.aspose.psd.RectangleF.Width  för denna  com.aspose.psd.RectangleF  struktur. |
| [getSize()](#getSize--) | Hämtar eller anger storleken på denna  com.aspose.psd.RectangleF . |
| [getTop()](#getTop--) | Hämtar eller anger y-koordinaten för den övre kanten av detta  com.aspose.psd.RectangleF  struktur. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden på detta  com.aspose.psd.RectangleF  struktur. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur. |
| [hashCode()](#hashCode--) | Hämtar hash‑koden för detta  com.aspose.psd.RectangleF  struktur. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.psd.RectangleF-float-float-) | Skapar och returnerar en uppblåst kopia av den angivna  com.aspose.psd.RectangleF  strukturen. |
| [inflate(SizeF size)](#inflate-com.aspose.psd.SizeF-) | Uppblåser detta  com.aspose.psd.RectangleF  med det angivna beloppet. |
| [inflate(float x, float y)](#inflate-float-float-) | Uppblåser detta  com.aspose.psd.RectangleF  struktur med det angivna beloppet. |
| [intersect(RectangleF rect)](#intersect-com.aspose.psd.RectangleF-) | Ersätter detta  com.aspose.psd.RectangleF  struktur med skärningspunkten mellan sig själv och den angivna  com.aspose.psd.RectangleF  strukturen. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Returnerar en  com.aspose.psd.RectangleF  struktur som representerar skärningspunkten mellan två rektanglar. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.psd.RectangleF-) | Bestämmer om denna rektangel skär med  rect . |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om  com.aspose.psd.RectangleF.Width  eller  com.aspose.psd.RectangleF.Height  egenskapen för detta  com.aspose.psd.RectangleF  har värdet noll. |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) |  |
| [multiplyToTransformMatrix_internalized(double[] transformMatrix)](#multiplyToTransformMatrix-internalized-double---) | Multiplicerar de aktuella rektangelvärdena för att transformera matrisens vertikala och horisontella skalvärden och returnerar en ny [RectangleF](../../com.aspose.psd/rectanglef)‑instans med resultatvärden. |
| [normalize()](#normalize--) | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [offset(PointF pos)](#offset-com.aspose.psd.PointF-) | Justerar placeringen av denna rektangel med det angivna beloppet. |
| [offset(float x, float y)](#offset-float-float-) | Justerar placeringen av denna rektangel med det angivna beloppet. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.psd.RectangleF-float-) | Implementerar operatorn /. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Testar om två  com.aspose.psd.RectangleF  strukturer har lika placering och storlek. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Testar om två  com.aspose.psd.RectangleF  strukturer skiljer sig åt i placering eller storlek. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.psd.RectangleF-float-) | Implementerar operatorn \*. |
| [setBottom(float value)](#setBottom-float-) | Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.RectangleF.Y  och  com.aspose.psd.RectangleF.Height  för denna  com.aspose.psd.RectangleF  struktur. |
| [setHeight(float value)](#setHeight-float-) | Hämtar eller anger höjden på denna  com.aspose.psd.RectangleF  struktur. |
| [setLeft(float value)](#setLeft-float-) | Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.RectangleF  struktur. |
| [setLocation(PointF value)](#setLocation-com.aspose.psd.PointF-) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.RectangleF  struktur. |
| [setRight(float value)](#setRight-float-) | Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.RectangleF.X  och  com.aspose.psd.RectangleF.Width  för denna  com.aspose.psd.RectangleF  struktur. |
| [setSize(SizeF value)](#setSize-com.aspose.psd.SizeF-) | Hämtar eller anger storleken på denna  com.aspose.psd.RectangleF . |
| [setTop(float value)](#setTop-float-) | Hämtar eller anger y-koordinaten för den övre kanten av detta  com.aspose.psd.RectangleF  struktur. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller anger bredden på detta  com.aspose.psd.RectangleF  struktur. |
| [setX(float value)](#setX-float-) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur. |
| [setY(float value)](#setY-float-) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur. |
| [toRectangle_internalized()](#toRectangle-internalized--) | Konverterar en [RectangleF](../../com.aspose.psd/rectanglef) till en [Rectangle](../../com.aspose.psd/rectangle) struktur med trunkerade rektangelvärden. |
| [toString()](#toString--) | Konverterar attributen för detta  com.aspose.psd.RectangleF  till en människoläsbar sträng. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.psd.Rectangle-) | Konverterar den angivna  com.aspose.psd.Rectangle  strukturen till en  com.aspose.psd.RectangleF  struktur. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda av två rektanglar som bildar en union. |
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


Initierar en ny instans av strukturen  com.aspose.psd.RectangleF  med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Den x-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | float | Den y-koordinaten för det övre vänstra hörnet av rektangeln. |
| bredd | float | Bredden på rektangeln. |
| höjd | float | Höjden på rektangeln. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.psd.PointF-com.aspose.psd.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initierar en ny instans av strukturen  com.aspose.psd.RectangleF  med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [PointF](../../com.aspose.psd/pointf) | En  com.aspose.psd.PointF  som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [SizeF](../../com.aspose.psd/sizef) | En  com.aspose.psd.SizeF  som representerar bredden och höjden av det rektangulära området. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(RectangleF that) {#CloneTo-com.aspose.psd.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.psd/rectanglef) |  |

### contains(PointF point) {#contains-com.aspose.psd.PointF-}
```
public boolean contains(PointF point)
```


Bestämmer om den angivna punkten finns inom denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Den  com.aspose.psd.PointF  att testa. |

**Returns:**
boolean - Denna metod returnerar true om punkten som representeras av parametern  point  finns inom denna  com.aspose.psd.RectangleF  struktur; annars false.
### contains(RectangleF rect) {#contains-com.aspose.psd.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Bestämmer om det rektangulära området som representeras av  rect  är helt innehållet i denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  att testa. |

**Returns:**
boolean - Denna metod returnerar true om det rektangulära området som representeras av  rect  är helt innehållet inom det rektangulära området som representeras av denna  com.aspose.psd.RectangleF ; annars false.
### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Bestämmer om den angivna punkten finns inom denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten att testa. |
| y | float | Y-koordinaten för punkten att testa. |

**Returns:**
boolean - Denna metod returnerar true om punkten definierad av  x  och  y  finns inom denna  com.aspose.psd.RectangleF  struktur; annars false.
### create_internalized(float x, float y, SizeF size) {#create-internalized-float-float-com.aspose.psd.SizeF-}
```
public static RectangleF create_internalized(float x, float y, SizeF size)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Dividerar de aktuella rektangelvärdena för att transformera matrisens vertikala och horisontella skalvärden och returnerar en ny [RectangleF](../../com.aspose.psd/rectanglef) instans med resultatvärdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transformMatrix | double[] | Lagertransformmatrisen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with divided values.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om  obj  är en  com.aspose.psd.RectangleF  med samma plats och storlek som denna  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objektet  System.Object  att testa. |

**Returns:**
boolean - Denna metod returnerar true om  obj  är en  com.aspose.psd.RectangleF  och dess X-, Y-, Width- och Height-egenskaper är lika med motsvarande egenskaper för denna  com.aspose.psd.RectangleF ; annars false.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Skapar en  com.aspose.psd.RectangleF  struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | float | X-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| överkant | float | Y-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| höger | float | X-koordinaten för det nedre högra hörnet av det rektangulära området. |
| nedre | float | Y-koordinaten för det nedre högra hörnet av det rektangulära området. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The new  com.aspose.psd.RectangleF  that this method creates.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.psd.PointF-com.aspose.psd.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Skapar en ny  Rectangle  från två angivna punkter. De två hörnen av den skapade  Rectangle  kommer att vara lika med de överförda  point1  och  point2 . Dessa är vanligtvis de motsatta hörnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.psd/pointf) | Den första  Point  för den nya rektangeln. |
| point2 | [PointF](../../com.aspose.psd/pointf) | Den andra  punkten  för den nya rektangeln. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A newly created  Rectangle .
### getBottom() {#getBottom--}
```
public float getBottom()
```


Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.RectangleF.Y  och  com.aspose.psd.RectangleF.Height  för denna  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - Y-koordinaten som är summan av  com.aspose.psd.RectangleF.Y  och  com.aspose.psd.RectangleF.Height  för denna  com.aspose.psd.RectangleF  struktur.
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


Hämtar en ny instans av strukturen  com.aspose.psd.RectangleF  som har värdena  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width  och  com.aspose.psd.RectangleF.Height  satta till noll.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef)
### getHeight() {#getHeight--}
```
public float getHeight()
```


Hämtar eller anger höjden på denna  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - Höjden på denna  com.aspose.psd.RectangleF  struktur.
### getLeft() {#getLeft--}
```
public float getLeft()
```


Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - X-koordinaten för den vänstra kanten av denna  com.aspose.psd.RectangleF  struktur.
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.RectangleF  struktur.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - A  com.aspose.psd.PointF  that represents the upper-left corner of this  com.aspose.psd.RectangleF  structure.
### getRight() {#getRight--}
```
public float getRight()
```


Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.RectangleF.X  och  com.aspose.psd.RectangleF.Width  för denna  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - X-koordinaten som är summan av  com.aspose.psd.RectangleF.X  och  com.aspose.psd.RectangleF.Width  för denna  com.aspose.psd.RectangleF  struktur.
### getSize() {#getSize--}
```
public SizeF getSize()
```


Hämtar eller anger storleken på denna  com.aspose.psd.RectangleF .

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - A  com.aspose.psd.SizeF  that represents the width and height of this  com.aspose.psd.RectangleF  structure.
### getTop() {#getTop--}
```
public float getTop()
```


Hämtar eller anger y-koordinaten för den övre kanten av detta  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - Y-koordinaten för den övre kanten av denna  com.aspose.psd.RectangleF  struktur.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Hämtar eller anger bredden på detta  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - Bredden på denna  com.aspose.psd.RectangleF  struktur.
### getX() {#getX--}
```
public float getX()
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - X-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.RectangleF  struktur.
### getY() {#getY--}
```
public float getY()
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur.

**Returns:**
float - Y-koordinaten för det övre vänstra hörnet av denna  com.aspose.psd.RectangleF  struktur.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hash‑koden för detta  com.aspose.psd.RectangleF  struktur.

**Returns:**
int - Hashkoden för detta  com.aspose.psd.RectangleF .
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.psd.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Skapar och returnerar en uppblåst kopia av den angivna  com.aspose.psd.RectangleF  strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga rektangeln förblir oförändrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Den  com.aspose.psd.RectangleF  som ska kopieras. Denna rektangel är inte modifierad. |
| x | float | Mängden för att blåsa upp kopian av rektangeln horisontellt. |
| y | float | Mängden för att blåsa upp kopian av rektangeln vertikalt. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The inflated  com.aspose.psd.RectangleF .
### inflate(SizeF size) {#inflate-com.aspose.psd.SizeF-}
```
public void inflate(SizeF size)
```


Uppblåser detta  com.aspose.psd.RectangleF  med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Mängden för att blåsa upp denna rektangel. |

### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Uppblåser detta  com.aspose.psd.RectangleF  struktur med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Mängden för att blåsa upp denna  com.aspose.psd.RectangleF  struktur horisontellt. |
| y | float | Mängden för att blåsa upp denna  com.aspose.psd.RectangleF  struktur vertikalt. |

### intersect(RectangleF rect) {#intersect-com.aspose.psd.RectangleF-}
```
public void intersect(RectangleF rect)
```


Ersätter detta  com.aspose.psd.RectangleF  struktur med skärningspunkten mellan sig själv och den angivna  com.aspose.psd.RectangleF  strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln att skära av. |

### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Returnerar en  com.aspose.psd.RectangleF  struktur som representerar skärningen av två rektanglar. Om det inte finns någon skärning, returneras en tom  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | En första rektangel att skära av. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | En andra rektangel att skära av. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - A third  com.aspose.psd.RectangleF  structure the size of which represents the overlapped area of the two specified rectangles.
### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.psd.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bestämmer om denna rektangel skär med  rect .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln att testa. |

**Returns:**
boolean - Denna metod returnerar true om det finns någon skärning.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om  com.aspose.psd.RectangleF.Width  eller  com.aspose.psd.RectangleF.Height  egenskapen för detta  com.aspose.psd.RectangleF  har värdet noll.

**Returns:**
boolean - Denna egenskap returnerar true om  com.aspose.psd.RectangleF.Width  eller  com.aspose.psd.RectangleF.Height  för denna  com.aspose.psd.RectangleF  har värdet noll; annars false.
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.psd/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.psd/rectanglef) |  |

**Returns:**
boolean
### multiplyToTransformMatrix_internalized(double[] transformMatrix) {#multiplyToTransformMatrix-internalized-double---}
```
public final RectangleF multiplyToTransformMatrix_internalized(double[] transformMatrix)
```


Multiplicerar de aktuella rektangelvärdena för att transformera matrisens vertikala och horisontella skalvärden och returnerar en ny [RectangleF](../../com.aspose.psd/rectanglef)‑instans med resultatvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| transformMatrix | double[] | Lagertransformmatrisen. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - Returns a new [RectangleF](../../com.aspose.psd/rectanglef) instance with multiplied values.
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




### offset(PointF pos) {#offset-com.aspose.psd.PointF-}
```
public void offset(PointF pos)
```


Justerar placeringen av denna rektangel med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.psd/pointf) | Mängden för att förskjuta platsen. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Justerar placeringen av denna rektangel med det angivna beloppet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Mängden för att förskjuta platsen horisontellt. |
| y | float | Mängden för att förskjuta platsen vertikalt. |

### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementerar operatorn /.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln. |
| delare | float | Delaren. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Testar om två  com.aspose.psd.RectangleF  strukturer har lika placering och storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Strukturen  com.aspose.psd.RectangleF  som är till vänster om likhetsoperatorn. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Strukturen  com.aspose.psd.RectangleF  som är till höger om likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om de två angivna  com.aspose.psd.RectangleF  strukturerna har lika  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , och  com.aspose.psd.RectangleF.Height  egenskaper.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Testar om två  com.aspose.psd.RectangleF  strukturer skiljer sig åt i placering eller storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.psd/rectanglef) | Strukturen  com.aspose.psd.RectangleF  som är till vänster om olikhetsoperatorn. |
| right | [RectangleF](../../com.aspose.psd/rectanglef) | Strukturen  com.aspose.psd.RectangleF  som är till höger om olikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om någon av  com.aspose.psd.RectangleF.X ,  com.aspose.psd.RectangleF.Y ,  com.aspose.psd.RectangleF.Width , eller  com.aspose.psd.RectangleF.Height  egenskaperna i de två  com.aspose.psd.RectangleF  strukturerna är olika; annars false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.psd.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementerar operatorn \*.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.psd/rectanglef) | Rektangeln. |
| multiplikator | float | Multiplikatorn. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The result of the operator.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Hämtar eller anger y-koordinaten som är summan av  com.aspose.psd.RectangleF.Y  och  com.aspose.psd.RectangleF.Height  för denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Hämtar eller anger höjden på denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Hämtar eller anger x-koordinaten för den vänstra kanten av denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setLocation(PointF value) {#setLocation-com.aspose.psd.PointF-}
```
public void setLocation(PointF value)
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Hämtar eller anger x-koordinaten som är summan av  com.aspose.psd.RectangleF.X  och  com.aspose.psd.RectangleF.Width  för denna  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setSize(SizeF value) {#setSize-com.aspose.psd.SizeF-}
```
public void setSize(SizeF value)
```


Hämtar eller anger storleken på denna  com.aspose.psd.RectangleF .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) |  |

### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Hämtar eller anger y-koordinaten för den övre kanten av detta  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Hämtar eller anger bredden på detta  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av detta  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### toRectangle_internalized() {#toRectangle-internalized--}
```
public final Rectangle toRectangle_internalized()
```


Konverterar en [RectangleF](../../com.aspose.psd/rectanglef) till en [Rectangle](../../com.aspose.psd/rectangle) struktur med trunkerade rektangelvärden.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - Returns a [Rectangle](../../com.aspose.psd/rectangle) structure.
### toString() {#toString--}
```
public String toString()
```


Konverterar attributen för detta  com.aspose.psd.RectangleF  till en människoläsbar sträng.

**Returns:**
java.lang.String - En sträng som innehåller position, bredd och höjd för denna  com.aspose.psd.RectangleF  struktur.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.psd.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Konverterar den angivna  com.aspose.psd.Rectangle  strukturen till en  com.aspose.psd.RectangleF  struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Strukturen  com.aspose.psd.Rectangle  att konvertera. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The  com.aspose.psd.RectangleF  structure that is converted from the specified  com.aspose.psd.Rectangle  structure.
### union(RectangleF a, RectangleF b) {#union-com.aspose.psd.RectangleF-com.aspose.psd.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Skapar den minsta möjliga tredje rektangeln som kan innehålla båda av två rektanglar som bildar en union.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.psd/rectanglef) | Den första rektangeln för förening. |
| b | [RectangleF](../../com.aspose.psd/rectanglef) | Den andra rektangeln för förening. |

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

