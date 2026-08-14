---
title: "Point Klasse"
type: docs
weight: 3530
url: /de/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Point()](#Point__1) | Initialisiert eine neue Instanz der Point Klasse |
| [Point(dw)](#Point_dw_2) | Initialisiert eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur mit Koordinaten, die durch einen ganzzahligen Wert angegeben werden. |
| [Point(size)](#Point_size_3) | Initialisiert eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur aus der [Size](/psd/python-net/aspose.psd/size/) Struktur. |
| [Point(x, y)](#Point_x_y_4) | Initialisiert eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur mit den angegebenen Koordinaten. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Ruft eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur ab, bei der die Werte von [Point.x](/psd/python-net/aspose.psd/point/) und [Point.y](/psd/python-net/aspose.psd/point/) auf Null gesetzt sind. |
| is_empty | bool | r | Ruft einen Wert ab, der angibt, ob dieses [Point](/psd/python-net/aspose.psd/point/) leer ist. |
| x | int | r/w | Liest oder setzt die x-Koordinate dieses [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Liest oder setzt die y-Koordinate dieses [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Addiert die angegebene [Size](/psd/python-net/aspose.psd/size/) zum angegebenen [Point](/psd/python-net/aspose.psd/point/). |
| [ceiling(point)](#ceiling_point_2) | Konvertiert das angegebene [PointF](/psd/python-net/aspose.psd/pointf/) in ein [Point](/psd/python-net/aspose.psd/point/), indem die Werte des [PointF](/psd/python-net/aspose.psd/pointf/) auf die nächsthöheren Ganzzahlen gerundet werden. |
| [offset(dx, dy)](#offset_dx_dy_3) | Verschiebt dieses [Point](/psd/python-net/aspose.psd/point/) um den angegebenen Betrag. |
| [offset(point)](#offset_point_4) | Verschiebt dieses [Point](/psd/python-net/aspose.psd/point/) um das angegebene [Point](/psd/python-net/aspose.psd/point/). |
| [round(point)](#round_point_5) | Konvertiert das angegebene [PointF](/psd/python-net/aspose.psd/pointf/) in ein [Point](/psd/python-net/aspose.psd/point/)‑Objekt, indem die Werte des [Point](/psd/python-net/aspose.psd/point/) auf die nächste ganze Zahl gerundet werden. |
| [subtract(point, size)](#subtract_point_size_6) | Gibt das Ergebnis der Subtraktion der angegebenen [Size](/psd/python-net/aspose.psd/size/) vom angegebenen [Point](/psd/python-net/aspose.psd/point/) zurück. |
| [truncate(point)](#truncate_point_7) | Konvertiert das angegebene [PointF](/psd/python-net/aspose.psd/pointf/) in ein [Point](/psd/python-net/aspose.psd/point/), indem die Werte des [Point](/psd/python-net/aspose.psd/point/) abgeschnitten werden. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initialisiert eine neue Instanz der Point Klasse

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initialisiert eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur mit Koordinaten, die durch einen ganzzahligen Wert angegeben werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dw | int | Ein 32‑Bit‑Integer, der die Koordinaten für den neuen Punkt angibt. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initialisiert eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur aus der [Size](/psd/python-net/aspose.psd/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Enthält die neuen Punktkoordinaten. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initialisiert eine neue Instanz der [Point](/psd/python-net/aspose.psd/point/) Struktur mit den angegebenen Koordinaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die horizontale Position des Punktes. |
| y | int | Die vertikale Position des Punktes. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Addiert die angegebene [Size](/psd/python-net/aspose.psd/size/) zum angegebenen [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) zu dem hinzugefügt wird. |
| size | [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) zum Hinzufügen zu <paramref name="point" />. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) der das Ergebnis der Additionsoperation ist. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Konvertiert das angegebene [PointF](/psd/python-net/aspose.psd/pointf/) in ein [Point](/psd/python-net/aspose.psd/point/), indem die Werte des [PointF](/psd/python-net/aspose.psd/pointf/) auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das [PointF](/psd/python-net/aspose.psd/pointf/) das konvertiert werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) in den diese Methode konvertiert. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Verschiebt dieses [Point](/psd/python-net/aspose.psd/point/) um den angegebenen Betrag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dx | int | Der Betrag, um den die x‑Koordinate verschoben wird. |
| dy | int | Der Betrag, um den die y‑Koordinate verschoben wird. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Verschiebt dieses [Point](/psd/python-net/aspose.psd/point/) um das angegebene [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) der verwendet wird, um dieses [Point](/psd/python-net/aspose.psd/point/) zu verschieben. |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Konvertiert das angegebene [PointF](/psd/python-net/aspose.psd/pointf/) in ein [Point](/psd/python-net/aspose.psd/point/)‑Objekt, indem die Werte des [Point](/psd/python-net/aspose.psd/point/) auf die nächste ganze Zahl gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das [PointF](/psd/python-net/aspose.psd/pointf/) das konvertiert werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) in den diese Methode konvertiert. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Gibt das Ergebnis der Subtraktion der angegebenen [Size](/psd/python-net/aspose.psd/size/) vom angegebenen [Point](/psd/python-net/aspose.psd/point/) zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) von dem subtrahiert wird. |
| size | [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) die von <paramref name="point" /> subtrahiert wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) der das Ergebnis der Subtraktionsoperation ist. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Konvertiert das angegebene [PointF](/psd/python-net/aspose.psd/pointf/) in ein [Point](/psd/python-net/aspose.psd/point/), indem die Werte des [Point](/psd/python-net/aspose.psd/point/) abgeschnitten werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das [PointF](/psd/python-net/aspose.psd/pointf/) das konvertiert werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/) in den diese Methode konvertiert. |


