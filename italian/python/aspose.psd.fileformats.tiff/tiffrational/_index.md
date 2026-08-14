---
title: "Classe TiffRational"
type: docs
weight: 30
url: /it/python-net/aspose.psd.fileformats.tiff/tiffrational/
---

**Summary:** The tiff rational type.

**Module:** [aspose.psd.fileformats.tiff](/psd/python-net/aspose.psd.fileformats.tiff/)

**Full Name:** aspose.psd.fileformats.tiff.TiffRational

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffRational()](#TiffRational__1) | Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(nominator, denominator)](#TiffRational_nominator_denominator_2) | Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
| [TiffRational(value)](#TiffRational_value_3) | Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| EPSILON [statico] | double | r | L'epsilon per il calcolo della frazione |
| denominatore | uint | r | Restituisce il denominatore. |
| numeratore | uint | r | Restituisce il numeratore. |
| value | float | r | Restituisce il valore float. |
| value_d | double | r | Restituisce il valore double. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [approximate_fraction(value)](#approximate_fraction_value_1) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value)](#approximate_fraction_value_2) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_3) | Approssima il valore fornito a una frazione. |
| [approximate_fraction(value, epsilon)](#approximate_fraction_value_epsilon_4) | Approssima il valore fornito a una frazione. |


### Constructor: TiffRational() {#TiffRational__1}


```
 TiffRational() 
```

Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

### Constructor: TiffRational(nominator, denominator) {#TiffRational_nominator_denominator_2}


```
 TiffRational(nominator, denominator) 
```

Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| numeratore | uint | Il numeratore. |
| denominatore | uint | Il denominatore. |

### Constructor: TiffRational(value) {#TiffRational_value_3}


```
 TiffRational(value) 
```

Inizializza una nuova istanza della classe [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | uint | Il valore del numeratore. |

### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_1}


```
 approximate_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | double | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un numero razionale con errore inferiore a [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value)  [static] {#approximate_fraction_value_2}


```
 approximate_fraction(value) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | float | Il valore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un numero razionale con errore inferiore a [TiffRational.EPSILON](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/). |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_3}


```
 approximate_fraction(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | double | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un numero razionale con errore inferiore a <paramref name="epsilon" />. |


### Method: approximate_fraction(value, epsilon)  [static] {#approximate_fraction_value_epsilon_4}


```
 approximate_fraction(value, epsilon) 
```

Approssima il valore fornito a una frazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | float | Il valore. |
| epsilon | double | L'errore consentito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational) | Un numero razionale con errore inferiore a <paramref name="epsilon" />. |


