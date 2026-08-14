---
title: "SizeF Klasse"
type: docs
weight: 4090
url: /de/python-net/aspose.psd/sizef/
---

**Summary:** Stores an ordered pair of floating-point numbers, typically the width and height of a rectangle.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.SizeF

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SizeF()](#SizeF__1) | Initialisiert eine neue Instanz der SizeF Klasse |
| [SizeF(point)](#SizeF_point_2) | Initialisiert eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur aus dem angegebenen [PointF](/psd/python-net/aspose.psd/pointf/). |
| [SizeF(size)](#SizeF_size_3) | Initialisiert eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur aus dem angegebenen [SizeF](/psd/python-net/aspose.psd/sizef/). |
| [SizeF(width, height)](#SizeF_width_height_4) | Initialisiert eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur aus den angegebenen Abmessungen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Gibt eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur zurück, deren [SizeF.width](/psd/python-net/aspose.psd/sizef/) und [SizeF.height](/psd/python-net/aspose.psd/sizef/) Werte auf Null gesetzt sind. |
| height | float | r/w | Liest oder setzt die vertikale Komponente dieses [SizeF](/psd/python-net/aspose.psd/sizef/). |
| is_empty | bool | r | Liest einen Wert, der angibt, ob dieses [SizeF](/psd/python-net/aspose.psd/sizef/) eine Breite und Höhe von Null hat. |
| width | float | r/w | Liest oder setzt die horizontale Komponente dieses [SizeF](/psd/python-net/aspose.psd/sizef/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Addiert die Breite und Höhe einer [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur zur Breite und Höhe einer anderen [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur. |
| [subtract(size1, size2)](#subtract_size1_size2_2) | Subtrahiert die Breite und Höhe einer [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur von der Breite und Höhe einer anderen [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur. |
| [to_point_f()](#to_point_f__3) | Konvertiert ein [SizeF](/psd/python-net/aspose.psd/sizef/) zu einem [PointF](/psd/python-net/aspose.psd/pointf/). |
| [to_size()](#to_size__4) | Konvertiert ein [SizeF](/psd/python-net/aspose.psd/sizef/) zu einer [Size](/psd/python-net/aspose.psd/size/) Struktur mit abgeschnittenen Größenwerten. |


### Constructor: SizeF() {#SizeF__1}


```
 SizeF() 
```

Initialisiert eine neue Instanz der SizeF Klasse

### Constructor: SizeF(point) {#SizeF_point_2}


```
 SizeF(point) 
```

Initialisiert eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur aus dem angegebenen [PointF](/psd/python-net/aspose.psd/pointf/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Der [PointF](/psd/python-net/aspose.psd/pointf/), von dem aus dieses [SizeF](/psd/python-net/aspose.psd/sizef/) initialisiert wird. |

### Constructor: SizeF(size) {#SizeF_size_3}


```
 SizeF(size) 
```

Initialisiert eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur aus dem angegebenen [SizeF](/psd/python-net/aspose.psd/sizef/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Das [SizeF](/psd/python-net/aspose.psd/sizef/), von dem aus das neue [SizeF](/psd/python-net/aspose.psd/sizef/) erstellt wird. |

### Constructor: SizeF(width, height) {#SizeF_width_height_4}


```
 SizeF(width, height) 
```

Initialisiert eine neue Instanz der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur aus den angegebenen Abmessungen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | float | Die Breitenkomponente des neuen [SizeF](/psd/python-net/aspose.psd/sizef/). |
| height | float | Die Höhenkomponente des neuen [SizeF](/psd/python-net/aspose.psd/sizef/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Addiert die Breite und Höhe einer [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur zur Breite und Höhe einer anderen [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Das erste [SizeF](/psd/python-net/aspose.psd/sizef/) zum Hinzufügen. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Das zweite [SizeF](/psd/python-net/aspose.psd/sizef/) zum Hinzufügen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Eine [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur, die das Ergebnis der Additionsoperation ist. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_2}


```
 subtract(size1, size2) 
```

Subtrahiert die Breite und Höhe einer [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur von der Breite und Höhe einer anderen [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [SizeF](/psd/python-net/aspose.psd/sizef) | Die [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [SizeF](/psd/python-net/aspose.psd/sizef) | Die [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SizeF](/psd/python-net/aspose.psd/sizef) | Das [SizeF](/psd/python-net/aspose.psd/sizef/), das das Ergebnis der Subtraktionsoperation ist. |


### Method: to_point_f() {#to_point_f__3}


```
 to_point_f() 
```

Konvertiert ein [SizeF](/psd/python-net/aspose.psd/sizef/) zu einem [PointF](/psd/python-net/aspose.psd/pointf/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PointF](/psd/python-net/aspose.psd/pointf) | Gibt eine [PointF](/psd/python-net/aspose.psd/pointf/) Struktur zurück. |


### Method: to_size() {#to_size__4}


```
 to_size() 
```

Konvertiert ein [SizeF](/psd/python-net/aspose.psd/sizef/) zu einer [Size](/psd/python-net/aspose.psd/size/) Struktur mit abgeschnittenen Größenwerten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Gibt eine [Size](/psd/python-net/aspose.psd/size/) Struktur zurück. |


