---
title: "SizeF-klass"
type: docs
weight: 4090
url: /sv/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initierar en ny instans av SizeF-klassen |
| [SizeF(point)](#SizeF_point_2) | Initierar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen från den angivna [PointF](/psd/python-net/aspose.psd/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initierar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen från den angivna [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initierar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen från de angivna dimensionerna. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Hämtar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen som har [SizeF.width](/psd/python-net/aspose.psd/sizef/) och [SizeF.height](/psd/python-net/aspose.psd/sizef/) värden satta till noll. |
| height | float | r/w | Hämtar eller anger den vertikala komponenten i detta [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Hämtar ett värde som indikerar om detta [SizeF](/psd/python-net/aspose.psd/sizef/) har noll bredd och höjd. |
| width | float | r/w | Hämtar eller anger den horisontella komponenten i detta [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Lägger till bredden och höjden av en [SizeF](/psd/python-net/aspose.psd/sizef/) struktur till bredden och höjden av en annan [SizeF](/psd/python-net/aspose.psd/sizef/) struktur. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Subtraherar bredden och höjden av en [SizeF](/psd/python-net/aspose.psd/sizef/) struktur från bredden och höjden av en annan [SizeF](/psd/python-net/aspose.psd/sizef/) struktur. |
| [to_point_f()](#to_point_f__3) | Konverterar en [SizeF](/psd/python-net/aspose.psd/sizef/) till en [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Konverterar en [SizeF](/psd/python-net/aspose.psd/sizef/) till en [Size](/psd/python-net/aspose.psd/size/) struktur med trunkerade storleksvärden. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initierar en ny instans av SizeF-klassen

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initierar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen från den angivna [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Den [PointF](/psd/python-net/aspose.psd/pointf/) som ska initiera detta [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initierar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen från den angivna [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) från vilken den nya [SizeF](/psd/python-net/aspose.psd/sizef/) ska skapas. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initierar en ny instans av [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen från de angivna dimensionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | float | Breddkomponenten för den nya [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | Höjdkomponenten för den nya [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Lägger till bredden och höjden av en [SizeF](/psd/python-net/aspose.psd/sizef/) struktur till bredden och höjden av en annan [SizeF](/psd/python-net/aspose.psd/sizef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Den första [SizeF](/psd/python-net/aspose.psd/sizef/) att lägga till. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Den andra [SizeF](/psd/python-net/aspose.psd/sizef/) att lägga till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | En [SizeF](/psd/python-net/aspose.psd/sizef/) struktur som är resultatet av additionsoperationen. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Subtraherar bredden och höjden av en [SizeF](/psd/python-net/aspose.psd/sizef/) struktur från bredden och höjden av en annan [SizeF](/psd/python-net/aspose.psd/sizef/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen på vänster sida av subtraktionsoperatorn. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen på höger sida av subtraktionsoperatorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) som är resultatet av subtraktionsoperationen. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Konverterar en [SizeF](/psd/python-net/aspose.psd/sizef/) till en [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Returnerar en [PointF](/psd/python-net/aspose.psd/pointf/) struktur. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Konverterar en [SizeF](/psd/python-net/aspose.psd/sizef/) till en [Size](/psd/python-net/aspose.psd/size/) struktur med trunkerade storleksvärden.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Returnerar en [Size](/psd/python-net/aspose.psd/size/) struktur. |


