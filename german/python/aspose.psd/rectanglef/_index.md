---
title: "RectangleF-Klasse"
type: docs
weight: 3830
url: /de/python-net/aspose.psd/rectanglef/
---

**Summary:** Stores a set of four floating-point numbers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RectangleF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [RectangleF()](#RectangleF__1) | Initialisiert eine neue Instanz der RectangleF-Klasse |
| [RectangleF(location, size)](#RectangleF_location_size_2) | Initialisiert eine neue Instanz der [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur mit dem angegebenen Ort und der Größe. |
| [RectangleF(x, y, width, height)](#RectangleF_x_y_width_height_3) | Initialisiert eine neue Instanz der [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur mit dem angegebenen Ort und der Größe. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bottom | float | r/w | Liest oder setzt die y-Koordinate, die die Summe von [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/) und [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur ist. |
| empty [static] | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Liest eine neue Instanz der [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, deren Werte für [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.y](/psd/python-net/aspose.psd/rectanglef/), [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) und [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) auf Null gesetzt sind. |
| height | float | r/w | Liest oder setzt die Höhe dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| is_empty | bool | r | Liest einen Wert, der angibt, ob die Eigenschaft [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) oder [RectangleF.height](/psd/python-net/aspose.psd/rectanglef/) dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) den Wert Null hat. |
| left | float | r/w | Liest oder setzt die x-Koordinate der linken Kante dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | r/w | Liest oder setzt die Koordinaten der oberen linken Ecke dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| right | float | r/w | Liest oder setzt die x-Koordinate, die die Summe von [RectangleF.x](/psd/python-net/aspose.psd/rectanglef/) und [RectangleF.width](/psd/python-net/aspose.psd/rectanglef/) dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur ist. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Liest oder setzt die Größe dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |
| top | float | r/w | Liest oder setzt die y-Koordinate der oberen Kante dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| width | float | r/w | Liest oder setzt die Breite dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| x | float | r/w | Liest oder setzt die x‑Koordinate der oberen linken Ecke dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| y | float | r/w | Liest oder setzt die y‑Koordinate der oberen linken Ecke dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [contains(point)](#contains_point_1) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt. |
| [contains(rect)](#contains_rect_2) | Bestimmt, ob die durch <paramref name=\"rect\" /> dargestellte rechteckige Region vollständig innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt. |
| [contains(x, y)](#contains_x_y_3) | Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_4) | Erstellt eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen. |
| [from_points(point1, point2)](#from_points_point1_point2_5) | Erstellt ein neues [Rectangle](/psd/python-net/aspose.psd/rectangle/) aus zwei angegebenen Punkten. Zwei Eckpunkte des erstellten [Rectangle](/psd/python-net/aspose.psd/rectangle/) entsprechen den übergebenen <paramref name=\"point1\" /> und <paramref name=\"point2\" />. Diese sind typischerweise die gegenüberliegenden Eckpunkte. |
| [inflate(rect, x, y)](#inflate_rect_x_y_6) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Das ursprüngliche Rechteck bleibt unverändert. |
| [inflate(size)](#inflate_size_7) | Bläht dieses [RectangleF](/psd/python-net/aspose.psd/rectanglef/) um den angegebenen Betrag auf. |
| [inflate(x, y)](#inflate_x_y_8) | Bläht diese [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur um den angegebenen Betrag auf. |
| [intersect(a, b)](#intersect_a_b_9) | Gibt eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zurückgegeben. |
| [intersect(rect)](#intersect_rect_10) | Ersetzt diese [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur durch die Schnittmenge mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |
| [intersects_with(rect)](#intersects_with_rect_11) | Bestimmt, ob dieses Rechteck mit <paramref name=\"rect\" /> schneidet. |
| normalize() | Normalisiert das Rechteck, indem Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [offset(pos)](#offset_pos_12) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [offset(x, y)](#offset_x_y_13) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [union(a, b)](#union_a_b_14) | Erstellt das kleinste mögliche dritte Rechteck, das beide der beiden Rechtecke, die eine Vereinigung bilden, enthalten kann. |


### Constructor: RectangleF() {#RectangleF__1}


```
 RectangleF() 
```

Initialisiert eine neue Instanz der RectangleF-Klasse

### Constructor: RectangleF(location, size) {#RectangleF_location_size_2}


```
 RectangleF(location, size) 
```

Initialisiert eine neue Instanz der [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| location | [PointF](/psd/python-net/aspose.psd/pointf) | Ein [PointF](/psd/python-net/aspose.psd/pointf/), das die obere linke Ecke der rechteckigen Region darstellt. |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Ein [SizeF](/psd/python-net/aspose.psd/sizef/), das Breite und Höhe der rechteckigen Region darstellt. |

### Constructor: RectangleF(x, y, width, height) {#RectangleF_x_y_width_height_3}


```
 RectangleF(x, y, width, height) 
```

Initialisiert eine neue Instanz der [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x‑Koordinate der oberen linken Ecke des Rechtecks. |
| y | float | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| width | float | Die Breite des Rechtecks. |
| height | float | Die Höhe des Rechtecks. |

### Method: contains(point) {#contains_point_1}


```
 contains(point) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Der zu testende [PointF](/psd/python-net/aspose.psd/pointf/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch den Parameter <paramref name=\"point\" /> dargestellte Punkt innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt; andernfalls false. |


### Method: contains(rect) {#contains_rect_2}


```
 contains(rect) 
```

Bestimmt, ob die durch <paramref name=\"rect\" /> dargestellte rechteckige Region vollständig innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch <paramref name="rect" /> dargestellte rechteckige Bereich vollständig innerhalb des durch dieses [RectangleF](/psd/python-net/aspose.psd/rectanglef/) dargestellten rechteckigen Bereichs liegt; andernfalls false. |


### Method: contains(x, y) {#contains_x_y_3}


```
 contains(x, y) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die x-Koordinate des zu testenden Punktes. |
| y | float | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch <paramref name="x" /> und <paramref name="y" /> definierte Punkt innerhalb dieser [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur liegt; andernfalls false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_4}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Erstellt eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur mit der oberen linken Ecke und der unteren rechten Ecke an den angegebenen Positionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left | float | Die x-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| oben | float | Die y-Koordinate der oberen linken Ecke des rechteckigen Bereichs. |
| rechts | float | Die x-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |
| bottom | float | Die y-Koordinate der unteren rechten Ecke des rechteckigen Bereichs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das neue [RectangleF](/psd/python-net/aspose.psd/rectanglef/), das diese Methode erstellt. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_5}


```
 from_points(point1, point2) 
```

Erstellt ein neues [Rectangle](/psd/python-net/aspose.psd/rectangle/) aus zwei angegebenen Punkten. Zwei Eckpunkte des erstellten [Rectangle](/psd/python-net/aspose.psd/rectangle/) entsprechen den übergebenen <paramref name=\"point1\" /> und <paramref name=\"point2\" />. Diese sind typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [PointF](/psd/python-net/aspose.psd/pointf) | Der erste [Point](/psd/python-net/aspose.psd/point/) für das neue Rechteck. |
| point2 | [PointF](/psd/python-net/aspose.psd/pointf) | Der zweite [Point](/psd/python-net/aspose.psd/point/) für das neue Rechteck. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein neu erstelltes [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_6}


```
 inflate(rect, x, y) 
```

Erstellt und gibt eine aufgeblähte Kopie der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zurück. Die Kopie wird um den angegebenen Betrag vergrößert. Das ursprüngliche Rechteck bleibt unverändert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das zu kopierende [RectangleF](/psd/python-net/aspose.psd/rectanglef/). Dieses Rechteck wird nicht verändert. |
| x | float | Der Betrag, um den die Kopie des Rechtecks horizontal aufgebläht wird. |
| y | float | Der Betrag, um den die Kopie des Rechtecks vertikal aufgebläht wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das aufgeblähte [RectangleF](/psd/python-net/aspose.psd/rectanglef/). |


### Method: inflate(size) {#inflate_size_7}


```
 inflate(size) 
```

Bläht dieses [RectangleF](/psd/python-net/aspose.psd/rectanglef/) um den angegebenen Betrag auf.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Der Betrag, um den dieses Rechteck aufgebläht wird. |

### Method: inflate(x, y) {#inflate_x_y_8}


```
 inflate(x, y) 
```

Bläht diese [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur um den angegebenen Betrag auf.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Der Betrag, um den diese [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur horizontal aufgebläht wird. |
| y | float | Der Betrag, um den diese [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur vertikal aufgebläht wird. |

### Method: intersect(a, b)  [static] {#intersect_a_b_9}


```
 intersect(a, b) 
```

Gibt eine [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur zurück, die die Schnittmenge zweier Rechtecke darstellt. Wenn es keine Schnittmenge gibt, wird ein leeres [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein erstes Rechteck zum Schneiden. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein zweites Rechteck zum Schneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein drittes [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, deren Größe den überlappenden Bereich der beiden angegebenen Rechtecke darstellt. |


### Method: intersect(rect) {#intersect_rect_10}


```
 intersect(rect) 
```

Ersetzt diese [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur durch die Schnittmenge mit der angegebenen [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Rechteck zum Schneiden. |

### Method: intersects_with(rect) {#intersects_with_rect_11}


```
 intersects_with(rect) 
```

Bestimmt, ob dieses Rechteck mit <paramref name=\"rect\" /> schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das Rechteck zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn es irgendeine Schnittmenge gibt. |


### Method: offset(pos) {#offset_pos_12}


```
 offset(pos) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pos | [PointF](/psd/python-net/aspose.psd/pointf) | Der Betrag, um den Standort zu verschieben. |

### Method: offset(x, y) {#offset_x_y_13}


```
 offset(x, y) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Der Betrag, um den Standort horizontal zu verschieben. |
| y | float | Der Betrag, um den Standort vertikal zu verschieben. |

### Method: union(a, b)  [static] {#union_a_b_14}


```
 union(a, b) 
```

Erstellt das kleinste mögliche dritte Rechteck, das beide der beiden Rechtecke, die eine Vereinigung bilden, enthalten kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein erstes Rechteck für die Vereinigung. |
| b | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Ein zweites Rechteck für die Vereinigung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Eine dritte [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur, die beide Rechtecke, die die Vereinigung bilden, enthält. |


