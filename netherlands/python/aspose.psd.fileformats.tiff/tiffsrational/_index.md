---
title: "TiffSRational-klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initialiseert een nieuw exemplaar van de klasse [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initialiseert een nieuw exemplaar van de klasse [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| EPSILON [statisch] | double | r | De epsilon voor breukberekening |
| noemer | int | r | Haalt de noemer op. |
| teller | int | r | Haalt de teller op. |
| value | float | r | Haalt de float-waarde op. |
| value_d | double | r | Haalt de double-waarde op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Benadert de opgegeven waarde tot een breuk. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Benadert de opgegeven waarde tot een breuk. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Benadert de opgegeven waarde tot een breuk. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Benadert de opgegeven waarde tot een breuk. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initialiseert een nieuw exemplaar van de klasse [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initialiseert een nieuw exemplaar van de klasse [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| teller | int | De teller. |
| noemer | int | De noemer. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initialiseert een nieuw exemplaar van de [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | int | De tellerwaarde. |

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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Een rationaal getal met een fout kleiner dan [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Een rationaal getal met een fout kleiner dan [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Een rationaal getal met een fout kleiner dan <paramref name="epsilon" />. |


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
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Een rationaal getal met een fout kleiner dan <paramref name="epsilon" />. |


