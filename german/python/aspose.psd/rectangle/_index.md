---
title: "Rectangle-Klasse"
type: docs
weight: 3810
url: /de/python-net/aspose.psd/rectangle/
---

**Summary:** Stores a set of four integers that represent the location and size of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Rectangle

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Rectangle()](#Rectangle__1) | Initialisiert eine neue Instanz der Rectangle-Klasse |
| [Rectangle(location, size)](#Rectangle_location_size_2) | Initialisiert eine neue Instanz der [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur mit dem angegebenen Ort und der Größe. |
| [Rectangle(x, y, width, height)](#Rectangle_x_y_width_height_3) | Initialisiert eine neue Instanz der [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur mit dem angegebenen Ort und der Größe. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bottom | int | r/w | Liest oder setzt die y-Koordinate, die die Summe der [Rectangle.y](/psd/python-net/aspose.psd/rectangle/) und [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) Eigenschaftswerte dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur ist. |
| empty [static] | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Liest eine neue Instanz der [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, deren [Rectangle.x](/psd/python-net/aspose.psd/rectangle/), [Rectangle.y](/psd/python-net/aspose.psd/rectangle/), [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) und [Rectangle.height](/psd/python-net/aspose.psd/rectangle/) Werte auf Null gesetzt sind. |
| height | int | r/w | Liest oder setzt die Höhe dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| is_empty | bool | r | Liest einen Wert, der angibt, ob alle numerischen Eigenschaften dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) den Wert Null haben. |
| left | int | r/w | Liest oder setzt die x-Koordinate der linken Kante dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| location | [Point](/psd/python-net/aspose.psd/point) | r/w | Liest oder setzt die Koordinaten der oberen linken Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| right | int | r/w | Liest oder setzt die x-Koordinate, die die Summe der [Rectangle.x](/psd/python-net/aspose.psd/rectangle/) und [Rectangle.width](/psd/python-net/aspose.psd/rectangle/) Eigenschaftswerte dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur ist. |
| size | [Size](/psd/python-net/aspose.psd/size) | r/w | Liest oder setzt die Größe dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| top | int | r/w | Liest oder setzt die y-Koordinate der oberen Kante dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| width | int | r/w | Liest oder setzt die Breite dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| x | int | r/w | Liest oder setzt die x-Koordinate der oberen linken Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| y | int | r/w | Liest oder setzt die y-Koordinate der oberen linken Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [ceiling(value)](#ceiling_value_1) | Konvertiert die angegebene [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur in eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, indem die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Werte auf die nächsthöhere ganze Zahl gerundet werden. |
| [contains(point)](#contains_point_2) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur liegt. |
| [contains(rect)](#contains_rect_3) | Bestimmt, ob der durch <paramref name="rect" /> dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur liegt. |
| [contains(x, y)](#contains_x_y_4) | Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur liegt. |
| [from_left_top_right_bottom(left, top, right, bottom)](#from_left_top_right_bottom_left_top_right_bottom_5) | Erstellt eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur mit den angegebenen Kantenpositionen. |
| [from_points(point1, point2)](#from_points_point1_point2_6) | Erstellt ein neues [Rectangle](/psd/python-net/aspose.psd/rectangle/) aus zwei angegebenen Punkten. Zwei Vertikalen des erstellten [Rectangle](/psd/python-net/aspose.psd/rectangle/) werden gleich den übergebenen <paramref name="point1" /> und <paramref name="point2" /> sein. Diese wären typischerweise die gegenüberliegenden Eckpunkte. |
| [inflate(rect, x, y)](#inflate_rect_x_y_7) | Erstellt und gibt eine aufgeblähte Kopie der angegebenen [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Die ursprüngliche [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur bleibt unverändert. |
| [inflate(size)](#inflate_size_8) | Bläht dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) um den angegebenen Betrag auf. |
| [inflate(width, height)](#inflate_width_height_9) | Bläht dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) um den angegebenen Betrag auf. |
| [intersect(a, b)](#intersect_a_b_10) | Gibt eine dritte [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen darstellt. Wenn keine Schnittmenge existiert, wird ein leeres [Rectangle](/psd/python-net/aspose.psd/rectangle/) zurückgegeben. |
| [intersect(rect)](#intersect_rect_11) | Ersetzt dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) durch die Schnittmenge von sich selbst und dem angegebenen [Rectangle](/psd/python-net/aspose.psd/rectangle/). |
| [intersects_with(rect)](#intersects_with_rect_12) | Bestimmt, ob dieses Rechteck mit <paramref name=\"rect\" /> schneidet. |
| normalize() | Normalisiert das Rechteck, indem Breite und Höhe positiv gemacht werden, links kleiner als rechts und oben kleiner als unten ist. |
| [offset(pos)](#offset_pos_13) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [offset(x, y)](#offset_x_y_14) | Verschiebt die Position dieses Rechtecks um den angegebenen Betrag. |
| [round(value)](#round_value_15) | Konvertiert das angegebene [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zu einem [Rectangle](/psd/python-net/aspose.psd/rectangle/), indem die Werte des [RectangleF](/psd/python-net/aspose.psd/rectanglef/) auf die nächsten Ganzzahlen gerundet werden. |
| [truncate(value)](#truncate_value_16) | Konvertiert das angegebene [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zu einem [Rectangle](/psd/python-net/aspose.psd/rectangle/), indem die Werte des [RectangleF](/psd/python-net/aspose.psd/rectanglef/) abgeschnitten werden. |
| [union(a, b)](#union_a_b_17) | Erhält eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die die Vereinigung zweier [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen enthält. |


### Constructor: Rectangle() {#Rectangle__1}


```
 Rectangle() 
```

Initialisiert eine neue Instanz der Rectangle-Klasse

### Constructor: Rectangle(location, size) {#Rectangle_location_size_2}


```
 Rectangle(location, size) 
```

Initialisiert eine neue Instanz der [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Ein [Point](/psd/python-net/aspose.psd/point/), der die obere linke Ecke des rechteckigen Bereichs darstellt. |
| size | [Size](/psd/python-net/aspose.psd/size) | Ein [Size](/psd/python-net/aspose.psd/size/), der die Breite und Höhe des rechteckigen Bereichs darstellt. |

### Constructor: Rectangle(x, y, width, height) {#Rectangle_x_y_width_height_3}


```
 Rectangle(x, y, width, height) 
```

Initialisiert eine neue Instanz der [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur mit dem angegebenen Ort und der Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x‑Koordinate der oberen linken Ecke des Rechtecks. |
| y | int | Die y‑Koordinate der oberen linken Ecke des Rechtecks. |
| width | int | Die Breite des Rechtecks. |
| height | int | Die Höhe des Rechtecks. |

### Method: ceiling(value)  [static] {#ceiling_value_1}


```
 ceiling(value) 
```

Konvertiert die angegebene [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur in eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, indem die [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Werte auf die nächsthöhere ganze Zahl gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Die zu konvertierende [RectangleF](/psd/python-net/aspose.psd/rectanglef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Gibt ein [Rectangle](/psd/python-net/aspose.psd/rectangle/) zurück. |


### Method: contains(point) {#contains_point_2}


```
 contains(point) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Der zu testende [Point](/psd/python-net/aspose.psd/point/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch <paramref name="point" /> dargestellte Punkt innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur enthalten ist; andernfalls false. |


### Method: contains(rect) {#contains_rect_3}


```
 contains(rect) 
```

Bestimmt, ob der durch <paramref name="rect" /> dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das zu testende [Rectangle](/psd/python-net/aspose.psd/rectangle/). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch <paramref name="rect" /> dargestellte rechteckige Bereich vollständig innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur enthalten ist; andernfalls false. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bestimmt, ob der angegebene Punkt innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur liegt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Koordinate des zu testenden Punktes. |
| y | int | Die y-Koordinate des zu testenden Punktes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn der durch <paramref name="x" /> und <paramref name="y" /> definierte Punkt innerhalb dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur enthalten ist; andernfalls false. |


### Method: from_left_top_right_bottom(left, top, right, bottom)  [static] {#from_left_top_right_bottom_left_top_right_bottom_5}


```
 from_left_top_right_bottom(left, top, right, bottom) 
```

Erstellt eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur mit den angegebenen Kantenpositionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| left | int | Die x-Koordinate der oberen linken Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| top | int | Die y-Koordinate der oberen linken Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| right | int | Die x‑Koordinate der unteren rechten Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |
| bottom | int | Die y‑Koordinate der unteren rechten Ecke dieser [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das neue [Rectangle](/psd/python-net/aspose.psd/rectangle/), das diese Methode erstellt. |


### Method: from_points(point1, point2)  [static] {#from_points_point1_point2_6}


```
 from_points(point1, point2) 
```

Erstellt ein neues [Rectangle](/psd/python-net/aspose.psd/rectangle/) aus zwei angegebenen Punkten. Zwei Vertikalen des erstellten [Rectangle](/psd/python-net/aspose.psd/rectangle/) werden gleich den übergebenen <paramref name="point1" /> und <paramref name="point2" /> sein. Diese wären typischerweise die gegenüberliegenden Eckpunkte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point1 | [Point](/psd/python-net/aspose.psd/point) | Der erste [Point](/psd/python-net/aspose.psd/point/) für das neue Rechteck. |
| point2 | [Point](/psd/python-net/aspose.psd/point) | Der zweite [Point](/psd/python-net/aspose.psd/point/) für das neue Rechteck. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein neu erstelltes [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(rect, x, y)  [static] {#inflate_rect_x_y_7}


```
 inflate(rect, x, y) 
```

Erstellt und gibt eine aufgeblähte Kopie der angegebenen [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur zurück. Die Kopie wird um den angegebenen Betrag aufgebläht. Die ursprüngliche [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur bleibt unverändert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das [Rectangle](/psd/python-net/aspose.psd/rectangle/) zum Starten. Dieses Rechteck wird nicht verändert. |
| x | int | Der Betrag, um den dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) horizontal erweitert wird. |
| y | int | Der Betrag, um den dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) vertikal erweitert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das erweiterte [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: inflate(size) {#inflate_size_8}


```
 inflate(size) 
```

Bläht dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) um den angegebenen Betrag auf.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Der Betrag, um den dieses Rechteck aufgebläht wird. |

### Method: inflate(width, height) {#inflate_width_height_9}


```
 inflate(width, height) 
```

Bläht dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) um den angegebenen Betrag auf.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Der Betrag, um den dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) horizontal erweitert wird. |
| height | int | Der Betrag, um den dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) vertikal erweitert wird. |

### Method: intersect(a, b)  [static] {#intersect_a_b_10}


```
 intersect(a, b) 
```

Gibt eine dritte [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur zurück, die die Schnittmenge zweier anderer [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen darstellt. Wenn keine Schnittmenge existiert, wird ein leeres [Rectangle](/psd/python-net/aspose.psd/rectangle/) zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein erstes Rechteck zum Schneiden. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein zweites Rechteck zum Schneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein [Rectangle](/psd/python-net/aspose.psd/rectangle/), das die Schnittmenge von <paramref name="a" /> und <paramref name="b" /> darstellt. |


### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Ersetzt dieses [Rectangle](/psd/python-net/aspose.psd/rectangle/) durch die Schnittmenge von sich selbst und dem angegebenen [Rectangle](/psd/python-net/aspose.psd/rectangle/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das [Rectangle](/psd/python-net/aspose.psd/rectangle/) zum Überschneiden. |

### Method: intersects_with(rect) {#intersects_with_rect_12}


```
 intersects_with(rect) 
```

Bestimmt, ob dieses Rechteck mit <paramref name=\"rect\" /> schneidet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck zum Testen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Diese Methode gibt true zurück, wenn eine Schnittmenge existiert, andernfalls false. |


### Method: offset(pos) {#offset_pos_13}


```
 offset(pos) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pos | [Point](/psd/python-net/aspose.psd/point) | Betrag, um den Standort zu verschieben. |

### Method: offset(x, y) {#offset_x_y_14}


```
 offset(x, y) 
```

Verschiebt die Position dieses Rechtecks um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Der horizontale Versatz. |
| y | int | Der vertikale Versatz. |

### Method: round(value)  [static] {#round_value_15}


```
 round(value) 
```

Konvertiert das angegebene [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zu einem [Rectangle](/psd/python-net/aspose.psd/rectangle/), indem die Werte des [RectangleF](/psd/python-net/aspose.psd/rectanglef/) auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zum Konvertieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein neues [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: truncate(value)  [static] {#truncate_value_16}


```
 truncate(value) 
```

Konvertiert das angegebene [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zu einem [Rectangle](/psd/python-net/aspose.psd/rectangle/), indem die Werte des [RectangleF](/psd/python-net/aspose.psd/rectanglef/) abgeschnitten werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| value | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Das [RectangleF](/psd/python-net/aspose.psd/rectanglef/) zum Konvertieren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein neues [Rectangle](/psd/python-net/aspose.psd/rectangle/). |


### Method: union(a, b)  [static] {#union_a_b_17}


```
 union(a, b) 
```

Erhält eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die die Vereinigung zweier [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| a | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein erstes Rechteck für die Vereinigung. |
| b | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ein zweites Rechteck für die Vereinigung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Eine [Rectangle](/psd/python-net/aspose.psd/rectangle/) Struktur, die die Vereinigung der beiden [Rectangle](/psd/python-net/aspose.psd/rectangle/) Strukturen umschließt. |


