---
title: "Classe TiffSRational"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.fileformats.tiff/tiffsrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffSRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffSRational()](#TiffSRational__1) | Initialise une nouvelle instance de la classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(nominator, denominator)](#TiffSRational_nominator_denominator_2) | Initialise une nouvelle instance de la classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |
| [TiffSRational(value)](#TiffSRational_value_3) | Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [statique] | double | r | L’epsilon pour le calcul de fraction |
| dénominateur | int | r | Obtient le dénominateur. |
| numérateur | int | r | Obtient le numérateur. |
| valeur | float | r | Obtient la valeur flottante. |
| value_d | double | r | Obtient la valeur double. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approxime la valeur fournie en une fraction. |


### Constructor: TiffSRational() {#TiffSRational__1}


```
 TiffSRational() 
```

Initialise une nouvelle instance de la classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

### Constructor: TiffSRational(nominator, denominator) {#TiffSRational_nominator_denominator_2}


```
 TiffSRational(nominator, denominator) 
```

Initialise une nouvelle instance de la classe [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| numérateur | int | Le numérateur. |
| dénominateur | int | Le dénominateur. |

### Constructor: TiffSRational(value) {#TiffSRational_value_3}


```
 TiffSRational(value) 
```

Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | int | La valeur du numérateur. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | double | La valeur. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un nombre rationnel dont l'erreur est inférieure à [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | float | La valeur. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un nombre rationnel dont l'erreur est inférieure à [TiffSRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | double | La valeur. |
| epsilon | double | L’erreur autorisée. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un nombre rationnel dont l’erreur est inférieure à <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Approxime la valeur fournie en une fraction.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | float | La valeur. |
| epsilon | double | L’erreur autorisée. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffSRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffsrational) | Un nombre rationnel dont l’erreur est inférieure à <paramref name="epsilon" />. |


