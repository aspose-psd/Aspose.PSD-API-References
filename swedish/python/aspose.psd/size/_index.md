---
title: "Size-klass"
type: docs
weight: 4080
url: /sv/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Size()](#Size__1) | Initierar en ny instans av Size-klassen |
| [Size(point)](#Size_point_2) | Initierar en ny instans av strukturen [Size](/psd/python-net/aspose.psd/size/) från den angivna [Point](/psd/python-net/aspose.psd/point/). |
| [Size(width, height)](#Size_width_height_3) | Initierar en ny instans av strukturen [Size](/psd/python-net/aspose.psd/size/) från de angivna dimensionerna. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Hämtar en ny instans av strukturen [Size](/psd/python-net/aspose.psd/size/) som har [Size.width](/psd/python-net/aspose.psd/size/) och [Size.height](/psd/python-net/aspose.psd/size/) värden satta till noll. |
| height | int | r/w | Hämtar eller anger den vertikala komponenten för detta [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Hämtar ett värde som indikerar om detta [Size](/psd/python-net/aspose.psd/size/) har bredd och höjd på 0. |
| width | int | r/w | Hämtar eller anger den horisontella komponenten för detta [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Lägger till bredden och höjden av en [Size](/psd/python-net/aspose.psd/size/) struktur till bredden och höjden av en annan [Size](/psd/python-net/aspose.psd/size/) struktur. |
| [ceiling(size)](#ceiling_size_2) | Konverterar den angivna [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till en [Size](/psd/python-net/aspose.psd/size/) struktur genom att avrunda värdena i [Size](/psd/python-net/aspose.psd/size/) strukturen till nästa högre heltalsvärde. |
| [round(size)](#round_size_3) | Konverterar den angivna [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till en [Size](/psd/python-net/aspose.psd/size/) struktur genom att avrunda värdena i [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till närmaste heltal. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtraherar bredden och höjden av en [Size](/psd/python-net/aspose.psd/size/) struktur från bredden och höjden av en annan [Size](/psd/python-net/aspose.psd/size/) struktur. |
| [truncate(size)](#truncate_size_5) | Konverterar den angivna [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till en [Size](/psd/python-net/aspose.psd/size/) struktur genom att trunkera värdena i [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till nästa lägre heltalsvärde. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initierar en ny instans av Size-klassen

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initierar en ny instans av strukturen [Size](/psd/python-net/aspose.psd/size/) från den angivna [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Den [Point](/psd/python-net/aspose.psd/point/) från vilken detta [Size](/psd/python-net/aspose.psd/size/) ska initieras. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initierar en ny instans av strukturen [Size](/psd/python-net/aspose.psd/size/) från de angivna dimensionerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Den breddkomponenten för den nya [Size](/psd/python-net/aspose.psd/size/). |
| height | int | Den höjskomponenten för den nya [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Lägger till bredden och höjden av en [Size](/psd/python-net/aspose.psd/size/) struktur till bredden och höjden av en annan [Size](/psd/python-net/aspose.psd/size/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Den första [Size](/psd/python-net/aspose.psd/size/) att lägga till. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Den andra [Size](/psd/python-net/aspose.psd/size/) att lägga till. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | En [Size](/psd/python-net/aspose.psd/size/) struktur som är resultatet av additionsoperationen. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Konverterar den angivna [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till en [Size](/psd/python-net/aspose.psd/size/) struktur genom att avrunda värdena i [Size](/psd/python-net/aspose.psd/size/) strukturen till nästa högre heltalsvärde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) struktur som den här metoden konverterar till. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Konverterar den angivna [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till en [Size](/psd/python-net/aspose.psd/size/) struktur genom att avrunda värdena i [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till närmaste heltal.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) struktur som den här metoden konverterar till. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtraherar bredden och höjden av en [Size](/psd/python-net/aspose.psd/size/) struktur från bredden och höjden av en annan [Size](/psd/python-net/aspose.psd/size/) struktur.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) struktur på vänster sida av subtraktionsoperatorn. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) struktur på höger sida av subtraktionsoperatorn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) som är resultatet av subtraktionsoperationen. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Konverterar den angivna [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till en [Size](/psd/python-net/aspose.psd/size/) struktur genom att trunkera värdena i [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen till nästa lägre heltalsvärde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Den [SizeF](/psd/python-net/aspose.psd/sizef/) strukturen att konvertera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Den [Size](/psd/python-net/aspose.psd/size/) struktur som den här metoden konverterar till. |


