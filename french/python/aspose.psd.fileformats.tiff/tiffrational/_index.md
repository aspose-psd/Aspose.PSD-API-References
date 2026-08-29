---
title: "Classe TiffRational"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [statique] | double | r | L’epsilon pour le calcul de fraction |
| dénominateur | uint | r | Obtient le dénominateur. |
| numérateur | uint | r | Obtient le numérateur. |
| valeur | float | r | Obtient la valeur flottante. |
| value_d | double | r | Obtient la valeur double. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approxime la valeur fournie en une fraction. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approxime la valeur fournie en une fraction. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| numérateur | uint | Le numérateur. |
| dénominateur | uint | Le dénominateur. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Initialise une nouvelle instance de la classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeur | uint | La valeur du numérateur. |

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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un nombre rationnel dont l’erreur est inférieure à [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un nombre rationnel dont l’erreur est inférieure à [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un nombre rationnel dont l’erreur est inférieure à <paramref name="epsilon" />. |


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
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un nombre rationnel dont l’erreur est inférieure à <paramref name="epsilon" />. |


