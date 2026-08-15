---
title: "TiffRational-klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse. |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse. |
| [TiffRational(value)](#TiffRational_value_3) | Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| EPSILON [statisch] | double | r | De epsilon voor breukberekening |
| noemer | uint | r | Haalt de noemer op. |
| teller | uint | r | Haalt de teller op. |
| value | float | r | Haalt de float-waarde op. |
| value_d | double | r | Haalt de double-waarde op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Benadert de opgegeven waarde tot een breuk. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Benadert de opgegeven waarde tot een breuk. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Benadert de opgegeven waarde tot een breuk. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Benadert de opgegeven waarde tot een breuk. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse.

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| teller | uint | De teller. |
| noemer | uint | De noemer. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | uint | De tellerwaarde. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Benadert de opgegeven waarde tot een breuk.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | double | De value. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Een rationaal getal met een fout kleiner dan [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Benadert de opgegeven waarde tot een breuk.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | float | De value. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Een rationaal getal met een fout kleiner dan [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Benadert de opgegeven waarde tot een breuk.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | double | De value. |
| epsilon | double | De toegestane fout. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Een rationaal getal met een fout kleiner dan <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Benadert de opgegeven waarde tot een breuk.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | float | De value. |
| epsilon | double | De toegestane fout. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Een rationaal getal met een fout kleiner dan <paramref name="epsilon" />. |


