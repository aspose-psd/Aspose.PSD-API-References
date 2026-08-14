---
title: "TiffSRational Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initialisiert eine neue Instanz der [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) Klasse. |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initialisiert eine neue Instanz der [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) Klasse. |
| [TiffSRational(value)](#TiffSRational_value_3) | Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| EPSILON [statisch] | double | r | Das Epsilon für die Bruchberechnung |
| Nenner | int | r | Liefert den Nenner. |
| Zähler | int | r | Liefert den Zähler. |
| Wert | float | r | Liefert den Float-Wert. |
| value_d | double | r | Liefert den Double-Wert. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Nähert den angegebenen Wert an einen Bruch. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Nähert den angegebenen Wert an einen Bruch. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Nähert den angegebenen Wert an einen Bruch. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Nähert den angegebenen Wert an einen Bruch. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initialisiert eine neue Instanz der [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) Klasse.

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initialisiert eine neue Instanz der [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zähler | int | Der Zähler. |
| Nenner | int | Der Nenner. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | int | Der Zählerwert. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Nähert den angegebenen Wert an einen Bruch.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | double | Der Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Eine rationale Zahl mit einem Fehler kleiner als [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Nähert den angegebenen Wert an einen Bruch.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Eine rationale Zahl mit einem Fehler kleiner als [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Nähert den angegebenen Wert an einen Bruch.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | double | Der Wert. |
| epsilon | double | Der zulässige Fehler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Eine rationale Zahl mit einem Fehler kleiner als <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Nähert den angegebenen Wert an einen Bruch.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | float | Der Wert. |
| epsilon | double | Der zulässige Fehler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Eine rationale Zahl mit einem Fehler kleiner als <paramref name="epsilon" />. |


