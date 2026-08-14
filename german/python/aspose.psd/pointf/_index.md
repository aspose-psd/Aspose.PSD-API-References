---
title: "PointF Klasse"
type: docs
weight: 3550
url: /de/python-net/aspose.psd/pointf/
---

**Summary:** Represents an ordered pair of floating-point x- and y-coordinates that defines a point in a two-dimensional plane.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.PointF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PointF()](#PointF__1) | Initialisiert eine neue Instanz der PointF Klasse |
| [PointF(x, y)](#PointF_x_y_2) | Initialisiert eine neue Instanz der [PointF](/psd/python-net/aspose.psd/pointf/) Struktur mit den angegebenen Koordinaten. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [PointF](/psd/python-net/aspose.psd/pointf) | r | Ruft eine neue Instanz der [PointF](/psd/python-net/aspose.psd/pointf/) Struktur ab, bei der die Werte von [PointF.x](/psd/python-net/aspose.psd/pointf/) und [PointF.y](/psd/python-net/aspose.psd/pointf/) auf Null gesetzt sind. |
| is_empty | bool | r | Ruft einen Wert ab, der angibt, ob dieses [PointF](/psd/python-net/aspose.psd/pointf/) leer ist. |
| x | float | r/w | Ruft die X‑Koordinate dieses [PointF](/psd/python-net/aspose.psd/pointf/) ab oder legt sie fest. |
| y | float | r/w | Ruft die Y‑Koordinate dieses [PointF](/psd/python-net/aspose.psd/pointf/) ab oder legt sie fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(point, size)](#add_point_size_1) | Verschiebt ein gegebenes [PointF](/psd/python-net/aspose.psd/pointf/) um die angegebene [Size](/psd/python-net/aspose.psd/size/). |
| [add(point, size)](#add_point_size_2) | Verschiebt ein gegebenes [PointF](/psd/python-net/aspose.psd/pointf/) um die angegebene [Size](/psd/python-net/aspose.psd/size/). |
| [subtract(point, size)](#subtract_point_size_3) | Verschiebt ein [PointF](/psd/python-net/aspose.psd/pointf/) um das Negative einer angegebenen Größe. |
| [subtract(point, size)](#subtract_point_size_4) | Verschiebt ein [PointF](/psd/python-net/aspose.psd/pointf/) um das Negative einer angegebenen Größe. |


### Constructor: PointF() {#PointF__1}


```
 PointF() 
```

Initialisiert eine neue Instanz der PointF Klasse

### Constructor: PointF(x, y) {#PointF_x_y_2}


```
 PointF(x, y) 
```

Initialisiert eine neue Instanz der [PointF](/psd/python-net/aspose.psd/pointf/) Struktur mit den angegebenen Koordinaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | float | Die horizontale Position des Punktes. |
| y | float | Die vertikale Position des Punktes. |

### Method: add(point, size)  [static] {#add_point_size_1}


```
 add(point, size) 
```

Verschiebt ein gegebenes [PointF](/psd/python-net/aspose.psd/pointf/) um die angegebene [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das zu verschiebende [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/), die die Zahlen angibt, die zu den Koordinaten von <paramref name=\"point\" /> addiert werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Das übersetzte [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: add(point, size)  [static] {#add_point_size_2}


```
 add(point, size) 
```

Verschiebt ein gegebenes [PointF](/psd/python-net/aspose.psd/pointf/) um die angegebene [Size](/psd/python-net/aspose.psd/size/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das zu verschiebende [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Die [Size](/psd/python-net/aspose.psd/size/), die die Zahlen angibt, die zu den Koordinaten von <paramref name=\"point\" /> addiert werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Das übersetzte [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_3}


```
 subtract(point, size) 
```

Verschiebt ein [PointF](/psd/python-net/aspose.psd/pointf/) um das Negative einer angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das zu verschiebende [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/), die die Zahlen angibt, die von den Koordinaten von <paramref name=\"point\" /> subtrahiert werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Das übersetzte [PointF](/psd/python-net/aspose.psd/pointf/). |


### Method: subtract(point, size)  [static] {#subtract_point_size_4}


```
 subtract(point, size) 
```

Verschiebt ein [PointF](/psd/python-net/aspose.psd/pointf/) um das Negative einer angegebenen Größe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Das zu verschiebende [PointF](/psd/python-net/aspose.psd/pointf/). |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Die [Size](/psd/python-net/aspose.psd/size/), die die Zahlen angibt, die von den Koordinaten von <paramref name=\"point\" /> subtrahiert werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Das übersetzte [PointF](/psd/python-net/aspose.psd/pointf/). |


