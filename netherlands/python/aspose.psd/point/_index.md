---
title: "Point Klasse"
type: docs
weight: 3530
url: /nl/python-net/aspose.psd/point/
---

**Summary:** Represents an ordered pair of integer x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Point

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Point()](#Point__1) | Initialiseert een nieuw exemplaar van de Point-klasse |
| [Point(dw)](#Point_dw_2) | Initialiseert een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur met coördinaten opgegeven door een geheel getal. |
| [Point(size)](#Point_size_3) | Initialiseert een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur vanuit de [Size](/psd/python-net/aspose.psd/size/) structuur. |
| [Point(x, y)](#Point_x_y_4) | Initialiseert een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur met de opgegeven coördinaten. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| empty [static] | [Point](/psd/python-net/aspose.psd/point) | r | Haalt een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur op dat [Point.x](/psd/python-net/aspose.psd/point/) en [Point.y](/psd/python-net/aspose.psd/point/) waarden op nul heeft ingesteld. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of deze [Point](/psd/python-net/aspose.psd/point/) leeg is. |
| x | int | r/w | Haalt de x-coördinaat van deze [Point](/psd/python-net/aspose.psd/point/) op of stelt deze in. |
| y | int | r/w | Haalt de y-coördinaat van deze [Point](/psd/python-net/aspose.psd/point/) op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Voegt de opgegeven [Size](/psd/python-net/aspose.psd/size/) toe aan de opgegeven [Point](/psd/python-net/aspose.psd/point/). |
| [ceiling(point)](#ceiling_point_2) | Converteert de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) naar een [Point](/psd/python-net/aspose.psd/point/) door de waarden van de [PointF](/psd/python-net/aspose.psd/pointf/) af te ronden naar de eerstvolgende hogere gehele getallen. |
| [offset(dx, dy)](#offset_dx_dy_3) | Verplaatst dit [Point](/psd/python-net/aspose.psd/point/) met de opgegeven hoeveelheid. |
| [offset(point)](#offset_point_4) | Verplaatst dit [Point](/psd/python-net/aspose.psd/point/) met de opgegeven [Point](/psd/python-net/aspose.psd/point/). |
| [round(point)](#round_point_5) | Converteert de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) naar een [Point](/psd/python-net/aspose.psd/point/) object door de [Point](/psd/python-net/aspose.psd/point/) waarden af te ronden naar het dichtstbijzijnde gehele getal. |
| [subtract(point, size)](#subtract_point_size_6) | Retourneert het resultaat van het aftrekken van de opgegeven [Size](/psd/python-net/aspose.psd/size/) van de opgegeven [Point](/psd/python-net/aspose.psd/point/). |
| [truncate(point)](#truncate_point_7) | Converteert de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) naar een [Point](/psd/python-net/aspose.psd/point/) door de waarden van de [Point](/psd/python-net/aspose.psd/point/) af te kappen. |


### Constructor: Point() {#Point__1}


```
 Point() 
```

Initialiseert een nieuw exemplaar van de Point-klasse

### Constructor: Point(dw) {#Point_dw_2}


```
 Point(dw) 
```

Initialiseert een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur met coördinaten opgegeven door een geheel getal.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dw | int | Een 32-bits geheel getal dat de coördinaten voor het nieuwe punt specificeert. |

### Constructor: Point(size) {#Point_size_3}


```
 Point(size) 
```

Initialiseert een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur vanuit de [Size](/psd/python-net/aspose.psd/size/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [Size](/psd/python-net/aspose.psd/size) | Bevat de coördinaten van het nieuwe punt. |

### Constructor: Point(x, y) {#Point_x_y_4}


```
 Point(x, y) 
```

Initialiseert een nieuw exemplaar van de [Point](/psd/python-net/aspose.psd/point/) structuur met de opgegeven coördinaten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De horizontale positie van het punt. |
| y | int | De verticale positie van het punt. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Voegt de opgegeven [Size](/psd/python-net/aspose.psd/size/) toe aan de opgegeven [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) om aan toe te voegen. |
| size | [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) om toe te voegen aan de <paramref name="point" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) dat het resultaat is van de optelling. |


### Method: ceiling(point)  [static] {#ceiling_point_2}


```
 ceiling(point) 
```

Converteert de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) naar een [Point](/psd/python-net/aspose.psd/point/) door de waarden van de [PointF](/psd/python-net/aspose.psd/pointf/) af te ronden naar de eerstvolgende hogere gehele getallen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De [PointF](/psd/python-net/aspose.psd/pointf/) om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) waar deze methode naar converteert. |


### Method: offset(dx, dy) {#offset_dx_dy_3}


```
 offset(dx, dy) 
```

Verplaatst dit [Point](/psd/python-net/aspose.psd/point/) met de opgegeven hoeveelheid.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dx | int | De hoeveelheid om de x-coördinaat te verschuiven. |
| dy | int | De hoeveelheid om de y-coördinaat te verschuiven. |

### Method: offset(point) {#offset_point_4}


```
 offset(point) 
```

Verplaatst dit [Point](/psd/python-net/aspose.psd/point/) met de opgegeven [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) dat wordt gebruikt om dit [Point](/psd/python-net/aspose.psd/point/) te verschuiven. |

### Method: round(point)  [static] {#round_point_5}


```
 round(point) 
```

Converteert de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) naar een [Point](/psd/python-net/aspose.psd/point/) object door de [Point](/psd/python-net/aspose.psd/point/) waarden af te ronden naar het dichtstbijzijnde gehele getal.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De [PointF](/psd/python-net/aspose.psd/pointf/) om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) waar deze methode naar converteert. |


### Method: subtract(point, size)  [static] {#subtract_point_size_6}


```
 subtract(point, size) 
```

Retourneert het resultaat van het aftrekken van de opgegeven [Size](/psd/python-net/aspose.psd/size/) van de opgegeven [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) waarvan afgetrokken wordt. |
| size | [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) om af te trekken van de <paramref name="point" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) dat het resultaat is van de aftrekking. |


### Method: truncate(point)  [static] {#truncate_point_7}


```
 truncate(point) 
```

Converteert de opgegeven [PointF](/psd/python-net/aspose.psd/pointf/) naar een [Point](/psd/python-net/aspose.psd/point/) door de waarden van de [Point](/psd/python-net/aspose.psd/point/) af te kappen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De [PointF](/psd/python-net/aspose.psd/pointf/) om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) waar deze methode naar converteert. |


