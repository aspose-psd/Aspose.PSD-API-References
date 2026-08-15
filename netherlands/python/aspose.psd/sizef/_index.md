---
title: "SizeF-klasse"
type: docs
weight: 4090
url: /nl/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initialiseert een nieuw exemplaar van de SizeF-klasse |
| [SizeF(point)](#SizeF_point_2) | Initialiseert een nieuw exemplaar van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur vanuit het opgegeven [PointF](/psd/python-net/aspose.psd/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initialiseert een nieuw exemplaar van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur vanuit de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initialiseert een nieuw exemplaar van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur vanuit de opgegeven afmetingen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Haalt een nieuw exemplaar op van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur waarvan de waarden van [SizeF.width](/psd/python-net/aspose.psd/sizef/) en [SizeF.height](/psd/python-net/aspose.psd/sizef/) op nul zijn gezet. |
| height | float | r/w | Haalt op of stelt de verticale component van deze [SizeF](/psd/python-net/aspose.psd/sizef/) in. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of deze [SizeF](/psd/python-net/aspose.psd/sizef/) een breedte en hoogte van nul heeft. |
| width | float | r/w | Haalt op of stelt de horizontale component van deze [SizeF](/psd/python-net/aspose.psd/sizef/) in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Voegt de breedte en hoogte van één [SizeF](/psd/python-net/aspose.psd/sizef/) structuur toe aan de breedte en hoogte van een andere [SizeF](/psd/python-net/aspose.psd/sizef/) structuur. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Trekt de breedte en hoogte van één [SizeF](/psd/python-net/aspose.psd/sizef/) structuur af van de breedte en hoogte van een andere [SizeF](/psd/python-net/aspose.psd/sizef/) structuur. |
| [to_point_f()](#to_point_f__3) | Converteert een [SizeF](/psd/python-net/aspose.psd/sizef/) naar een [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Converteert een [SizeF](/psd/python-net/aspose.psd/sizef/) naar een [Size](/psd/python-net/aspose.psd/size/) structuur met afgekorte groottewaarden. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initialiseert een nieuw exemplaar van de SizeF-klasse

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initialiseert een nieuw exemplaar van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur vanuit het opgegeven [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | De [PointF](/psd/python-net/aspose.psd/pointf/) waarvan dit [SizeF](/psd/python-net/aspose.psd/sizef/) moet worden geïnitialiseerd. |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initialiseert een nieuw exemplaar van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur vanuit de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) waarvan de nieuwe [SizeF](/psd/python-net/aspose.psd/sizef/) moet worden gemaakt. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initialiseert een nieuw exemplaar van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur vanuit de opgegeven afmetingen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | float | De breedtecomponent van de nieuwe [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | De hoogtecomponent van de nieuwe [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Voegt de breedte en hoogte van één [SizeF](/psd/python-net/aspose.psd/sizef/) structuur toe aan de breedte en hoogte van een andere [SizeF](/psd/python-net/aspose.psd/sizef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | De eerste [SizeF](/psd/python-net/aspose.psd/sizef/) om toe te voegen. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | De tweede [SizeF](/psd/python-net/aspose.psd/sizef/) om toe te voegen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Een [SizeF](/psd/python-net/aspose.psd/sizef/) structuur die het resultaat is van de optelling. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Trekt de breedte en hoogte van één [SizeF](/psd/python-net/aspose.psd/sizef/) structuur af van de breedte en hoogte van een andere [SizeF](/psd/python-net/aspose.psd/sizef/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) structuur aan de linkerkant van de aftreksomoperator. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) structuur aan de rechterkant van de aftreksomoperator. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) die het resultaat is van de aftreksom. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Converteert een [SizeF](/psd/python-net/aspose.psd/sizef/) naar een [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Retourneert een [PointF](/psd/python-net/aspose.psd/pointf/) structuur. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Converteert een [SizeF](/psd/python-net/aspose.psd/sizef/) naar een [Size](/psd/python-net/aspose.psd/size/) structuur met afgekorte groottewaarden.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Retourneert een [Size](/psd/python-net/aspose.psd/size/) structuur. |


