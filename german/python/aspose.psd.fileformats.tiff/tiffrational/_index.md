---
title: "TiffRational Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse. |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse. |
| [TiffRational(value)](#TiffRational_value_3) | Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| EPSILON [statisch] | double | r | Das Epsilon für die Bruchberechnung |
| Nenner | uint | r | Liefert den Nenner. |
| Zähler | uint | r | Liefert den Zähler. |
| Wert | float | r | Liefert den Float-Wert. |
| value_d | double | r | Liefert den Double-Wert. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Nähert den angegebenen Wert an einen Bruch. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Nähert den angegebenen Wert an einen Bruch. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Nähert den angegebenen Wert an einen Bruch. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Nähert den angegebenen Wert an einen Bruch. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse.

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zähler | uint | Der Zähler. |
| Nenner | uint | Der Nenner. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initialisiert eine neue Instanz der [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Wert | uint | Der Zählerwert. |

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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Eine rationale Zahl mit einem Fehler kleiner als [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Eine rationale Zahl mit einem Fehler kleiner als [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Eine rationale Zahl mit einem Fehler kleiner als <paramref name="epsilon" />. |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Eine rationale Zahl mit einem Fehler kleiner als <paramref name="epsilon" />. |


