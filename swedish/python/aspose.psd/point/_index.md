---
title: "Point-klass"
type: docs
weight: 3530
url: /sv/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Point()](#Point__1) | Initierar en ny instans av Point-klassen |
| [Point(dw)](#Point_dw_2) | Initierar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) med koordinater angivna av ett heltalsvärde. |
| [Point(size)](#Point_size_3) | Initierar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) från strukturen [Size](/psd/python-net/aspose.psd/size/). |
| [Point(x, y)](#Point_x_y_4) | Initierar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) med de angivna koordinaterna. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Hämtar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) som har värdena [Point.x](/psd/python-net/aspose.psd/point/) och [Point.y](/psd/python-net/aspose.psd/point/) satta till noll. |
| is_empty | bool | r | Hämtar ett värde som indikerar om denna [Point](/psd/python-net/aspose.psd/point/) är tom. |
| x | int | r/w | Hämtar eller anger x-koordinaten för denna [Point](/psd/python-net/aspose.psd/point/). |
| y | int | r/w | Hämtar eller anger y-koordinaten för denna [Point](/psd/python-net/aspose.psd/point/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Lägger till den angivna [Size](/psd/python-net/aspose.psd/size/) till den angivna [Point](/psd/python-net/aspose.psd/point/). |
| [ceiling(point)](#ceiling_point_2) | Konverterar den angivna [PointF](/psd/python-net/aspose.psd/pointf/) till en [Point](/psd/python-net/aspose.psd/point/) genom att avrunda värdena i [PointF](/psd/python-net/aspose.psd/pointf/) till nästa högre heltalsvärden. |
| [offset(dx, dy)](#offset_dx_dy_3) | Översätter denna [Point](/psd/python-net/aspose.psd/point/) med den angivna mängden. |
| [offset(point)](#offset_point_4) | Översätter denna [Point](/psd/python-net/aspose.psd/point/) med den angivna [Point](/psd/python-net/aspose.psd/point/). |
| [round(point)](#round_point_5) | Konverterar den angivna [PointF](/psd/python-net/aspose.psd/pointf/) till ett [Point](/psd/python-net/aspose.psd/point/)‑objekt genom att avrunda [Point](/psd/python-net/aspose.psd/point/)-värdena till närmaste heltal. |
| [subtract(point, size)](#subtract_point_size_6) | Returnerar resultatet av att subtrahera den angivna [Size](/psd/python-net/aspose.psd/size/) från den angivna [Point](/psd/python-net/aspose.psd/point/). |
| [truncate(point)](#truncate_point_7) | Konverterar den angivna [PointF](/psd/python-net/aspose.psd/pointf/) till en [Point](/psd/python-net/aspose.psd/point/) genom att trunkera värdena i [Point](/psd/python-net/aspose.psd/point/). |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initierar en ny instans av Point-klassen

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initierar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) med koordinater angivna av ett heltalsvärde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dw | int | Ett 32‑bitars heltal som anger koordinaterna för den nya punkten. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initierar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) från strukturen [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Innehåller de nya punktkoordinaterna. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initierar en ny instans av strukturen [Point](/psd/python-net/aspose.psd/point/) med de angivna koordinaterna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Den horisontella positionen för punkten. |
| y | int | Den vertikala positionen för punkten. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Lägger till den angivna [Size](/psd/python-net/aspose.psd/size/) till den angivna [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) att lägga till i. |
| size | [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) att lägga till <paramref name="point" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som är resultatet av additionsoperationen. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Konverterar den angivna [PointF](/psd/python-net/aspose.psd/pointf/) till en [Point](/psd/python-net/aspose.psd/point/) genom att avrunda värdena i [PointF](/psd/python-net/aspose.psd/pointf/) till nästa högre heltalsvärden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) för att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som den här metoden konverterar till. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Översätter denna [Point](/psd/python-net/aspose.psd/point/) med den angivna mängden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dx | int | Mängden för att förskjuta x-koordinaten. |
| dy | int | Mängden för att förskjuta y-koordinaten. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Översätter denna [Point](/psd/python-net/aspose.psd/point/) med den angivna [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som används för att förskjuta denna [Point](/psd/python-net/aspose.psd/point/). |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Konverterar den angivna [PointF](/psd/python-net/aspose.psd/pointf/) till ett [Point](/psd/python-net/aspose.psd/point/)‑objekt genom att avrunda [Point](/psd/python-net/aspose.psd/point/)-värdena till närmaste heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) för att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som den här metoden konverterar till. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Returnerar resultatet av att subtrahera den angivna [Size](/psd/python-net/aspose.psd/size/) från den angivna [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som ska subtraheras från. |
| size | [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) som ska subtraheras från <paramref name="point" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som är resultatet av subtraktionsoperationen. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Konverterar den angivna [PointF](/psd/python-net/aspose.psd/pointf/) till en [Point](/psd/python-net/aspose.psd/point/) genom att trunkera värdena i [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) för att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) som den här metoden konverterar till. |


