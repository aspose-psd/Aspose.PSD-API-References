---
title: "RectangleF-klasse"
type: docs
weight: 3830
url: /nl/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initialiseert een nieuw exemplaar van de RectangleF-klasse |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initialiseert een nieuw exemplaar van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur met de opgegeven locatie en grootte. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initialiseert een nieuw exemplaar van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur met de opgegeven locatie en grootte. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bottom | float | r/w | Haalt op of stelt de y-coördinaat in die de som is van [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) en [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Haalt een nieuw exemplaar op van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) en [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) waarden op nul heeft ingesteld. |
| height | float | r/w | Haalt op of stelt de hoogte in van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of de [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) of [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) eigenschap van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) een waarde van nul heeft. |
| left | float | r/w | Haalt op of stelt de x-coördinaat in van de linkerrand van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Haalt op of stelt de coördinaten in van de linkerbovenhoek van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| right | float | r/w | Haalt op of stelt de x-coördinaat in die de som is van [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) en [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Haalt op of stelt de grootte in van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Haalt op of stelt de y-coördinaat in van de bovenzijde van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| width | float | r/w | Haalt op of stelt de breedte in van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| x | float | r/w | Haalt op of stelt de x-coördinaat in van de linkerbovenhoek van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| y | float | r/w | Haalt op of stelt de y-coördinaat in van de linkerbovenhoek van deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [contains(point)](#contains_point_1) | Bepaalt of het opgegeven punt zich bevindt binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [contains(rect)](#contains_rect_2) | Bepaalt of het rechthoekige gebied dat wordt weergegeven door <paramref name="rect" /> volledig binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zit. |
| [contains(x, y)](#contains_x_y_3) | Bepaalt of het opgegeven punt zich bevindt binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Maakt een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur met de linkerbovenhoek en rechteronderhoek op de opgegeven locaties. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Maakt een nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/) van twee opgegeven punten. De twee hoekpunten van de gemaakte [Rectangle](/psd/python-net/aspose.psd/rectangle/) zijn gelijk aan de meegegeven <paramref name="point1" /> en <paramref name="point2" />. Dit zijn doorgaans de tegenovergestelde hoekpunten. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Maakt en retourneert een opgeblazen kopie van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke rechthoek blijft ongewijzigd. |
| [inflate(size)](#inflate_size_7) | Blaast deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) op met de opgegeven hoeveelheid. |
| [inflate(x, y)](#inflate_x_y_8) | Blaast deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur op met de opgegeven hoeveelheid. |
| [intersect(a, b)](#intersect_a_b_9) | Retourneert een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de intersectie van twee rechthoeken weergeeft. Als er geen intersectie is, wordt een lege [RectangleF](/psd/python-net/aspose.psd/rectanglef/) geretourneerd. |
| [intersect(rect)](#intersect_rect_10) | Vervangt deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur door de intersectie van zichzelf en de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. |
| [intersects_with(rect)](#intersects_with_rect_11) | Bepaalt of deze rechthoek intersecteert met <paramref name="rect" />. |
| normalize() | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder. |
| [offset(pos)](#offset_pos_12) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [offset(x, y)](#offset_x_y_13) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [union(a, b)](#union_a_b_14) | Maakt de kleinst mogelijke derde rechthoek die zowel de twee rechthoeken die een unie vormen, kan bevatten. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initialiseert een nieuw exemplaar van de RectangleF-klasse

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initialiseert een nieuw exemplaar van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur met de opgegeven locatie en grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Een [PointF](/psd/python-net/aspose.psd/pointf/) die de linkerbovenhoek van het rechthoekige gebied weergeeft. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Een [SizeF](/psd/python-net/aspose.psd/sizef/) die de breedte en hoogte van het rechthoekige gebied weergeeft. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initialiseert een nieuw exemplaar van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur met de opgegeven locatie en grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van de linkerbovenhoek van de rechthoek. |
| y | float | De y-coördinaat van de linkerbovenhoek van de rechthoek. |
| width | float | De breedte van de rechthoek. |
| hoogte | float | De hoogte van de rechthoek. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Bepaalt of het opgegeven punt zich bevindt binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De te testen [PointF](/psd/python-net/aspose.psd/pointf/). |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het punt dat wordt weergegeven door de <paramref name="point" /> parameter zich binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur bevindt; anders false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Bepaalt of het rechthoekige gebied dat wordt weergegeven door <paramref name="rect" /> volledig binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur zit.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De te testen [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het rechthoekige gebied dat wordt weergegeven door <paramref name="rect" /> volledig binnen het rechthoekige gebied dat door deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) wordt weergegeven, zit; anders false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Bepaalt of het opgegeven punt zich bevindt binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De x-coördinaat van het te testen punt. |
| y | float | De y-coördinaat van het te testen punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het punt gedefinieerd door <paramref name="x" /> en <paramref name="y" /> zich binnen deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur bevindt; anders false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Maakt een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur met de linkerbovenhoek en rechteronderhoek op de opgegeven locaties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| left | float | De x-coördinaat van de linkerbovenhoek van het rechthoekige gebied. |
| boven | float | De y-coördinaat van de linkerbovenhoek van het rechthoekige gebied. |
| right | float | De x-coördinaat van de rechteronderhoek van het rechthoekige gebied. |
| bottom | float | De y-coördinaat van de rechteronderhoek van het rechthoekige gebied. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De nieuwe [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die deze methode maakt. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Maakt een nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/) van twee opgegeven punten. De twee hoekpunten van de gemaakte [Rectangle](/psd/python-net/aspose.psd/rectangle/) zijn gelijk aan de meegegeven <paramref name="point1" /> en <paramref name="point2" />. Dit zijn doorgaans de tegenovergestelde hoekpunten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Het eerste [Point](/psd/python-net/aspose.psd/point/) voor de nieuwe rechthoek. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Het tweede [Point](/psd/python-net/aspose.psd/point/) voor de nieuwe rechthoek. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een nieuw aangemaakte [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Maakt en retourneert een opgeblazen kopie van de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke rechthoek blijft ongewijzigd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die gekopieerd moet worden. Deze rechthoek wordt niet gewijzigd. |
| x | float | De hoeveelheid om de kopie van de rechthoek horizontaal uit te breiden. |
| y | float | De hoeveelheid om de kopie van de rechthoek verticaal uit te breiden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De opgeblazen [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Blaast deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) op met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | De hoeveelheid om deze rechthoek uit te breiden. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Blaast deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur op met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De hoeveelheid om deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur horizontaal uit te breiden. |
| y | float | De hoeveelheid om deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur verticaal uit te breiden. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Retourneert een [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die de intersectie van twee rechthoeken weergeeft. Als er geen intersectie is, wordt een lege [RectangleF](/psd/python-net/aspose.psd/rectanglef/) geretourneerd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een eerste rechthoek om te intersecteren. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een tweede rechthoek om te intersecteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een derde [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur waarvan de grootte het overlappende gebied van de twee opgegeven rechthoeken weergeeft. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Vervangt deze [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur door de intersectie van zichzelf en de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De rechthoek om te intersecteren. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Bepaalt of deze rechthoek intersecteert met <paramref name="rect" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De rechthoek om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als er enige intersectie is. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | De hoeveelheid om de locatie te verschuiven. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | float | De hoeveelheid om de locatie horizontaal te verschuiven. |
| y | float | De hoeveelheid om de locatie verticaal te verschuiven. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Maakt de kleinst mogelijke derde rechthoek die zowel de twee rechthoeken die een unie vormen, kan bevatten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een eerste rechthoek om te verenigen. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een tweede rechthoek om te verenigen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Een derde [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die beide rechthoeken bevat die de unie vormen. |


