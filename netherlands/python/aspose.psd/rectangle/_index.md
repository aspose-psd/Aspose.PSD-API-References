---
title: "Rectangle Klasse"
type: docs
weight: 3810
url: /nl/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initialiseert een nieuw exemplaar van de Rectangle-klasse |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initialiseert een nieuw exemplaar van de [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur met de opgegeven locatie en grootte. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initialiseert een nieuw exemplaar van de [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur met de opgegeven locatie en grootte. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bottom | int | r/w | Haalt op of stelt de y-coördinaat in die de som is van de [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) en [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) eigenschapswaarden van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Haalt een nieuw exemplaar op van de [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur waarvan de [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) en [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) waarden op nul zijn ingesteld. |
| height | int | r/w | Haalt op of stelt de hoogte van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of alle numerieke eigenschappen van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur nulwaarden hebben. |
| left | int | r/w | Haalt op of stelt de x-coördinaat van de linkerrand van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Haalt op of stelt de coördinaten van de linkerbovenhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| right | int | r/w | Haalt op of stelt de x-coördinaat in die de som is van de [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) en [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) eigenschapswaarden van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Haalt op of stelt de grootte van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| top | int | r/w | Haalt op of stelt de y-coördinaat van de bovenzijde van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| width | int | r/w | Haalt op of stelt de breedte van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| x | int | r/w | Haalt op of stelt de x-coördinaat van de linkerbovenhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
| y | int | r/w | Haalt op of stelt de y-coördinaat van de linkerbovenhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Converteert de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur naar een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur door de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) waarden af te ronden naar de eerstvolgende hogere gehele getallen. |
| [contains(point)](#contains_point_2) | Bepaalt of het opgegeven punt zich binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur bevindt. |
| [contains(rect)](#contains_rect_3) | Bepaalt of het rechthoekige gebied dat wordt weergegeven door <paramref name="rect" /> volledig binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur ligt. |
| [contains(x, y)](#contains_x_y_4) | Bepaalt of het opgegeven punt zich binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur bevindt. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Maakt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur met de opgegeven randlocaties. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Maakt een nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/) aan de hand van twee opgegeven punten. De twee verticale zijden van de gemaakte [Rectangle](/psd/python-net/aspose.psd/rectangle/) zullen gelijk zijn aan de meegegeven <paramref name="point1" /> en <paramref name="point2" />. Deze zijn doorgaans de tegenovergestelde hoekpunten. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Maakt en retourneert een opgeblazen kopie van de opgegeven [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur blijft ongewijzigd. |
| [inflate(size)](#inflate_size_8) | Vergroot dit [Rectangle](/psd/python-net/aspose.psd/rectangle/) met de opgegeven hoeveelheid. |
| [inflate(width, height)](#inflate_width_height_9) | Vergroot dit [Rectangle](/psd/python-net/aspose.psd/rectangle/) met de opgegeven hoeveelheid. |
| [intersect(a, b)](#intersect_a_b_10) | Retourneert een derde [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de intersectie van twee andere [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren weergeeft. Als er geen intersectie is, wordt een lege [Rectangle](/psd/python-net/aspose.psd/rectangle/) geretourneerd. |
| [intersect(rect)](#intersect_rect_11) | Vervangt dit [Rectangle](/psd/python-net/aspose.psd/rectangle/) door de intersectie van zichzelf en de opgegeven [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_12) | Bepaalt of deze rechthoek intersecteert met <paramref name="rect" />. |
| normalize() | Normaliseert de rechthoek door de breedte en hoogte positief te maken, links kleiner dan rechts en boven kleiner dan onder. |
| [offset(pos)](#offset_pos_13) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [offset(x, y)](#offset_x_y_14) | Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid. |
| [round(value)](#round_value_15) | Converteert de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) naar een [Rectangle](/psd/python-net/aspose.psd/rectangle/) door de waarden van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) af te ronden op de dichtstbijzijnde gehele getallen. |
| [truncate(value)](#truncate_value_16) | Converteert de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) naar een [Rectangle](/psd/python-net/aspose.psd/rectangle/) door de waarden van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) af te kappen. |
| [union(a, b)](#union_a_b_17) | Haalt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur op die de unie van twee [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren bevat. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initialiseert een nieuw exemplaar van de Rectangle-klasse

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initialiseert een nieuw exemplaar van de [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur met de opgegeven locatie en grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Een [Point](/psd/python-net/aspose.psd/point/) die de linkerbovenhoek van het rechthoekige gebied weergeeft. |
| size | [Size](/psd/python-net/aspose.psd/size) | Een [Size](/psd/python-net/aspose.psd/size/) die de breedte en hoogte van het rechthoekige gebied weergeeft. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initialiseert een nieuw exemplaar van de [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur met de opgegeven locatie en grootte.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van de linkerbovenhoek van de rechthoek. |
| y | int | De y-coördinaat van de linkerbovenhoek van de rechthoek. |
| width | int | De breedte van de rechthoek. |
| hoogte | int | De hoogte van de rechthoek. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Converteert de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur naar een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur door de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) waarden af te ronden naar de eerstvolgende hogere gehele getallen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) structuur die moet worden geconverteerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Retourneert een [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Bepaalt of het opgegeven punt zich binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur bevindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het punt dat wordt weergegeven door <paramref name="point" /> zich binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur bevindt; anders false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Bepaalt of het rechthoekige gebied dat wordt weergegeven door <paramref name="rect" /> volledig binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur ligt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [Rectangle](/psd/python-net/aspose.psd/rectangle/) om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het rechthoekige gebied dat wordt weergegeven door <paramref name="rect" /> volledig binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur zit; anders false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bepaalt of het opgegeven punt zich binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur bevindt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De x-coördinaat van het te testen punt. |
| y | int | De y-coördinaat van het te testen punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als het punt gedefinieerd door <paramref name="x" /> en <paramref name="y" /> zich binnen deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur bevindt; anders false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Maakt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur met de opgegeven randlocaties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| left | int | De x-coördinaat van de linkerbovenhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| top | int | De y-coördinaat van de linkerbovenhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| right | int | De x-coördinaat van de rechteronderhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |
| bottom | int | De y-coördinaat van de rechteronderhoek van deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | De nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/) die deze methode maakt. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Maakt een nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/) aan de hand van twee opgegeven punten. De twee verticale zijden van de gemaakte [Rectangle](/psd/python-net/aspose.psd/rectangle/) zullen gelijk zijn aan de meegegeven <paramref name="point1" /> en <paramref name="point2" />. Deze zijn doorgaans de tegenovergestelde hoekpunten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Het eerste [Point](/psd/python-net/aspose.psd/point/) voor de nieuwe rechthoek. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Het tweede [Point](/psd/python-net/aspose.psd/point/) voor de nieuwe rechthoek. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een nieuw aangemaakte [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Maakt en retourneert een opgeblazen kopie van de opgegeven [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur. De kopie wordt opgeblazen met de opgegeven hoeveelheid. De oorspronkelijke [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur blijft ongewijzigd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [Rectangle](/psd/python-net/aspose.psd/rectangle/) waarmee gestart wordt. Deze rechthoek wordt niet gewijzigd. |
| x | int | De hoeveelheid om deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) horizontaal uit te breiden. |
| y | int | De hoeveelheid om deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) verticaal uit te breiden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | De vergrote [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Vergroot dit [Rectangle](/psd/python-net/aspose.psd/rectangle/) met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | De hoeveelheid om deze rechthoek uit te breiden. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Vergroot dit [Rectangle](/psd/python-net/aspose.psd/rectangle/) met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De hoeveelheid om deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) horizontaal uit te breiden. |
| height | int | De hoeveelheid om deze [Rectangle](/psd/python-net/aspose.psd/rectangle/) verticaal uit te breiden. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Retourneert een derde [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de intersectie van twee andere [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren weergeeft. Als er geen intersectie is, wordt een lege [Rectangle](/psd/python-net/aspose.psd/rectangle/) geretourneerd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een eerste rechthoek om te intersecteren. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een tweede rechthoek om te intersecteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [Rectangle](/psd/python-net/aspose.psd/rectangle/) die de intersectie van <paramref name="a" /> en <paramref name="b" /> weergeeft. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Vervangt dit [Rectangle](/psd/python-net/aspose.psd/rectangle/) door de intersectie van zichzelf en de opgegeven [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De [Rectangle](/psd/python-net/aspose.psd/rectangle/) waarmee moet worden geïntersecteerd. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Bepaalt of deze rechthoek intersecteert met <paramref name="rect" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om te testen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Deze methode retourneert true als er enige intersectie is, anders false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Hoeveelheid om de locatie te verschuiven. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Past de locatie van deze rechthoek aan met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De horizontale offset. |
| y | int | De verticale offset. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Converteert de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) naar een [Rectangle](/psd/python-net/aspose.psd/rectangle/) door de waarden van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) af te ronden op de dichtstbijzijnde gehele getallen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die moet worden geconverteerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Converteert de opgegeven [RectangleF](/psd/python-net/aspose.psd/rectanglef/) naar een [Rectangle](/psd/python-net/aspose.psd/rectangle/) door de waarden van de [RectangleF](/psd/python-net/aspose.psd/rectanglef/) af te kappen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | De [RectangleF](/psd/python-net/aspose.psd/rectanglef/) die moet worden geconverteerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een nieuwe [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Haalt een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur op die de unie van twee [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een eerste rechthoek om te verenigen. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een tweede rechthoek om te verenigen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Een [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuur die de unie van de twee [Rectangle](/psd/python-net/aspose.psd/rectangle/) structuren begrenst. |


