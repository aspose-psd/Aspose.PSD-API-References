---
title: "Größenklasse"
type: docs
weight: 4080
url: /de/python-net/aspose.psd/size/
---

**Summary:** Represents size.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Size

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Size()](#Size__1) | Initialisiert eine neue Instanz der Size-Klasse |
| [Size(point)](#Size_point_2) | Initialisiert eine neue Instanz der [Size](/psd/python-net/aspose.psd/size/) Struktur aus dem angegebenen [Point](/psd/python-net/aspose.psd/point/). |
| [Size(width, height)](#Size_width_height_3) | Initialisiert eine neue Instanz der [Size](/psd/python-net/aspose.psd/size/) Struktur aus den angegebenen Abmessungen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| empty [static] | [Size](/psd/python-net/aspose.psd/size) | r | Gibt eine neue Instanz der [Size](/psd/python-net/aspose.psd/size/) Struktur zurück, bei der die Werte von [Size.width](/psd/python-net/aspose.psd/size/) und [Size.height](/psd/python-net/aspose.psd/size/) auf Null gesetzt sind. |
| height | int | r/w | Liest oder setzt die vertikale Komponente dieses [Size](/psd/python-net/aspose.psd/size/). |
| is_empty | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [Size](/psd/python-net/aspose.psd/size/) Breite und Höhe von 0 hat. |
| width | int | r/w | Liest oder setzt die horizontale Komponente dieses [Size](/psd/python-net/aspose.psd/size/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(size1, size2)](#add_size1_size2_1) | Addiert die Breite und Höhe einer [Size](/psd/python-net/aspose.psd/size/) Struktur zur Breite und Höhe einer anderen [Size](/psd/python-net/aspose.psd/size/) Struktur. |
| [ceiling(size)](#ceiling_size_2) | Konvertiert die angegebene [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur in eine [Size](/psd/python-net/aspose.psd/size/) Struktur, indem die Werte der [Size](/psd/python-net/aspose.psd/size/) Struktur auf die nächsthöheren Ganzzahlen gerundet werden. |
| [round(size)](#round_size_3) | Konvertiert die angegebene [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur in eine [Size](/psd/python-net/aspose.psd/size/) Struktur, indem die Werte der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur auf die nächsten Ganzzahlen gerundet werden. |
| [subtract(size1, size2)](#subtract_size1_size2_4) | Subtrahiert die Breite und Höhe einer [Size](/psd/python-net/aspose.psd/size/) Struktur von der Breite und Höhe einer anderen [Size](/psd/python-net/aspose.psd/size/) Struktur. |
| [truncate(size)](#truncate_size_5) | Konvertiert die angegebene [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur in eine [Size](/psd/python-net/aspose.psd/size/) Struktur, indem die Werte der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden. |


### Constructor: Size() {#Size__1}


```
 Size() 
```

Initialisiert eine neue Instanz der Size-Klasse

### Constructor: Size(point) {#Size_point_2}


```
 Size(point) 
```

Initialisiert eine neue Instanz der [Size](/psd/python-net/aspose.psd/size/) Struktur aus dem angegebenen [Point](/psd/python-net/aspose.psd/point/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Der [Point](/psd/python-net/aspose.psd/point/), aus dem diese [Size](/psd/python-net/aspose.psd/size/) initialisiert wird. |

### Constructor: Size(width, height) {#Size_width_height_3}


```
 Size(width, height) 
```

Initialisiert eine neue Instanz der [Size](/psd/python-net/aspose.psd/size/) Struktur aus den angegebenen Abmessungen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breitenkomponente der neuen [Size](/psd/python-net/aspose.psd/size/). |
| height | int | Die Höhenkomponente der neuen [Size](/psd/python-net/aspose.psd/size/). |

### Method: add(size1, size2)  [static] {#add_size1_size2_1}


```
 add(size1, size2) 
```

Addiert die Breite und Höhe einer [Size](/psd/python-net/aspose.psd/size/) Struktur zur Breite und Höhe einer anderen [Size](/psd/python-net/aspose.psd/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Das erste [Size](/psd/python-net/aspose.psd/size/) zum Hinzufügen. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Das zweite [Size](/psd/python-net/aspose.psd/size/) zum Hinzufügen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Eine [Size](/psd/python-net/aspose.psd/size/) Struktur, die das Ergebnis der Additionsoperation ist. |


### Method: ceiling(size)  [static] {#ceiling_size_2}


```
 ceiling(size) 
```

Konvertiert die angegebene [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur in eine [Size](/psd/python-net/aspose.psd/size/) Struktur, indem die Werte der [Size](/psd/python-net/aspose.psd/size/) Struktur auf die nächsthöheren Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Die zu konvertierende [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) Struktur, in die diese Methode konvertiert. |


### Method: round(size)  [static] {#round_size_3}


```
 round(size) 
```

Konvertiert die angegebene [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur in eine [Size](/psd/python-net/aspose.psd/size/) Struktur, indem die Werte der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur auf die nächsten Ganzzahlen gerundet werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Die zu konvertierende [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) Struktur, in die diese Methode konvertiert. |


### Method: subtract(size1, size2)  [static] {#subtract_size1_size2_4}


```
 subtract(size1, size2) 
```

Subtrahiert die Breite und Höhe einer [Size](/psd/python-net/aspose.psd/size/) Struktur von der Breite und Höhe einer anderen [Size](/psd/python-net/aspose.psd/size/) Struktur.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size1 | [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) Struktur auf der linken Seite des Subtraktionsoperators. |
| size2 | [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) Struktur auf der rechten Seite des Subtraktionsoperators. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) die das Ergebnis der Subtraktionsoperation ist. |


### Method: truncate(size)  [static] {#truncate_size_5}


```
 truncate(size) 
```

Konvertiert die angegebene [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur in eine [Size](/psd/python-net/aspose.psd/size/) Struktur, indem die Werte der [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur auf die nächstniedrigeren Ganzzahlen abgeschnitten werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size | [SizeF](/psd/python-net/aspose.psd/sizef) | Die zu konvertierende [SizeF](/psd/python-net/aspose.psd/sizef/) Struktur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Size](/psd/python-net/aspose.psd/size) | Die [Size](/psd/python-net/aspose.psd/size/) Struktur, in die diese Methode konvertiert. |


