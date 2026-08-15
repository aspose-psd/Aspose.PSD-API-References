---
title: "Size-klasse"
type: docs
weight: 4080
url: /nl/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Size()](#Size__1) | Initialiseert een nieuw exemplaar van de Size-klasse |
| [Size(point)](#Size_point_2) | Initialiseert een nieuw exemplaar van de [Size](/psd/python-net/aspose.psd/size/) structuur vanuit het opgegeven [Point](/psd/python-net/aspose.psd/point/). |
| [Size(width, height)](#Size_width_height_3) | Initialiseert een nieuw exemplaar van de [Size](/psd/python-net/aspose.psd/size/) structuur vanuit de opgegeven afmetingen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Haalt een nieuw exemplaar van de [Size](/psd/python-net/aspose.psd/size/) structuur op dat [Size.width](/psd/python-net/aspose.psd/size/) en [Size.height](/psd/python-net/aspose.psd/size/) waarden heeft ingesteld op nul. |
| height | int | r/w | Haalt of stelt het verticale component van deze [Size](/psd/python-net/aspose.psd/size/) in. |
| is_empty | bool | r | Haalt een waarde op die aangeeft of deze [Size](/psd/python-net/aspose.psd/size/) een breedte en hoogte van 0 heeft. |
| width | int | r/w | Haalt of stelt het horizontale component van deze [Size](/psd/python-net/aspose.psd/size/) in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Voegt de breedte en hoogte van één [Size](/psd/python-net/aspose.psd/size/) structuur toe aan de breedte en hoogte van een andere [Size](/psd/python-net/aspose.psd/size/) structuur. |
| [ceiling(size)](#ceiling_size_2) | Converteert de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/) structuur naar een [Size](/psd/python-net/aspose.psd/size/) structuur door de waarden van de [Size](/psd/python-net/aspose.psd/size/) structuur af te ronden naar de eerstvolgende hogere gehele getallen. |
| [round(size)](#round_size_3) | Converteert de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/) structuur naar een [Size](/psd/python-net/aspose.psd/size/) structuur door de waarden van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur af te ronden op de dichtstbijzijnde gehele getallen. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Trekt de breedte en hoogte van één [Size](/psd/python-net/aspose.psd/size/) structuur af van de breedte en hoogte van een andere [Size](/psd/python-net/aspose.psd/size/) structuur. |
| [truncate(size)](#truncate_size_5) | Converteert de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/) structuur naar een [Size](/psd/python-net/aspose.psd/size/) structuur door de waarden van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur af te kappen tot de eerstvolgende lagere gehele getallen. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initialiseert een nieuw exemplaar van de Size-klasse

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initialiseert een nieuw exemplaar van de [Size](/psd/python-net/aspose.psd/size/) structuur vanuit het opgegeven [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Het [Point](/psd/python-net/aspose.psd/point/) waarvan deze [Size](/psd/python-net/aspose.psd/size/) moet worden geïnitialiseerd. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initialiseert een nieuw exemplaar van de [Size](/psd/python-net/aspose.psd/size/) structuur vanuit de opgegeven afmetingen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De breedtecomponent van de nieuwe [Size](/psd/python-net/aspose.psd/size/). |
| height | int | De hoogtecomponent van de nieuwe [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Voegt de breedte en hoogte van één [Size](/psd/python-net/aspose.psd/size/) structuur toe aan de breedte en hoogte van een andere [Size](/psd/python-net/aspose.psd/size/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | De eerste [Size](/psd/python-net/aspose.psd/size/) om toe te voegen. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | De tweede [Size](/psd/python-net/aspose.psd/size/) om toe te voegen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Een [Size](/psd/python-net/aspose.psd/size/) structuur die het resultaat is van de opteloperatie. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Converteert de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/) structuur naar een [Size](/psd/python-net/aspose.psd/size/) structuur door de waarden van de [Size](/psd/python-net/aspose.psd/size/) structuur af te ronden naar de eerstvolgende hogere gehele getallen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) structuur om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) structuur waar deze methode naar converteert. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Converteert de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/) structuur naar een [Size](/psd/python-net/aspose.psd/size/) structuur door de waarden van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur af te ronden op de dichtstbijzijnde gehele getallen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) structuur om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) structuur waar deze methode naar converteert. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Trekt de breedte en hoogte van één [Size](/psd/python-net/aspose.psd/size/) structuur af van de breedte en hoogte van een andere [Size](/psd/python-net/aspose.psd/size/) structuur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) structuur aan de linkerkant van de aftreksomoperator. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) structuur aan de rechterkant van de aftreksomoperator. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) die het resultaat is van de aftreksom. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Converteert de opgegeven [SizeF](/psd/python-net/aspose.psd/sizef/) structuur naar een [Size](/psd/python-net/aspose.psd/size/) structuur door de waarden van de [SizeF](/psd/python-net/aspose.psd/sizef/) structuur af te kappen tot de eerstvolgende lagere gehele getallen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | De [SizeF](/psd/python-net/aspose.psd/sizef/) structuur om te converteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | De [Size](/psd/python-net/aspose.psd/size/) structuur waar deze methode naar converteert. |


