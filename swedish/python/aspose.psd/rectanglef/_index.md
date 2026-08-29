---
title: "RectangleF klass"
type: docs
weight: 3830
url: /sv/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initierar en ny instans av RectangleF-klassen |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initierar en ny instans av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen med den angivna platsen och storleken. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initierar en ny instans av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen med den angivna platsen och storleken. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bottom | float | r/w | Hämtar eller anger y-koordinaten som är summan av [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) och [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) för denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Hämtar en ny instans av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen som har värdena [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) och [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) satta till noll. |
| height | float | r/w | Hämtar eller anger höjden på denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| is_empty | bool | r | Hämtar ett värde som indikerar om [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) eller [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) egenskapen för denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) har värdet noll. |
| left | float | r/w | Hämtar eller anger x-koordinaten för den vänstra kanten av denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| right | float | r/w | Hämtar eller anger x-koordinaten som är summan av [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) och [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) för denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Hämtar eller anger storleken på denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| top | float | r/w | Hämtar eller anger y-koordinaten för den övre kanten av denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| width | float | r/w | Hämtar eller anger bredden på denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| x | float | r/w | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| y | float | r/w | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [contains(point)](#contains_point_1) | Bestämmer om den angivna punkten finns inom denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [contains(rect)](#contains_rect_2) | Bestämmer om det rektangulära området som representeras av <paramref name=\"rect\" /> är helt inneslutet i denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [contains(x, y)](#contains_x_y_3) | Bestämmer om den angivna punkten finns inom denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Skapar en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Skapar en ny [Rectangle](/psd/python-net/aspose.psd/rectangle/) från två angivna punkter. De två hörnen i den skapade [Rectangle](/psd/python-net/aspose.psd/rectangle/) kommer att vara lika med de överförda <paramref name=\"point1\" /> och <paramref name=\"point2\" />. Dessa är vanligtvis de motsatta hörnen. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. Kopian uppblås med det angivna beloppet. Den ursprungliga rektangeln förblir oförändrad. |
| [inflate(size)](#inflate_size_7) | Uppblåser denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) med det angivna beloppet. |
| [inflate(x, y)](#inflate_x_y_8) | Uppblåser denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur med det angivna beloppet. |
| [intersect(a, b)](#intersect_a_b_9) | Returnerar en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar skärningen av två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| [intersect(rect)](#intersect_rect_10) | Ersätter denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur med skärningen av sig själv och den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. |
| [intersects_with(rect)](#intersects_with_rect_11) | Bestämmer om denna rektangel skär med <paramref name="rect" />. |
| normalize() | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [offset(pos)](#offset_pos_12) | Justera placeringen av denna rektangel med det angivna beloppet. |
| [offset(x, y)](#offset_x_y_13) | Justera placeringen av denna rektangel med det angivna beloppet. |
| [union(a, b)](#union_a_b_14) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initierar en ny instans av RectangleF-klassen

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initierar en ny instans av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | En [PointF](/psd/python-net/aspose.psd/pointf/) som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | En [SizeF](/psd/python-net/aspose.psd/sizef/) som representerar bredden och höjden på det rektangulära området. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initierar en ny instans av [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen med den angivna platsen och storleken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för det övre vänstra hörnet av rektangeln. |
| y | float | Y-koordinaten för det övre vänstra hörnet av rektangeln. |
| width | float | Rektangelns bredd. |
| height | float | Rektangelns höjd. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Bestämmer om den angivna punkten finns inom denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som representeras av parametern <paramref name="point" /> finns inom denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur; annars false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Bestämmer om det rektangulära området som representeras av <paramref name=\"rect\" /> är helt inneslutet i denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det rektangulära området som representeras av <paramref name="rect" /> är helt innehållet inom det rektangulära området som representeras av denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/); annars false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Bestämmer om den angivna punkten finns inom denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om punkten som definieras av <paramref name="x" /> och <paramref name="y" /> finns inom denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur; annars false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Skapar en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vänster | float | X-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| övre | float | Y-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| höger | float | X-koordinaten för det nedre högra hörnet av det rektangulära området. |
| nedre | float | Y-koordinaten för det nedre högra hörnet av det rektangulära området. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den nya [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som denna metod skapar. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Skapar en ny [Rectangle](/psd/python-net/aspose.psd/rectangle/) från två angivna punkter. De två hörnen i den skapade [Rectangle](/psd/python-net/aspose.psd/rectangle/) kommer att vara lika med de överförda <paramref name=\"point1\" /> och <paramref name=\"point2\" />. Dessa är vanligtvis de motsatta hörnen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Den första [Point](/psd/python-net/aspose.psd/point/) för den nya rektangeln. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Den andra [Point](/psd/python-net/aspose.psd/point/) för den nya rektangeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En ny skapad [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Skapar och returnerar en uppblåst kopia av den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen. Kopian uppblås med det angivna beloppet. Den ursprungliga rektangeln förblir oförändrad.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den [RectangleF](/psd/python-net/aspose.psd/rectanglef/) som ska kopieras. Denna rektangel är inte modifierad. |
| x | float | Mängden för att expandera kopian av rektangeln horisontellt. |
| y | float | Mängden för att expandera kopian av rektangeln vertikalt. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Den expanderade [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Uppblåser denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Mängden för att expandera denna rektangel. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Uppblåser denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | Mängden för att expandera denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur horisontellt. |
| y | float | Mängden för att expandera denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur vertikalt. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Returnerar en [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som representerar skärningen av två rektanglar. Om det inte finns någon skärning returneras en tom [RectangleF](/psd/python-net/aspose.psd/rectanglef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En första rektangel för skärning. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En andra rektangel för skärning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En tredje [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur vars storlek representerar det överlappande området av de två angivna rektanglarna. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Ersätter denna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur med skärningen av sig själv och den angivna [RectangleF](/psd/python-net/aspose.psd/rectanglef/) strukturen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rektangeln för skärning. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Bestämmer om denna rektangel skär med <paramref name="rect" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Rektangeln för test. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Denna metod returnerar true om det finns någon skärning. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Justera placeringen av denna rektangel med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | Mängden för att förskjuta platsen. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Justera placeringen av denna rektangel med det angivna beloppet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | float | Mängden för att förskjuta platsen horisontellt. |
| y | float | Mängden för att förskjuta platsen vertikalt. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En första rektangel för förening. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En andra rektangel för förening. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | En tredje [RectangleF](/psd/python-net/aspose.psd/rectanglef/) struktur som innehåller båda de två rektanglarna som bildar föreningen. |


