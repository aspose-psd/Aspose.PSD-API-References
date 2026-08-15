---
title: "Rectangle-klass"
type: docs
weight: 3810
url: /sv/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initierar en ny instans av Rectangle-klassen |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initierar en ny instans av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen med den angivna platsen och storleken. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initierar en ny instans av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen med den angivna platsen och storleken. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bottom | int | r/w | Hämtar eller anger y-koordinaten som är summan av [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) och [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) egenskapsvärdena för denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar en ny instans av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen som har värdena för [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) och [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) satta till noll. |
| height | int | r/w | Hämtar eller anger höjden på denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| is_empty | bool | r | Hämtar ett värde som indikerar om alla numeriska egenskaper för denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) har värdena noll. |
| left | int | r/w | Hämtar eller anger x-koordinaten för den vänstra kanten av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| right | int | r/w | Hämtar eller anger x-koordinaten som är summan av [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) och [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) egenskapsvärdena för denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Hämtar eller anger storleken på denna [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Hämtar eller anger y-koordinaten för den övre kanten av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| width | int | r/w | Hämtar eller anger bredden på denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| x | int | r/w | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| y | int | r/w | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Konverterar den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen till en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur genom att avrunda [RectangleF](/psd/python-net/aspose.psd/rectanglef/) värdena till nästa högre heltal. |
| [contains(point)](#contains_point_2) | Avgör om den angivna punkten finns inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| [contains(rect)](#contains_rect_3) | Avgör om den rektangulära regionen som representeras av <paramref name="rect" /> är helt innehållen inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| [contains(x, y)](#contains_x_y_4) | Avgör om den angivna punkten finns inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Skapar en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur med de angivna kantpositionerna. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Skapar en ny [Rectangle](/psd/python-net/aspose.psd/rectangle/) från två angivna punkter. De två vertikalerna i den skapade [Rectangle](/psd/python-net/aspose.psd/rectangle/) kommer att motsvara de överförda <paramref name="point1" /> och <paramref name="point2" />. Dessa är vanligtvis de motsatta hörnen. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Skapar och returnerar en uppblåst kopia av den angivna [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen. Kopian är uppblåst med det angivna beloppet. Den ursprungliga [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen förblir oförändrad. |
| [inflate(size)](#inflate_size_8) | Uppblåser detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) med det angivna beloppet. |
| [inflate(width, height)](#inflate_width_height_9) | Uppblåser detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) med det angivna beloppet. |
| [intersect(a, b)](#intersect_a_b_10) | Returnerar en tredje [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som representerar skärningen av två andra [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersect(rect)](#intersect_rect_11) | Ersätter detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) med skärningen av sig själv och den angivna [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_12) | Bestämmer om denna rektangel skär med <paramref name="rect" />. |
| normalize() | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [offset(pos)](#offset_pos_13) | Justera placeringen av denna rektangel med det angivna beloppet. |
| [offset(x, y)](#offset_x_y_14) | Justera placeringen av denna rektangel med det angivna beloppet. |
| [round(value)](#round_value_15) | Konverterar den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) till en [Rectangle](/psd/python-net/aspose.psd/rectangle/) genom att avrunda [RectangleF](/psd/python-net/aspose.psd/rectanglef/) värdena till närmaste heltal. |
| [truncate(value)](#truncate_value_16) | Konverterar den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) till en [Rectangle](/psd/python-net/aspose.psd/rectangle/) genom att trunkera [RectangleF](/psd/python-net/aspose.psd/rectanglef/) värdena. |
| [union(a, b)](#union_a_b_17) | Hämtar en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som innehåller unionen av två [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initierar en ny instans av Rectangle-klassen

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initierar en ny instans av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | En [Point](/psd/python-net/aspose.psd/point/) som representerar det övre vänstra hörnet av den rektangulära regionen. |
| size | [Size](/psd/python-net/aspose.psd/size) | En [Size](/psd/python-net/aspose.psd/size/) som representerar bredden och höjden på den rektangulära regionen. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initierar en ny instans av [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | int | Y-koordinaten för det övre vänstra hörnet av rektangeln. |
| width | int | Rektangelns bredd. |
| height | int | Rektangelns höjd. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Konverterar den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen till en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur genom att avrunda [RectangleF](/psd/python-net/aspose.psd/rectanglef/) värdena till nästa högre heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen som ska konverteras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Returnerar en [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Avgör om den angivna punkten finns inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som representeras av <paramref name="point" /> finns inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur; annars false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Avgör om den rektangulära regionen som representeras av <paramref name="rect" /> är helt innehållen inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [Rectangle](/psd/python-net/aspose.psd/rectangle/) att testa. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om den rektangulära regionen som representeras av <paramref name="rect" /> är helt innehållen i denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur; annars false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Avgör om den angivna punkten finns inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten definierad av <paramref name="x" /> och <paramref name="y" /> finns inom denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur; annars false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Skapar en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur med de angivna kantpositionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left | int | X-koordinaten för det övre vänstra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| top | int | Y-koordinaten för det övre vänstra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| right | int | X-koordinaten för det nedre högra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |
| bottom | int | Y-koordinaten för det nedre högra hörnet av denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den nya [Rectangle](/psd/python-net/aspose.psd/rectangle/) som denna metod skapar. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Skapar en ny [Rectangle](/psd/python-net/aspose.psd/rectangle/) från två angivna punkter. De två vertikalerna i den skapade [Rectangle](/psd/python-net/aspose.psd/rectangle/) kommer att motsvara de överförda <paramref name="point1" /> och <paramref name="point2" />. Dessa är vanligtvis de motsatta hörnen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Den första [Point](/psd/python-net/aspose.psd/point/) för den nya rektangeln. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Den andra [Point](/psd/python-net/aspose.psd/point/) för den nya rektangeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | En ny skapad [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Skapar och returnerar en uppblåst kopia av den angivna [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen. Kopian är uppblåst med det angivna beloppet. Den ursprungliga [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturen förblir oförändrad.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [Rectangle](/psd/python-net/aspose.psd/rectangle/) att börja med. Denna rektangel ändras inte. |
| x | int | Beloppet för att uppblåsa denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) horisontellt. |
| y | int | Mängden för att utvidga detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) vertikalt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den utvidgade [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Uppblåser detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Mängden för att expandera denna rektangel. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Uppblåser detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Beloppet för att uppblåsa denna [Rectangle](/psd/python-net/aspose.psd/rectangle/) horisontellt. |
| height | int | Mängden för att utvidga detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) vertikalt. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Returnerar en tredje [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som representerar skärningen av två andra [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer. Om det inte finns någon skärning returneras en tom [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En första rektangel för skärning. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En andra rektangel för skärning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [Rectangle](/psd/python-net/aspose.psd/rectangle/) som representerar skärningen av <paramref name=\"a\" /> och <paramref name=\"b\" />. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Ersätter detta [Rectangle](/psd/python-net/aspose.psd/rectangle/) med skärningen av sig själv och den angivna [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den [Rectangle](/psd/python-net/aspose.psd/rectangle/) att skära med. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Bestämmer om denna rektangel skär med <paramref name="rect" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln för test. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det finns någon skärning, annars false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Justera placeringen av denna rektangel med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Mängd för att förskjuta platsen. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Justera placeringen av denna rektangel med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Den horisontella förskjutningen. |
| y | int | Den vertikala förskjutningen. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Konverterar den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) till en [Rectangle](/psd/python-net/aspose.psd/rectangle/) genom att avrunda [RectangleF](/psd/python-net/aspose.psd/rectanglef/) värdena till närmaste heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som ska konverteras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | En ny [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Konverterar den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) till en [Rectangle](/psd/python-net/aspose.psd/rectangle/) genom att trunkera [RectangleF](/psd/python-net/aspose.psd/rectanglef/) värdena.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som ska konverteras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | En ny [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Hämtar en [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som innehåller unionen av två [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En första rektangel för förening. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | En andra rektangel för förening. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | En [Rectangle](/psd/python-net/aspose.psd/rectangle/) struktur som avgränsar föreningen av de två [Rectangle](/psd/python-net/aspose.psd/rectangle/) strukturerna. |


